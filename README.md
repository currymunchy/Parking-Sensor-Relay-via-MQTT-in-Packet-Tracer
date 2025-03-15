Integrated my parking sensor within the MQTT application to work natively within and send messages. So yes, when a sensor is activated,  it is possible to send a message to other IoT devices within Packet Tracer's environment (just gotta modify the application's code within Packet Tracer :D) 

Programmed and modified the Packet Tracer's MQTT application to include the parking sensor codes and can send a message when subscribed to the topic "parking". 
Currently the topic "parking" is hard-coded into the application for my parking sensor- meaning the parking sensor only sends a message via the topic "parking". This can be manually changed within pi0. go to programming > mqttapplication > main.py
