<h1>¿Porque se comporta exactamente igual que si lo hubiera cambiado por HTML puro?</h1>
<h2>Se ve igual que con HTML puro porque React al final lo traduce todo a HTML normal. O sea, el JSX que escribimos no llega directo al navegador,\
React lo convierte en funciones que al final generan HTML estandar, y eso es lo que el navegador entiende y muestra.</h2>

<h1>¿Qué significa className en React? ¿las props tienen un limite? ¿Quién define las props?</h1>
<h2>En React, className se usa para asignar clases de CSS a los elementos, ya que no se puede usar la palabra class porque esta reservada en JavaScript.
  Las props no tienen un limite establecido, se pueden pasar todas las que quieras, aunque es mejor no exagerar para que el codigo sea mas facil de leer y mantener. 
  Las props las define el componente padre y se las pasa al componente hijo, sirviendo como una forma de comunicacion entre ellos y permitiendo que los componentes sean mas reutilizables y personalizados.</h2>
