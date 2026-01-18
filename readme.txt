start Active MQ server

not mandatory configure
<!-- <transportConnector name="amqp" uri="amqp://0.0.0.0:5672?maximumConnections=1000&amp;wireFormat.maxFrameSize=104857600"/> -->
<transportConnector name="amqp+nio" uri="amqp+nio://localhost:5672"/>
