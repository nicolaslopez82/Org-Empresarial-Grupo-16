# Org-Empresarial-Grupo-16
FORO GRUPAL TEMA 2 Desarrollo de T.P tema: 2 ( Información para la toma de decisiones ))

# Tarea Tema 2 - Tarea a Desarrollar:
- Vamos a suponer que Ustedes son un grupo de gerentes de una Empresa, la cual se encuentra frente a una problemática y requiere de información para su solución. Les solicitan que elaboren y presenten un informe donde conste:
---
---

- #### Una breve descripción de la empresa (rubro, nombre comercial, posicionamiento en el mercado, etc.).

	- Rubro: E-Rubro commerce
	- Nombre Comercial: ACME
	- Posicionamiento en el mercado: Nivel Nacional

---	

- #### Función de cada gerente (puesto y área en la cual se desarrolla su función)

	- Gerente Gral.
	- Gerente de Desarrollo
	- Gerente Comercial
	- Gerente RRHH
	- Gerente de Soporte al Cliente

---

- #### Definición del problema, la problemática debe ser coherente y establecer los sectores que están afectados y que van a participar en la resolución del problema.

	- Dentro de nuestra plataforma de E-commerce, tenemos en nuestro servidor, una disponibilidad para 100 usuarios de forma concurrente, llamados de ahora en mas como (UC). 
	
	- En materia comercial, y concurriendo el mes de Septiembre, aun no hemos llegado al 50% de nuestro objetivo comercial y economico (OCE) establecido para el corriente anio. 
	
	- En 2 semanas, estamos ante el evento de Black-Friday, en donde tenemos una ventana de oportunidad de operaciones y ventas estipuladas, que nos acercarian a un 80% de nuestro OCE para este anio.
	
	- **Sin embargo, la disponibilidad de nuestro servidor (100 usuarios de forma concurrente), es muy limitada y no nos permite aprovechar dicho evento de Black-Friday en el cual nuestra disponibilidad deberia ser de unos 5000 (5K) usuarios de forma concurrente. Tener en cuenta que un usuario solo espera en nuestra plataforma, un promedio 1 minuto antes de abandonar la web si no recibe respuesta y o notificacion  alguna.**

	- Segun la informacion recabada, tenemos que coordinar con el gerente de desarrollo una solucion informatica para dicho evento; a su vez, coordinar con el gerente comercial los costos de dicha solucion y metodos de pago, y coordinar con la generencia de RRHH para establecer si contamos con los RRHH necesarios para la solucion, o contratar nuevo personal o capacitar a nuestro personal en forma urgente.

	- La gerencia de Soporte al Cliente debera determinar la disponibilidad de recursos necesarios en conjunto con la generencia de RRHH, para dar el soporte necesario a dichos cliente en el evento programado.


---


- #### Determinar que información necesitará para la solución del problema e indicar cuál seria la información relevante para tomar las decisiones. (En la teoría se explica bien esta tema) 

	- Informacion necesaria para la solucion al problema:
		- Disponibilidad de Usuarios Concurrentes (UC) actual y necesaria para el Black-Friday. **(Relevante)**
		- UC esperados por minuto para el Black-Friday.  
		- Tiempo de espera de UC en nuestras plataformas y plataformas competidoras. 
		- Disponibilidad de UC de nuestros competidores. 
		- Costos de dichas solucion. **(Relevante)**
		- Tiempos de busqueda de informacion, analisis, procesos y resultados de la informacion.
		- Ganancia minima y maxima esperada para dicho evento.
		- Soporte tanto al cliente, como a nuestra plataforma para dicho evento.
		- Solucion temporal o permanente, ya que nuestra disponibilidad de UC luego del evento, no es necesaria que sea de 5k, ya que generaria gastos innecesarios. **(Relevante)**

---

- #### Expliquen que tomo en cuenta para determinar la información relevante.

	 > La informacion que se tomo como relevante, es de un 20% aproximadamente de nuestra infomacion recabada, pero que nos brinda un 80% de solucion. Influenciada por su importancia y urgencia.

---

