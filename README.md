# ems-algasensors-meta
algaworks-ems-algasensors

-> IMPORTANTE:
* O projeto usa H2 database
* Produtor: TemperatureProcessingApplication
* Consumidor: TempertureMonitoringApplication
* Foi implementado um Sleep no consumidor de 10s para ser possível visualizar as mensagens sendo consumidas no painel do RabbitMQ

Pra subir o docker:
docker-compose up

Acessar a interface:
http://localhost:15673/
rabbitmq
rabbitmq


Exchange:
temperature-processing.temperature-received.v1.e

Queue:
temperature-monitoring.process-temperature.v1.q