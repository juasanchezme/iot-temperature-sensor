# [English Version](#english-version) | [Versión en Español](#versión-en-español)



---

## English Version

# 🌲 Forest Fire Early Warning System 🔥

## 📜 Table of Contents
- [Project Demo](#-project-demo)
- [Justification](#-justification)
- [Objectives](#-objectives)
- [System Architecture](#-system-architecture)
- [Acknowledgements and Gratitude](#-acknowledgements-and-gratitude)
- [Future Improvements](#-future-improvements)
- [Versión en Español](#-versión-en-español)

## 🎥 Project Demo
I had a great time working on this project, and here’s a video demo showcasing how the system works:

[![Project Demo Video](https://img.youtube.com/vi/xtU1OrlX2rM/0.jpg)](https://www.youtube.com/watch?v=xtU1OrlX2rM)

Click on the image above to watch the demo on YouTube.

## 📜 Justification
Forest fires are primarily influenced by human activities rather than spontaneous natural events. In order to prevent and alert authorities about potential forest fires, it is imperative to develop an early warning system. This system aims to minimize environmental and ecosystem losses by providing real-time monitoring and control to district and private organizations.

The proposed solution involves in-situ data collection through interconnected sensors that constantly measure temperature and other environmental conditions. This data is then transmitted via mobile devices to alert the responsible entities, allowing for immediate action. 

The implementation of this system is designed to be energy-efficient and capable of operating in remote locations with minimal human intervention.

## 🎯 Objectives
- **Early Detection**: 🔔 Alert about potential forest fires before they escalate.
- **Real-time Monitoring**: 🕒 Provide continuous data on environmental conditions.
- **Sustainability**: 🌞 Operate using renewable energy sources.
- **Low-Cost Solution**: 💰 Utilize affordable and accessible components for wide-scale deployment.

## 🏗️ System Architecture
The system is composed of several sensors and hardware components, powered by renewable energy, that continuously monitor temperature, humidity, and gas levels. Data is transmitted through LoRa technology to a central node, where it is processed and sent to mobile devices for real-time alerts. 

![IoT Temperature Sensor Architecture](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/Picture1.png)

The architecture includes:
1. **Sensor Nodes**: 📡 Collect environmental data.
2. **Data Transmission**: 🚀 Via LoRa technology to a central server.
3. **Central Processing**: 🧠 Data is analyzed, and alerts are generated.
4. **Mobile Notifications**: 📱 Authorities and users are notified of any potential fire risks.

| **Component**                           | **Description**                                                                                     |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------|
| 🌡️ **Temperature and Humidity Sensor (SHT31)** | Measures temperature and humidity, essential for detecting conditions that could lead to fires.       |
| 🛑 **Gas Sensor (MQ2)**                 | Detects smoke or gases such as methane, propane, and butane that may indicate the presence of fire.  |
| ⚙️ **Arduino Nano**                     | Acts as the microcontroller, processing data from the sensors and controlling the system.            |
| 📡 **LoRa Transceiver (SX1278)**        | Provides long-range communication between the sensor nodes and the central system.                    |
| ☀️ **Solar Panel (6V 3W 500mA)**        | Powers the system using renewable energy, ensuring operation in remote areas.                        |
| 🔋 **Li-ion Battery (18650 3500mAh)**   | Stores energy from the solar panel to ensure continuous operation, even during the night.             |
| 🔌 **DC-DC Converter (MT3608)**         | Regulates the voltage from the battery to provide stable power to the components.                    |

![Circuit diagram](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/esquematicoConexion.png)

## 🙏 Acknowledgements and Gratitude
I am deeply grateful for the recognition given to this project. The experience was both enjoyable and educational, and I appreciate all the support received throughout the process. Here are some moments captured during the presentation:

<p align="center">
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto1.jpeg" alt="Presentation 1" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto2.jpeg" alt="Presentation 2" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto3.jpeg" alt="Presentation 3" width="30%" />
</p>

## 🌟 Future Improvements
- **Additional Sensors**: Integrate more types of sensors such as wind speed 🌬️ or air quality 🏭 to improve fire prediction accuracy.
- **Machine Learning**: Implement machine learning models 🤖 to predict fire risk based on historical and real-time data.
- **Extended Network**: Deploy more sensor nodes to cover a larger area 🌍 and ensure comprehensive fire detection.

---

## Versión en Español

# 🌲 Sistema de Alerta Temprana de Incendios Forestales 🔥

## 📜 Contenido
- [Demostración del Proyecto](#-demostración-del-proyecto)
- [Justificación](#-justificación)
- [Objetivos](#-objetivos)
- [Arquitectura del Sistema](#-arquitectura-del-sistema)
- [Reconocimientos y Agradecimientos](#-reconocimientos-y-agradecimientos)
- [Mejoras Futuras](#-mejoras-futuras)

## 🎥 Demostración del Proyecto
Tuve un gran tiempo trabajando en este proyecto, y aquí hay un video demostrativo que muestra cómo funciona el sistema:

[![Video de Demostración del Proyecto](https://img.youtube.com/vi/xtU1OrlX2rM/0.jpg)](https://www.youtube.com/watch?v=xtU1OrlX2rM)

Haz clic en la imagen de arriba para ver la demostración en YouTube.

## 📜 Justificación
Los incendios forestales son principalmente influenciados por actividades humanas más que por eventos naturales espontáneos. Para prevenir y alertar a las autoridades sobre incendios forestales potenciales, es imperativo desarrollar un sistema de alerta temprana. Este sistema tiene como objetivo minimizar las pérdidas ambientales y del ecosistema proporcionando monitoreo y control en tiempo real a organizaciones distritales y privadas.

La solución propuesta implica la recolección de datos in situ a través de sensores interconectados que miden constantemente la temperatura y otras condiciones ambientales. Estos datos se transmiten a través de dispositivos móviles para alertar a las entidades responsables, permitiendo una acción inmediata.

La implementación de este sistema está diseñada para ser eficiente en energía y capaz de operar en ubicaciones remotas con mínima intervención humana.

## 🎯 Objetivos
- **Detección Temprana**: 🔔 Alertar sobre incendios forestales potenciales antes de que se agraven.
- **Monitoreo en Tiempo Real**: 🕒 Proporcionar datos continuos sobre las condiciones ambientales.
- **Sostenibilidad**: 🌞 Operar utilizando fuentes de energía renovable.
- **Solución de Bajo Costo**: 💰 Utilizar componentes asequibles y accesibles para un despliegue a gran escala.

## 🏗️ Arquitectura del Sistema
El sistema está compuesto por varios sensores y componentes de hardware, alimentados por energía renovable, que monitorean continuamente la temperatura, la humedad y los niveles de gases. Los datos se transmiten a través de tecnología LoRa a un nodo central, donde se procesan y se envían a dispositivos móviles para alertas en tiempo real.

![Arquitectura del Sensor de Temperatura IoT](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/Picture1.png)

La arquitectura incluye:
1. **Nodos de Sensor**: 📡 Recogen datos ambientales.
2. **Transmisión de Datos**: 🚀 A través de tecnología LoRa a un servidor central.
3. **Procesamiento Central**: 🧠 Los datos se analizan y se generan alertas.
4. **Notificaciones Móviles**: 📱 Se notifica a las autoridades y usuarios sobre cualquier riesgo potencial de incendio.

| **Componente**                          | **Descripción**                                                                                     |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------|
| 🌡️ **Sensor de Temperatura y Humedad (SHT31)** | Mide la temperatura y la humedad, esenciales para detectar condiciones que podrían llevar a incendios. |
| 🛑 **Sensor de Gas (MQ2)**              | Detecta humo o gases como metano, propano y butano que pueden indicar la presencia de fuego.        |
| ⚙️ **Arduino Nano**                     | Actúa como el microcontrolador, procesando datos de los sensores y controlando el sistema.            |
| 📡 **Transceptor LoRa (SX1278)**        | Proporciona comunicación de largo alcance entre los nodos de sensor y el sistema central.             |
| ☀️ **Panel Solar (6V 3W 500mA)**        | Alimenta el sistema utilizando energía renovable, asegurando operación en áreas remotas.             |
| 🔋 **Batería de Li-ion (18650 3500mAh)**| Almacena energía del panel solar para asegurar operación continua, incluso durante la noche.         |
| 🔌 **Convertidor DC-DC (MT3608)**       | Regula el voltaje de la batería para proporcionar energía estable a los componentes.                 |

![Diagrama del circuito](https://github.com/juasanchezme/iot-temperature-sensor/blob/main/images/esquematicoConexion.png)

## 🙏 Reconocimientos y Agradecimientos
Estoy profundamente agradecido por el reconocimiento dado a este proyecto. La experiencia fue tanto agradable como educativa, y aprecio todo el apoyo recibido a lo largo del proceso. Aquí hay algunos momentos capturados durante la presentación:

<p align="center">
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto1.jpeg" alt="Presentación 1" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto2.jpeg" alt="Presentación 2" width="30%" />
  <img src="https://github.com/juasanchezme/iot-temperature-sensor/blob/main/presentacionProyecto3.jpeg" alt="Presentación 3" width="30%" />
</p>

## 🌟 Mejoras Futuras
- **Sensores Adicionales**: Integrar más tipos de sensores como velocidad del viento 🌬️ o calidad del aire 🏭 para mejorar la precisión de la predicción de incendios.
- **Aprendizaje Automático**: Implementar modelos de aprendizaje automático 🤖 para predecir el riesgo de incendio basado en datos históricos y en tiempo real.
- **Red Ampliada**: Desplegar más nodos de sensor para cubrir un área más grande 🌍 y asegurar una detección integral de incendios.
