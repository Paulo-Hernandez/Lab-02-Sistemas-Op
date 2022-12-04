# Lab-02-Sistemas-Op
Trabajo sincronico Sistemas operativos
En una fábrica se tienen dos procesos que modelan una planta de cervezas, en latas y que trabajan en paralelo: 

• Un proceso «Enlatado» se encarga de preparar las latas de 350ml. (lava, llena y sella las latas de cervezas).

• Otro proceso «Empaquetador» se encarga de empaquetar y reponer las cajas donde se van colocando las latas de cervezas.

Cada vez que el enlatador prepara una lata, ésta se coloca en una caja, que tiene una capacidad de 20 latas. Si al colocar la lata, la caja queda llena, se envía una señal al empaquetador, que toma la caja, la sella y la guarda en un almacén. El empaquetador deposita una nueva caja de 10 litros, totalmente vacía. Mientras el empaquetador está haciendo su labor, el enlatador no puede colocar sus latas, ya que en esos momentos no hay una caja disponible. Escribe el algoritmo de estos dos procesos, solucionando los problemas de sincronización.

Integrantes: 
Martin Hurtado T
Paulo Hernandez T
Nicolas Barra
Jaime Ugaz R
