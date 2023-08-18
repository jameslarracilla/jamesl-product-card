# jamesl-product-card

This is a test for npm deploy.

### James Larracilla

```
import { ProductCard, ProductImage, ProductButtons, ProductTitle } from 'jamesl-product-card;
```

```
<ProductCard
        product={product}
        initialValues={{ count: 4, maxCount: 10 }}
      >
        {({ reset, count, isMaxCountReached, increaseBy }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>
```
