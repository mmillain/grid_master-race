# Grid Master Race
Demostración de diseños responsivos con grid

## ¿Que es Grid?
Grid es una técnica de diseño de cuadrícula de CSS en donde no necesitamos nada extra para hacerlo funcionar, evitamos maquetar con elementos float y hacemos un simple uso con solo declarar la propiedad display: grid ya estamos aptos para utilizar dicha técnica.

## Compatibilidad con los navegadores
Es muy importante ver la siguiente tabla ya que si necesitamos hacer un diseño para navegadores antiguos vamos a tener que aplicar cierta lógica para acomodar nuestros estilos

## ¿Qué podemos hacer con Grid?

Algo como esto:
![Alt text](./images/caniuse.png?raw=true "CanIuse")

### Compatibilidad:

![Alt text](./images/caniuse.png?raw=true "CanIuse")


## Ejemplo:

En esta demostración vamos a ver como hacer un diseño responsivo, colocando elementos de forma ordenada e indicando width mínimos y máximos.

### Principales propiedades en este ejemplo:

- **display: grid**
-- Los items se ordenan con un full width en cada espacio del container

- **grid-template-rows:** _( px | em | rem | % | fr | functions like repeat and it-content )_
-- Con esto indicamos valores para nuestras filas

- **grid-template-columns:** _( px | em | rem | % | fr | functions like repeat and it-content )_
-- Con esto indicamos valores para nuestras columnas- **grid-gap**: _( px | em | rem )_
-- Espacio (margin) entre los elementos por cada elemento sin contar el espacio por sobre los bordes del container

- **repeat:** _( [ < positive-integer > | auto-fill | auto-fit ] , < track-list > )8r4 _
-- Representa un fragmento repetido de la lista de vías, permitiendo que un gran número de filas que muestran un patrón recurrente se escriban de una manera más compacta.

## Recursos:
- https://learncssgrid.com/ (Recomendado)
- https://caniuse.com/#search=grid (Compatibilidad de grid)
- https://lenguajecss.com/p/css/propiedades/grid-css (Doc en español)
- https://youtu.be/bam83Xv4VMA (Responsive CSS Grid with NO MEDIA QUERIES!)
