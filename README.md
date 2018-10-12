# Idea for CodeFunDo++

Our idea involves collecting meteorological and geological data and analysing it in real time in order to promptly notify people under the risk of disaster.

The one instrument that lies closest to a human, which happens to be the mobile phone will be used as the primary means to interact with the Disaster Management Authority and with other people.

## Tackling the three phases of disaster

### 1. Pre-Disaster

* Using a network of **IOT** enabled devices with appropriate **sensors** to send the data in real time to central server
* The server will crunch the data using **Machine Learning** algorithms and based on earlier data try to predict and provide indication as to whether there is a probability of a disaster in the source devices' zone.

### 2. During-Disaster

* Vulnerable people will receive **notification** on their phones on the app and also SMS. This will particularly be helpful in the case when internet is not accessible or the person is using a basic mobile phone.
* Data on availability of resources and lack thereof can be fed to the app by the people stuck in a site of disaster for their mutual help before relief arrives.

### 3. Post-Disaster

* An **SMS bot** will be much helpful to get quick answers on queries regarding supplies and support from authorities.
* In the case of broken network connectivity, local **P2P network** using WiFi can at least help to establish communication among the local people so that people can find the lost ones.
* Since **GPS** requires no internet, the location data can be encoded in a SMS and sent to the rescue authorities for recieving help sooner.
* Offline maps will display the location of relief camps so that people can reach safe areas easily.

#### Implementation
We plan on incorporating Microsoft azure machine learning service for analysing the data we receive from the sensors. Raspberry Pi and sensor modules like accelerometer will provide with the data required for the service.

Microsoft mobile services can be used to create the SMS bot.