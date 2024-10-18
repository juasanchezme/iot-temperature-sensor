# 🌲 Forest Fire Early Warning System 🔥

[🇺🇸 English Version](#english-version) | [🇪🇸 Versión en Español](#versión-en-español)

---

## 🇺🇸 English Version

## 🎥 Project Demo

I had a great time working on this project, and here’s a video demo showcasing how the system works:

[![Project Demo Video](https://img.youtube.com/vi/xtU1OrlX2rM/0.jpg)](https://www.youtube.com/watch?v=xtU1OrlX2rM)

Click on the image above to watch the demo on YouTube.

## 📜 Justification
Forest fires are primarily influenced by human activities rather than spontaneous natural events. In order to prevent and alert authorities about potential forest fires, it is imperative to develop an early warning system. This system aims to minimize environmental and ecosystem losses by providing real-time monitoring and control to district and private organizations.

## 🎯 Objectives
- **Early Detection**: 🔔 Alert about potential forest fires before they escalate.
- **Real-time Monitoring**: 🕒 Provide continuous data on environmental conditions.
- **Sustainability**: 🌞 Operate using renewable energy sources.
- **Low-Cost Solution**: 💰 Utilize affordable and accessible components for wide-scale deployment.

## 🏗️ System Architecture

![IoT Temperature Sensor Architecture](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/Picture1.png)

The system is composed of several sensors and hardware components, powered by renewable energy, that continuously monitor temperature, humidity, and gas levels. Data is transmitted through LoRa technology to a central node, where it is processed and sent to mobile devices for real-time alerts. 

| **Component**                           | **Description**                                                                                     |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------|
| 🌡️ **Temperature and Humidity Sensor (SHT31)** | Measures temperature and humidity, essential for detecting conditions that could lead to fires.       |
| 🛑 **Gas Sensor (MQ2)**                 | Detects smoke or gases such as methane, propane, and butane that may indicate the presence of fire.  |
| ⚙️ **Arduino Nano**                     | Acts as the microcontroller, processing data from the sensors and controlling the system.            |
| 📡 **LoRa Transceiver (SX1278)**        | Provides long-range communication between the sensor nodes and the central system.                    |
| ☀️ **Solar Panel (6V 3W 500mA)**        | Powers the system using renewable energy, ensuring operation in remote areas.                        |
| 🔋 **Li-ion Battery (18650 3500mAh)**   | Stores energy from the solar panel to ensure continuous operation, even during the night.             |
| 🔌 **DC-DC Converter (MT3608)**         | Regulates the voltage from the battery to provide stable power to the components.                    |

## 🙏 Acknowledgements and Gratitude

I am deeply grateful for the recognition given to this project. The experience was both enjoyable and educational, and I appreciate all the support received throughout the process. Here are some moments captured during the presentation:

<p align="center">
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto1.jpeg" alt="Presentation 1" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto2.jpeg" alt="Presentation 2" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto3.jpeg" alt="Presentation 3" width="30%" />
</p>

---

## 🇪🇸 Versión en Español

## 🎥 Demostración del Proyecto

Disfruté mucho trabajando en este proyecto, aquí tienes un video que muestra cómo funciona el sistema:

[![Video Demostración del Proyecto](https://img.youtube.com/vi/xtU1OrlX2rM/0.jpg)](https://www.youtube.com/watch?v=xtU1OrlX2rM)

Haz clic en la imagen de arriba para ver la demo en YouTube.

## 📜 Justificación
Los incendios forestales no son en su mayoría el resultado de la acción espontánea de la naturaleza, sino que están influenciados por actividades humanas. Con el fin de prevenir y alertar sobre posibles incendios forestales, se hace imperativo desarrollar un sistema de alertas tempranas. Este sistema tiene como objetivo minimizar las pérdidas ambientales y del ecosistema proporcionando monitoreo y control en tiempo real a las organizaciones distritales y privadas.

## 🎯 Objetivos
- **Detección Temprana**: 🔔 Alertar sobre posibles incendios antes de que escalen.
- **Monitoreo en Tiempo Real**: 🕒 Proporcionar datos continuos sobre las condiciones ambientales.
- **Sostenibilidad**: 🌞 Operar usando fuentes de energía renovables.
- **Solución de Bajo Costo**: 💰 Utilizar componentes accesibles y asequibles para su implementación a gran escala.

## 🏗️ Arquitectura del Sistema

![Arquitectura del Sensor de Temperatura IoT](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/Picture1.png)

El sistema está compuesto por varios sensores y componentes de hardware, alimentados por energía renovable, que monitorean continuamente la temperatura, la humedad y los niveles de gas. Los datos se transmiten a través de tecnología LoRa a un nodo central, donde se procesan y se envían alertas en tiempo real a dispositivos móviles.

| **Componente**                          | **Descripción**                                                                                     |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------|
| 🌡️ **Sensor de Temperatura y Humedad (SHT31)** | Mide la temperatura y la humedad, esenciales para detectar condiciones que podrían generar incendios. |
| 🛑 **Sensor de Gas (MQ2)**              | Detecta humo o gases como metano, propano y butano que pueden indicar la presencia de fuego.         |
| ⚙️ **Arduino Nano**                     | Actúa como el microcontrolador, procesando los datos de los sensores y controlando el sistema.       |
| 📡 **Transceptor LoRa (SX1278)**        | Proporciona comunicación de largo alcance entre los nodos de sensores y el sistema central.           |
| ☀️ **Panel Solar (6V 3W 500mA)**        | Alimenta el sistema utilizando energía renovable, garantizando su operación en áreas remotas.        |
| 🔋 **Batería Li-ion (18650 3500mAh)**   | Almacena la energía del panel solar para asegurar una operación continua, incluso durante la noche.   |
| 🔌 **Convertidor DC-DC (MT3608)**       | Regula el voltaje de la batería para proporcionar energía estable a los componentes.                 |

## 🙏 Agradecimientos y Gratitud

Estoy muy agradecido por el reconocimiento dado a este proyecto. La experiencia fue tanto educativa como divertida, y aprecio todo el apoyo recibido a lo largo del proceso. Aquí algunos momentos capturados durante la presentación:

<p align="center">
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto1.jpeg" alt="Presentación 1" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto2.jpeg" alt="Presentación 2" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto3.jpeg" alt="Presentación 3" width="30%" />
</p>

