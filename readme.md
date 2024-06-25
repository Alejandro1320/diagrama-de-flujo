```mermaid
graph TD
A[Inicio del Pedido] -->|Realiza pedido| B[Confirmación del Pedido]
B -->|Verifica disponibilidad| C[Preparación del Pedido]
C -->|Prepara y verifica pedido| D[Despacho del Pedido]
D -->|Asigna y notifica reparto| E[Entrega del Pedido]
E -->|Entrega y verifica| F[Confirmación de Entrega]
F -->|Cliente confirma recepción| G[Post-Entrega]
G -->|Encuesta de satisfacción| H[Soporte al Cliente]
