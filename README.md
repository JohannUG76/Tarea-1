## Practica de interface

La nueva interfaz de práctica del tercer semestre en la Universidad de Guayaquil será una plataforma innovadora y dinámica, cuidadosamente diseñada para optimizar el aprendizaje de los estudiantes. Contará con herramientas interactivas y una amplia gama de recursos multimedia, fomentando así un ambiente colaborativo y estimulante para el estudio. ¡Prepárate para sumergirte en una experiencia educativa verdaderamente enriquecedora e innovadora.

## Imagen de ejemplo del Proyecto

![image](https://github.com/JohannUG76/Tarea-1/assets/169223501/d815fb8a-4e35-4e84-aa29-0106f1d07d93)


## Textfield

El proyecto ha sido diseñado meticulosamente, incluyendo un TextField que se ajusta fielmente al diseño establecido. Este componente se ha posicionado tanto vertical como horizontalmente dentro del AnchorPane según las especificaciones requeridas. Luego, se ha integrado al AnchorPane para que sea visible en la interfaz de usuario. Esta configuración cuidadosa garantiza que el TextField esté correctamente ubicado en el diseño, asegurando una experiencia de usuario coherente y fácil de usar. La atención meticulosa a los detalles en la disposición de los elementos refuerza la calidad y la estética general de la interfaz, proporcionando una experiencia de usuario profesional y satisfactoria.

##   ListView

El código proporcionado inicializa un ListView vacío y lo coloca cuidadosamente dentro del AnchorPane. Se especifica su ubicación precisa en la esquina superior izquierda, desplazado 20.0 unidades desde la parte superior y 220.0 unidades desde la izquierda. Este ListView es fundamental para mostrar contenido dinámico en la interfaz de usuario, como listas de elementos seleccionables. Al agregarlo al AnchorPane, se garantiza su visibilidad y su correcta integración en la estructura de la interfaz. Esta disposición meticulosa asegura una presentación organizada y coherente del contenido, mejorando así la experiencia del usuario al interactuar con la aplicación. La posición estratégica del ListView contribuye a una navegación intuitiva y eficiente dentro de la interfaz, lo que mejora la usabilidad general del sistema.

## Metodo label

En el método agregarLabels, se utiliza repetidamente el método agregarLabel para añadir varias etiquetas al AnchorPane. Cada llamada al método especifica el texto y la posición de una etiqueta diferente.

## Agregar el label

El método agregarLabel crea un objeto Label con el texto proporcionado y luego utiliza los métodos estáticos setTopAnchor y setLeftAnchor de la clase AnchorPane para establecer su posición en la parte superior e izquierda del AnchorPane. Finalmente, el método agrega el Label al AnchorPane llamando a getChildren().add(label).
