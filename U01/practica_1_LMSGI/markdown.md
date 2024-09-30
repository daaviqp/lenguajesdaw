# Introducción a los lenguajes de marcas. Markdown.
## ¿Qué son los lenguajes de marcas?  
 Estos llamados *lenguajes de marcas* son **sistemas de codificación** que usan etiquetas para definir el formato y la estructura de los documentos. Estas etiquetas, proporcionan la información adicional necesaria sobre la estructura del texto o su formato de presentación. A continuación, veremos una clasificación de los diferentes lenguajes de marcas;  
>1. **_Lenguajes de marca de propósito general:_**
   >> - **HTML (HyperText Markup Language):** Es el lenguaje de marcas más famoso y más usado para crear páginas web.
    >> - **XML (eXtensible Markup Language):** Este lenguaje es muy flexible y permite definir etiquetas personalizadas, es mayoritariamente usado para almacenar y transportar datos.
>2. **_Lenguajes de marcas de documentos:_**
   >> - **LaTeX:** Este permite una alta calidad tipográfica y es usado principalmente en documentos técnicos y científicos.
   >> - **Markdown:** Es el lenguaje de marcas ligero más usado para formatear texto en web. Es muy popular en plataformas como GitHub. Será nuestro protagonista del día de hoy.
>3. **_Lenguajes de marcas de presentación:_**
   >> - **CSS (Cascading Style Sheets):** Este no es un lnguaje de marcas en sí, pero es muy usado junto a HTML para definir la presentación de los documentos web.
---  
>Como he comentado antes, *Markdown* será nuestro protagonista hoy. Conoceremos qué es, por qué y cómo usarlo.  

---
## ¿Qué es Markdown?
Markdown es un lenguaje **de marcado ligero** que fue diseñado para ser fácil de leer y aún más fácil de escrbir, ya que este convierte **texto plano** en **lenguaje HTML** de manera muy eficiente. Debido a esto, este lenguaje se convierte en un gran atractivo para un amplio público. Este lenguaje puede sonarnos, ya que es muy usado por escritores, profesores, creadores de contenido en redes sociales, desarrolladores, etc. También, si hemos usado alguna vez **GitHub**, es probable que nos hayamos cruzado con algún archivo escrito en Markdown (estos, acabados en ".md"). Aparte de esto, es muy compatible con **plataformas de gestión de contenidos** (CMS Hub, WordPress, Drupal...), **sistemas de control de versiones** (como GitHub) y distintos **entornos de desarrollo** (NetBeans, Eclipse, Visual Studio Code...).  

![alt text](https://geekytheory.com/content/images/size/w2000/2014/03/markdown.png)  

## ¿Por qué usar Markdown?
Markdown, como ya se ha mencionado anteriormente, es un lenguaje fácil de usar y es muy accesible para una gran mayoría de personas. Además de ser fácil de leer y escribir, podemos tener siempre un respaldo de nuestros documentos y archivos, ya que es compatible con GitHub. Esto hace que siempre podamos tener a salvo nuestros archivos. Estas son algunas de las tantas ventajas que obtenemos al usar Markdown:
>- **Simplicidad y legibilidad:** Permite crear documentos bien estructurados sin necesidad de aprender lenguaje de programación complejo.
>- **Conversión a HTML:** Es muy fácil convertir documentos Markdown a HTML, esto es muy útil para la publicación en la web.
>- **Rapidez:** Es mucho más rápido escribir en Markdown que en otros lenguajes de marcado, esto, ahorra mucho tiempo a los que lo usan.
>- **Compatibilidad:** Muchos sistemas de control de versiones, como GitHub, soportan Markdown. Esto facilita la colaboración y revisión de documentos.

## ¿Cómo usar Markdown?
Markdown nos permite crear documentos de texto formateados sin la necesidad de trabajar con editores de texto especiales. Este lenguaje de marcas de documentos es especialmente famoso debido a que es muy sencillo de usar. Podemos encontrar miles de vídeos y de tutoriales en internet, además de [chuletarios](https://www.markdownguide.org/cheat-sheet/#extended-syntax) como este, el los cuáles nos explican lo sencillo que es usar Markdown y todas sus ventajas. Además, podemos escribir mientras vemos una previsualización de cómo va a quedar. Para ello, podemos usar webs como [esta](https://markdownlivepreview.com/), o simplemente desde nuestro entorno de desarrollo, buscando la opción de previsualización.
Este es un lenguaje completo, ya que nos permite multitud de opciones, como agregar **texto en negrita** o *texto en cursiva*, hacer listas ordenadas y no ordenadas, como las que he usado al principio el documento. También nos permite añadir imágenes y bloques de código preformateado;

``` java
package unidad02;

import java.util.Scanner;

/** Introduciendo un año de nacimiento, el programa dirá si el usuario es:
 * bebé: 0-2 años
 * niñ@: 3-11 años
 * ...
 */

public class EtapaVital {

	public static void main(String[] args) {
		// PROGRAMA EDAD.
		
		Scanner scan = new Scanner(System.in);
		System.out.print("Introduce tu año de nacimiento: ");
		int anio = scan.nextInt();
		int edad = 2024-anio;
		if (edad < 0) {
			System.err.println("No se puede introducir un año mayor al actual");
		} else if (edad <= 2) {
			System.out.println("Eres un bebé");
		} else if (edad <= 11) {
			System.out.println("Eres un niñ@");
		} else if (edad <= 18) {
			System.out.println("Eres un adolescente");
		} else if (edad <= 65) {
			System.out.println("Eres un adulto");
		} else if (edad <= 65) {
			System.out.println("Eres un anciano");
			scan.close();
		}
	
	}

} 
```
Aparte de esto también nos permite añadir tablas:
| ID | NOMBRE | PAÍS |
| -  | -      | -    |
| 1 | Carlos | España|
| 2 | Luis | Argentina|
| 3 | Alejandro | México|  
--- 
## Conclusión:
A modo de conclusión, Markdown es un lenguaje muy fácil y versátil que puede ser usado por una gran mayoría de público ya que es muy sencillo de aprender. Este lenguaje yo lo recomendaría si eres estudiante o creas contenido en internet, ya que es compatible con muchos sistemas de control de versiones. Esto facilita mucho el poder colaborar con otros compañeros. Esto puede ser muy útil para, por ejemolo, para una página web en común. Todos pueden trabajar de una forma sencilla sin que haya ninguna complicación.


