# Header 1
## Header 2
### Header 3
#### Header 4

*Italic text* or _italic text_

**Bold text** or __Bold text__

***Bold and italic text*** or ___Bold and italic text___

- List item
    - Antoher item
    - yeah
1. First
2. Second

[The Coder Cave](https://www.youtube.com/watch?v=8mKf9rjvjv8)

![The Coder Cave](https://www.65ymas.com/uploads/s1/76/67/77/foto.jpeg2)

> This is a blockquote.  
Y esto vaale valee

| Heather 1 | Heather 2 | Heather 3 |  
| --------- | --------- | --------- |  
| tabla | jbjs | ksdnks |
| tabla | jbjs | ksdnks |
| tabla | jbjs | ksdnks |
| tabla | jbjs | ksdnks |  

---  

- [ ] Incomplete task.  
- [x] Completed task.

`Incline code`  

```java
package unidad01;

import java.util.Scanner;

public class AS {

	public static void main(String[] args) {
		//INTENTO DE REGLA DE TRES.
		System.out.println("Realicemos una regla de tres!");
		Scanner scan = new Scanner(System.in);
		System.out.print("Introduzca el valor a: ");
		double a = scan.nextDouble();
		System.out.print("Introduzca el valor b: ");
		double b = scan.nextDouble();
		System.out.print("Introduzca el valor c: ");
		double c = scan.nextDouble();
		double x = (b*c)/a;
		System.out.print("El resultado de la operación es " + x);
		scan.close();
							
	}

}


