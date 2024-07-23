# do-product-card-alejocarpa

Este es un paquete de pruebas de despliegue en NPM

### Alejandro Cardenas

## Ejemplo
```
import {
    ProductCard,
    ProductImage,
    ProductTitle,
    ProductButtons
} from 'do-product-card'
```
```
<ProductCard
    product={product}                
    initialValues = {{
        count: 4,
        maxCount: 10
    }}
>
    {
        ({ reset, count, increaseBy, isMaxCountReached }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />                                    
            </>
        )
    }
</ProductCard>
```