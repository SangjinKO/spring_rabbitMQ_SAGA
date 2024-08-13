# SAGA Pattern with a rabbitMQ

Date: 2024.08

What's learned
- RabbitMQ
- Kafka
- SAGA Pattern

Project Architecture
- Compensating Actions: If a step in the saga fails, compensating actions are used to undo or mitigate the effects of the previous steps. This ensures that the system can recover to a consistent state.
<img width="878" alt="Untitled (1)" src="https://github.com/user-attachments/assets/bed9d405-5221-4916-b336-66bdd70a7751">