- #### Establecer la forma en que se tomarían las decisiones para solucionar el problema. (Leer claramente la teoría en el pdf!!)

	- Teoría de la decisión 
	
		> Es una metodología que le indica al hombre como debe decidir plasmando un modelo formal que termina por sugerir la elección optima.

		> Da importancia a las decisiones grupales y a la vez organizacionales, ya que considera que son el resultado de un proceso complejo que une referencias individuales de acuerdo al poder que cada miembro posea dentro de la organización.

	- Decisiones programadas 
	
		- Datos adecuados
		- Datos repetitivos
		- Condiciones estáticas
		- Certeza
		- Previsión 

	- Etapas en el proceso decisorio
		
	    1. Encontrar toda la información necesaria acerca del problema a resolver, para esto se necesita conocer las dimensiones del problema
		
		2. Generar los posibles caminos alternativos y evaluarlos de acuerdo a las referencias de quien debe decidir. En esta etapa que desarrolla la actividad de diseño, se requiere de la creatividad del hombre y de técnicas de estimulación adecuada, para definir las alternativas y evaluarlas.
		
		3. Aplicar un criterio de decisión para elegir la alternativa optima que logre cumplir el objetivo propuesto.

		4. En esta etapa se evalúa las decisiones tomadas en función de los hechos ocurridos.


---

- #### Exponer las distintas alternativas para solucionar el problema (mínimo 2 alternativas), elegir una y explicar el motivo.

	- `Alternativa 1:`
		
		1. Contratar un servicio provisto por una empresa del exterior, llamada Queue-IT, que nos provee de un servicio ya de buena reputacion en el mercado, en el cual cada usuario al ingresar a nuestro sitio el dia del evento, recibira un ticket electronico el cual lo ubicara dentro de una cola de espera para poder ingresar al sitio y disponer de unos 20 minutos para realizar sus compras. 
		
		2. Minutos antes de su turno, el cliente sera notificado mediante sms, whatsapp, email o llamada, indicandole su proximidad al turno. Mientras tanto, puede visitar las ofertas disponibles de nuestro sitio el dia del evento, descuentos disponibles, medios de pagos, y sorteos.
		
		3. Dicho servicio, nos provee de un soporte tecnico en espaniol tanto para el equipo de IT de nuesta empresa, como asi tambien una plantilla de 20 personas disponibles para la atencion del cliente.

		4. Ademas, ellos disponen de una triangulacion de 3 servidores, en los cuales balanceara la carga de Usuarios Concurrentes (UC), pudiendo asi tener una capacidad de 10k UC, superando a nuestros competidores en un 35% en disponibilidad, velocidad y calidad de servicio, venta y post-venta.

		5. Luego del evento, podremos seguir manteniendo nuestro servidor de 100 UC que es nuestra capacidad y demanda habitual, sin tener que costear el mantenimiento de 3 servidores para una disponibilidad de 10K UC que luego del evento no vamos a tener.

		6. El pago seria del 60% previo al evento, y un pago del 40% al dia siguiente de terminado el evento.

	- `Alternativa 2:`

		1. Disponemos de 2 semanas para la ampliacion de 1 servidor a 3 servidores para poder llegar una disponibilidad aproximada de 5k UC.
		
		2. Sumar los costos en dolares para la compra de dichos servidores, traslados, instalacion, mantenimiento y la contratacion de 2 recursos de Administradores de Servidores.
		
		3. Capacitar al equipo de desarrollo para realizar las mejoras al sitio web para la conexion a los nuevos servidores, y sus correspondientes pruebas en ambientes de QA, y Pre-Produccion. Correccion de posibles errores relacionados.
		
		4. Disponer en el plazo de una semana para la instalacion de los servidores y balanceadores, pruebas y puesta a punto en un ambiente de pre-produccion para eventuales correcciones a realizar dias previos al evento.
		
		5. Disponer de nuestra plantilla de 5 personas para soporte a clientes del sitio el dia del evento y la posterior post-venta.
		
		6. El balanceador de cargas NO informa a los clientes el tiempo restante para el ingreso al sitio para realizar las compras.
		
		7. La amplicacion de servidores, NO provee de un sistema informado de cola a cliente. Solo lo deja en espera y NO tenemos forma alguna de informar al cliente su posicion frente a los demas compradores.


---

La tarea deberá ser realizada y entregada en un documento de word o pdf  llamado Grupo N°__Tarea2.doc