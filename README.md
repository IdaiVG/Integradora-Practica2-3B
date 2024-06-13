# Integradora-Practica2-3B
En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones, Documentación, Desarrollo colaborativo y Respaldo del proyecto para la asignatura de Integradora I

## Comandos Básicos para la documentación, utilizando el estándar (md)
Markdown es el estándar utilizado por Git y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

### 1. Encabezados o Titulos (HEADERS)
Para poder realizar una buena documentación del proyecto debemos, distribuir correctametne los contenidos, para poder delimitar o hacer énfasis (enfatizar), es decir, resaltar las secciones importantes, podemos utilizar los siguientes:

# Encabezado de Nivel 1 -Similar a H1 en HTML
## Encabezado de Nivel 2 -Similar a H1 en HTML
### Encabezado de Nivel 3 -Similar a H1 en HTML
#### Encabezado de Nivel 4 -Similar a H1 en HTML
##### Encabezado de Nivel 5 -Similar a H1 en HTML
###### Encabezado de Nivel 6 -Similar a H1 en HTML
####### Encabezado de Nivel 7 -Solo 6 son los niveles permitidos


### 2. Separadores (SEPARATORS)
Si se desea marcar una separación más visual de contenidos podemos utilizarlos indicando 3 caracteres de "-" continuos, en el maquetado.
EJEMPLO:
--- 
*Esto es similar a un tag de < HR > en HTML.

### 3. Párrafos (PARAGRPAHS)
Son utilizados para presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.

EJEMPLO
Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 este texto pertenece al parrafo 1Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 este texto pertenece al parrafo 1Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 
Este texto pertenece al párrafo 1Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 este texto pertenece al parrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 este texto pertenece al parrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al parrafo 1 este texto pertenece al parrafo 1


Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 este texto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 este texto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 este texto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 este texto pertenece al parrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al parrafo 2 este texto pertenece al parrafo 2

Lo que en una página utilizariamos usando la etiqueta <p>

También podemos aplicar estilos basicos de alineación :

Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto

<p align = "right">
Este párrafo esta alineado a la derecha utilizando la propiedad de lineación Este párrafo esta alineado a la derecha utilizando la propiedad de alineación Este párrafo esta alineado a la derecha utilizando la propiedad de lineación Este párrafo esta alineado a la derecha utilizando la propiedad de alineación Este párrafo esta alineado a la derecha utilizando la propiedad de lineación Este párrafo esta alineado a la derecha utilizando la propiedad de alineación Este párrafo esta alineado a la derecha utilizando la propiedad de lineación Este párrafo esta alineado a la derecha utilizando la propiedad de alineación Este párrafo esta alineado a la derecha utilizando la propiedad de lineación Este párrafo esta alineado a la derecha utilizando la propiedad de alineación

<p align = "center">
Este párrafo esta centrado utilizando la propiedad de lineación Este párrafo esta centrado utilizando la propiedad de alineación Este párrafo esta centrado utilizando la propiedad de lineación Este párrafo esta centrado utilizando la propiedad de alineación Este párrafo esta centrado utilizando la propiedad de lineación Este párrafo esta centrado utilizando la propiedad de alineación Este párrafo esta centrado utilizando la propiedad de lineación Este párrafo esta centrado utilizando la propiedad de alineación Este párrafo esta centrado utilizando la propiedad de lineación Este párrafo esta centrado utilizando la propiedad de alineación

<p align = "justify">
Este párrafo estará justificado utilizando la propiedad de lineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de lineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de lineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de lineación Este párrafo estará justificado utilizando la propiedad de alineación

### Texto enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que deseamos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### 4. Texto en negrita (BOLD)
Para poner el texto en negritas este debera estar encerrado entre *

EJEMPLO

TEXTO TEXTO TEXTO TEXTO TEXTO *Texto importatne* TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO

##### Texto en cursiva (ITALIC)
Para poder poner el texto en cursiva, este deberá ser encerrado con la 
Texto Texto Texto Texto <i>Texto Importante</i> Texto Texto Texto Texto Texto Texto

##### Texto en cursiva y negrita(BOLD/ITALIC)
Para poder poner el texto en cursiva y negrita, este deberá ser encerrado con la 
Texto TextoTexto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto
###### Subrayado (UNDERLINE)
Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bine markdown no tiene un atajo o codificación rápida podemos utilizarl el estilo estándar de HTMl usando el tag /<ins> y cerrando con /</ins>

**Ejemplo**
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto cursivo* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto /<ins>Texto Texto Texto /</ins> Texto Texto Texto Texto Texto Texto 

# Integradora-Practica03
Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación

### 5. Cuadros para códigos o reseñas (BLOCKQUOTES)
Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (/>)

**EJEMPLO**
Para listar las carpetas y archivos desde una terminal de sistemas operativos Windows debemos ingresar el comando:
c:dir
Después oprimimos la tecla "Enter".

También podemos ingresar textos multilínea

**Ejemplo**

>Aquí se ingresa un conjunto de instrucciones
>para explicar al usuario, como instalar el
>software que hemos diseñado.

Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

