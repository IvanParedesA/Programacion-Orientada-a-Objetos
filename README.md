# TC1030 Proyecto: Agencia de Transporte

El proyecto consiste en calcular los ingresos que genera una agencia de transporte a través de las tarifas que generan los distintos tipos de viajes que hay. Algo que debemos tener en cuenta es que los viajes comparten algunas características en común como: ubicación de origen y destino, id de viaje, una etiqueta con el tipo de viaje, una tarifa por kilómetro recorrido y una tarifa total. Sin embargo, en la siguiente lista podremos encontrar son los diferentes tipos de viajes disponibles junto con sus características distintivas:

Taxi Local: Tiene una tarifa especial cuando se encuentra en un horario concurrido (El doble del precio)

Taxi Inter-urbano: Tiene una tarifa especial dependiendo de la cantidad de pasajeros y la cantidad de equipaje (25% extra por persona excepto cuando es solo un ocupante y 5% extra por cada uno de los equipajes)

Fletes: Tiene una tarifa especial dependiendo del peso de la carga (25% extra cada 200kg)

El programa podrá calcular la tarifa específica de cada uno de los tipos de viajes incluyendo el monto total de todas las tarifas juntas del conjunto de todos los tipos de viaje.

La clase principal que representa a la agencia, contiene dentro las clases que representan los tipos de viaje. De esta manera tendríamos 4 clases, ya que la clase de "Viaje" es una clase abstracta. Ya que se usan elementos de composición para el proyecto, este dejaría de funcionar si la clase de la empresa es eliminada ya que al desaparecer ella, las demás clases también lo harían.
