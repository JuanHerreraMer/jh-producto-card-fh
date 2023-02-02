# Do-product-card

Este es un paquete de pruebas de despliegue en NPM

### Juan Herrera

## Ejemplo

```
import {
    ProductButtons,
  ProductCard,
  ProductImage,
  ProductTitle
} from 'jh-producto-card-fh'

```

```
<ProductCard 
        product={product}
        initialValues={{
          count: 0,
          // maxCount: 10
        }}
      >
        {
          ({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
            <>
              <ProductImage />
              <ProductTitle />
              <ProductButtons />
            </>
          )
        }

      </ProductCard>

```