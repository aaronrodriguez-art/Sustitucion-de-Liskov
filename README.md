# Sustitucion-de-Liskov
Principio Sustitucion de Liskov de SOLID


Este principio se aplica asegurando que las clases hijas puedan usarse en lugar de la clase padre sin alterar el funcionamiento del programa:

- La clase base `Producto` define un método virtual llamado `AplicarDescuento()`.
- Las clases hijas (`Fisico` y `Digital`) heredan de `Producto` y sobrescriben (*override*) ese método con su propia lógica y porcentajes de descuento específicos.
- En el código principal (`main`), podemos trabajar con cualquiera de los objetos derivados llamando a sus métodos de forma transparente y segura, garantizando que el comportamiento polimórfico funcione a la perfección.
