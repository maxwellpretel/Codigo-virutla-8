# Posicionamiento en CCS
##`position:relative;`  

- puedo mover a un elemento con 2 ejes de referencia:
    -top: cantidad de pixeles desde el extremo superior
    -left: cantidad de pixeles desde el extremo izquierdo
- Si el elemento es movido, su espacio original se respeta por los demás elementos
-Un elemento también puede tener `position:relative` cuando tiene hijos con `postition:absolute` de tal forma que dichos hijos, no se salgan del área del padre

## ´position:absolute´

- El elemento sale del contexto de los demás elementos(tiene el efecto de florae sobre los demás elementos)
- Los elementos que no tienen `position:absolute` ocupan el espacio de este elemento.
- puedo mover al elemento con 4 ejes de referencia:
    -top, left, rigth y bottom
- obligatorioamento debemos especificar alemenos 2 ejes de referencia
-el elementos `absolute` se mueve copn referencia alñ próximo padre directo que tenga ´position:realtive´

- de no cuplirse el anterior punto, el padre de referencia sería el elemetno HTML

## ```position:fixed```

-El elemento es posicionado con referencia al viewport( el área de visualización de la página)
-Es decir, si el scroll se mueve por ejemplo, el elemento se mantiene fijado con rteferencia al Viewport
-se ouede anclar hasta con 4 puntos de referenca: top, left, rigthy bottom