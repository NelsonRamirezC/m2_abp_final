💼 Continuamos con nuestra wallet, la idea es incorporar dinamismo a las pantallas de inicio de sesión, menú principal y últimos movimientos.


💡 Desafío: Crea una billetera digital básica que incluya las siguientes pantallas:


Pantalla de inicio de sesión (login.html):


1. Agrega un evento al botón "Iniciar sesión".

Implementa la funcionalidad de validar las credenciales ingresadas utilizando JavaScript. 
Si las credenciales son correctas:
- mostra un mensaje de éxito y redirige a la pantalla del menú principal (menu.html). CHECK
- Si las credenciales son incorrectas, mostrar un mensaje de error. CHECK 

El boton de menu principal no debe verse en la pantalla login, ya que ahora tenemos que poder redirigir a la pantalla menú con el inicio de login


Pantalla del menú principal (menu.html):


- Agregar eventos a estos tres botones: "Depositar", "Enviar Dinero" y "Últimos Movimientos" para que al hacer clic aparezca una leyenda que diga, redirigiendo a “nombre de la pantalla seleccionada”. EJemplo: redirigiendo a últimos movimientos. CHECK 

- Implementa la funcionalidad de los botones utilizando JavaScript para redirigir a las pantallas correspondientes. CHECK


Pantalla de depósito (deposit.html):


- Agregar evento al botón "Realizar depósito". CHECK

- Implementa la funcionalidad de actualizar el saldo de la cuenta con el monto depositado y mostrar el nuevo saldo en la pantalla del menú principal al hacer clic en "Realizar depósito". (Incrementando el monto inicial) CHECK


Pantalla de enviar dinero (sendmoney.html):


Agregar evento al botón "Agregar nuevo contacto" para abrir un formulario emergente donde se pueden agregar nuevos contactos.

Este formulario debe pedir los siguientes datos:

Nombre y apellido

número de CBU

Alias

Nombre del Banco

Al seleccionar un contacto y hacer clic en "Enviar dinero", mostrar un mensaje de confirmación y actualizar el saldo de la cuenta en la pantalla del menú principal.


Pantalla de Últimos movimientos (transactions.html):

mostrar una lista con los movimientos realizados y reflejar los detalles de ultimas operaciones



Implementa la interactividad de las pantallas utilizando JavaScript:


Captura los eventos de los formularios y botones mediante JavaScript.

Valida los campos del formulario antes de enviar los datos.

Actualiza dinámicamente la información en la pantalla del menú principal cuando se realizan depósitos, envíos de dinero, etc.

💡Recorda que cada pantalla debe estar en su propio archivo HTML y debes enlazarlos correctamente entre sí utilizando enlaces o redirecciones según lo indique la consigna. Además, utiliza CSS y Bootstrap para personalizar la apariencia de las pantallas y hacerlas atractivas y responsive.