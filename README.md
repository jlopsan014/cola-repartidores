# Cola de Repartidores

App web para organizar a los repartidores de Glovo, Uber Eats, Just Eat y otras plataformas en el mostrador.

- Registra cada repartidor por orden de llegada con su plataforma y código/nombre de pedido.
- Cronómetro de espera (naranja a los 5 min, rojo a los 10).
- Estados: Esperando → Listo → Entregado, con deshacer.
- Pantalla grande para repartidores ("Listo para recoger" / "Preparando").
- Historial del día con espera media.

Es un único archivo `index.html`, sin dependencias ni servidor. Los datos se guardan en el navegador del dispositivo (localStorage).