**Ejemplo**
**Pasos para Instalar la Base de Datos**
> - Descargar MySQL Server del Sitio Oficial
> - Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario ***root***
> - Descargamos el archivo de respaldo de la base de datos (.sql)
> - Restauramos la Base de Datos Usando el comando *MySQL *
>> c:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password\<respaldo.sql

### 6. Listas Ordenadas y Listas Desordenadas
Si en nuestra documentación necesitamos incluir información en modo de lista, un elemneto tras otro, podemos hacerlo utilizando los números con un punto decimal si las deseamos ordenadas con un guión medio - si solo queremos una viñeta.

**Ejemplo**
Para crear tu primer repositorio en GitHub deberás:
1. Contar con cuneta HitHub.
2. Dar click en el boton: **Nuevo repositorio*
3. Asignarle un Nombre a tu repositorio, por ejemplo: *practica03-3b*
4. Asignarle un nivel de privacidad entre
   - **Públuico:** Si quieres que esté disponible para todos los usuarios.
   - **Privado:** Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado : *READNE.md*
6. Definir si habrá exclusiones de archivo a través del archivo *.gitgnore*
7. Guardar los cambios.

#### 7. Ligas(Hipervínvulos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y que se maquetan utilizando los corchetes \[\], inmediatamente despues pondrémos la liga de referencia entre parentesis ().

**Ejemplo**
Mi buscador favorito es: [Google](http://www.google.com).

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizar los simbolos \< \>

**Ejemplo**
Documentación creada por: ***Guadalupe Idai Vargas Galindo*** 

<230574@utxicotepec.edu.mx>

<http://utxicotepec.edu.mx>


#### 8. Imágenes
Puede mostrar una imágen agregando ! y ajustar el texto alternativo en [ ]. El texto alternativo es un texto corto equivalente a la información de la imágen. Luego escribe el vinculo de la imágen entre paréntesis ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)






GitHub admite la inserción de imágenes en incidencias, solicitudes de incorporación de cambios, debates, comentarios y archivos .md. Puedes mostrar una imagen desde tu repositorio, agregar un enlace a una imagen en línea o cargar una imagen. Para obtener más información, consulte "Carga de recursos".


#### 9. Tabla (Tables)
Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el carácter \| para delimitar las columnas y \- para delimitar filas.

**Ejemplo:**

| Encabezado 1 | Encabezado 2| Encabezado 3| Encabezado 4|
|--------------|-------------|-------------|-------------|
|Fila 1 celda 1|Fila 1 celda 2|Fila 1 celda 3|Fila 1 celda 4|
|Fila 2 celda 1|Fila 2 celda 2|Fila 2 celda 3|Fila 2 celda 4|
|Fila 3 celda 1|Fila 3 celda 2|Fila 3 celda 3|Fila 3 celda 4|

En el caso de necesitar la fusión de celdas en columnas usaremos la propiedad "colspan" del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad "rowspan".

**Ejemplo**

|Encabezado 1|Encabezado 2|Encabezado 3| Encabezado 4|
|------------|------------|------------|-------------|
|Fila 1 Celda 1|Fila 1 Celda 2| Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1 <td colspan=2> Fila 2 Celda 2| Fila 2 Celda 3|
|Fila 3 Celda 1|Fila 3 Celda 2| Fila 3 Celda 3|Fila 3 Celda 4|
|             |Fila 4 Celda 2|Fila 4 Celda 3| Fila 4 Celda 4|
|             |Fila 5 Celda 2|Fila 5 Celda 3| Fila 5 Celda 4|
|Fila 6 Celda 1|Fila 6 Celda 2| Fila 6 Celda 3|Fila 6 Celda 4|

Dado que en el ejemplo pasado usando markdown no se puede realizar la fusión de filas debemos utilizar el estandar de HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas y <td> para las celdas, y en ellos utilizar la propiedad de "colspan" y "rowspan".

**Ejemplo**

<table>
   <tr>
      <th>Encabezado 1</th>
      <th>Encabezado 2</th>
      <th>Encabezado 3</th>
      <th>Encabezado 4</th>
   </tr>
   <tr>
      <td>Fila 1 Celda 1</td>
      <td>Fila 1 Celda 2</td>
      <td>Fila 1 Celda 3</td>
      <td>Fila 1 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 2 Celda 1</td>
      <td colspan=3 align="center">Fila 2 Celda 2</td>
   </tr>
   <tr>
      <td rowspan=3>Fila 3 Celda 1</td>
      <td>Fila 3 Celda 2</td>
      <td>Fila 3 Celda 3</td>
      <td>Fila 3 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 4 Celda 2</td>
      <td>Fila 4 Celda 3</td>
      <td>Fila 4 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 5 Celda 2</td>
      <td>Fila 5 Celda 3</td>
      <td>Fila 5 Celda 4</td>
   </tr>
   <tr>
      <td>Fila 6 Celda 1</td>
      <td>Fila 6 Celda 2</td>
      <td>Fila 6 Celda 3</td>
      <td>Fila 6 Celda 4</td>
   </tr>
</table>
