Este material se usa para trabajar en el
Curso de CSS: Flexbox y layouts responsivos.

Anotaciones empleadas durante el aprendizaje:
Curso de CSS: Flexbox y layouts responsivos.

	Video 03 
Caja flexible: cabecera.
We saw what "flex-box" are; They are literally fexibble boxes that allow page elements to be moved and arranged depending on the browser where the content is displayed. The way to initially work with "flex-box" is to set the display: flex. 

	Video 05
Aling-items: cabecera.
Video example:
display: flex; /*Initialize the flex-box*/
justify-content: space-between;  /*Elemnts are align with equals space between them*/
align-items: center; /*The elements are focused on the container*/
position: fixed; /*The position is set*/
top:0; /*Cabecera´s position with respect to the top edge of the page*/

	Video 07
Estilos con @media.
It basically explains what breakpoints are, which are conditions that we can apply for a given style whether or not it is applied, depending on the behavior or characteristics of the browser on the device it is running on , we can configure how the elements are displayed.
Video example: 
@media(min-width:834px){   /* Working styles with Media Queries, it is restricted to the minimum screen width being: 834px */
    .cabecera__buscar__item{  /* Once the condition is met, the style is created */
        display:block;
    }
}
Layout: visual arrangement of elements
Media queries: CCS system to apply restrictions. 
Breakpoints: are the width measurements we use for responsive design. 

	Video 02
Lineas y columnas: flex-direction.
    flex-direction: column; /* Establishes that child elements are placed on top of each other*/

	Video 03
Ajuste de columnas y filas: flex-wrap.
flex-flow: column wrap; /* Combine flex-direction: column; + flex-wrap: wrap; */

a) display: flex : The containers expand to occupy the entire width and are placed one on the top of the other in a column.
b) display: inline-flex : The containers do not occupy the entire width, they are displayed on the same line. 

	Video 05
Aplicando gap.
white-space: nowrap; /* The text is not wrapped, that is, it is not broken into several lines. */
    overflow: scroll; /* Adds an scroll to the container. */
    gap: 16px; /* In the flexbox context it gives space between the children of the flex container. */ 

	Video 02
Fijando el menu mobile.
 bottom: 0% ; /* Distance from the bottom edge of the page. */
    height: 75px; /* Set the maximum height. */
    width: 100%; /* Set the maximun width, in this case setting 100% makes it occupy the entire screen. */

	Video 03
Mobile: elementos en linea.
.menu_lista:nth-child(2), /* Select the second element of the list with the class 'menu_lista'. */
These pseudo classes are used to select sibling elements of the same container.


	Video 04 
Mobile: align-self.
   justify-content: space-around; /* Evenly distributes space between elements within a container */

    align-self: center; /* Individually aligns an element within a flex container. */


Links mas importantes:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://www.aluracursos.com/blog/puntos-de-ruptura-en-el-diseno-responsivo
https://www.w3schools.com/css/css_rwd_mediaqueries.asp
