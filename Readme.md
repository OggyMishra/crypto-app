Undestanding the need of celery.
- HTTP: Request and Response cycle.
- Executing queries/Processing data.
- Django processing -> User wait for response (before any action can be taken)
- Server resources are limited.

A task or process manager, a task queue.
use celery:
- to execute process(Tasks)
- Different Thread(On demand )
- Distribute Workloads.

Message Broker:
- RabbitMQ/Redis


Number of modules for configuring the celery tasks:
1. Define all the tasks.
2. Workers.
3. 