# JeSpañol 
### JavaScript en Español
###### por <a href="https://Codigo-AR.github.io/">Codigo-AR</a>

## Empezar a usar JeSpañol
#### Lo primero es incluir este CDN antes de cerrar el `body` y antes de los demás `script`
```
<script src="https://CodigoAR-JeS.github.io/js/JeSpañol.min.js"></script>
```

Por ejemplo:

    <!DOCTYPE html>
    <html lang="es>
    <head>
        <!-- META TAG OBLIGATORIO -->
        <meta charset="UTF-8">
        
        <!-- Tu HTML -->
        
    </head>
    <body>
        
        <!-- Tu HTML -->
        
        <!-- CDN JeSpañol OBLIGATORIO -->
        <script src="https://CodigoAR-JeS.github.io/js/JeSpañol.min.js"></script>
        
        <!-- Tus SCRIPS -->
        
    </body>
    </html>

#### Lo segundo es comprobar que JeSpañol funciona por lo tanto escribe este código en la consola de tu web:
```
consola.mostrar($('html')[0])
```

esto nos debe mostrar en la consola algo cómo esto:
```
 >  consola.mostrar($('html')[0])                  
___________________________________________________
      <html lang="es">              JeSpañol.js:49 
       >> <head>...</head>                         
       >> <body>...</body>                         
      </html>                                      
___________________________________________________
 <· undefined                                       
```

#### Lo tercero es leerse la <a href="https://CodigoAR-JeS.github.io/docs/">documentación del funcionamiento de JeSpañol</a>
