# Table of Contents

## UNIT I. **Motor Temperature Logging with SD Card**
1. [DS18B20 Temperature Sensor](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#1-ds18b20-temperature-sensor)
   - 1.1 [Introduction](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#introduction)
   - 1.2 [Initialization Sequence](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#initialization-sequence)
   - 1.3 [Read/Write Time Slots](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#read-time-slots)
   - 1.4 [Read Time Slots](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#read-time-slots)
   - 1.5 [Absolute Maximum Ratings](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)
   - 1.6 [DC Electrical Characteristics](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)
   - 1.7 [AC Electrical Characteristics](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)
   - 1.8 [Memory](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)
   - 1.9 [Pinout](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)
   - 1.10 [Connection](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#absolute-maximum-ratings)

2. [Interfacing the Sensor](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#2-interfacing-the-sensor)
   - 2.1 [The Need for an SD Card Module](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#21-the-need-for-an-sd-card-module)
   - 2.2 [Temperature Data Logging Code](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#22-temperature-data-logging-code)
   - 2.3 [Mounting of the sensors](https://github.com/KetanMe/Aquiring-Motor-Tempreature/blob/main/README.md#23-mounting-of-the-sensors)
  
     


## UNIT II. **Measuring-RPM-using-Orange-Rotary-Encoder**

1. [Rotary Encoder Overview](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#1-rotary-encoder-overview)
   - 1.1 [Introduction](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#introduction)
   - 1.2 [Working Principle](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#working-principle)
   - 1.3 [Usage of Signals](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#usage-of-signals)
   - 1.4 [Incremental Encoding and PPR/CPR](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#incremental-encoding-and-pprcpr)
   - 1.5 [Choosing the Best Encoder](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#choosing-the-best-encoder)
   - 1.6 [Types of Encoders](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#types-of-encoders)
2. [Interfacing the sensor](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#2-interfacing-the-sensor)
3. [Code for interfacing sensor with ESP8266](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/blob/main/Orange_enoder_RPM_Esp8266.ino)
   - 3.1 [Logic Behind the Code](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#logic-behind-the-code)
   - 3.2 [Theoretical Discussion](https://github.com/KetanMe/Measuring-RPM-using-Orange-Rotary-Encoder/edit/main/README.md#theoretical-discussion)
  
## UNIT III. **Introduction to Control Area Network (CAN)**

1. [Primary Purpose of the CAN Protocol](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#primary-purpose-of-the-can-protocol)
   - 1.1 [Introduction](#introduction-to-the-can-protocol)
   - 1.2 [Key Features](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#key-features-of-the-can-protocol)

2. [CAN vs Other Communication Protocols](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#can-vs-other-communication-protocols-such-as-uart-or-spi)
   - 2.1 [Communication Model](#communication-model)
   - 2.2 [Message Formatting](#message-formatting)
   - 2.3 [Error Handling](#error-handling)
   - 2.4 [Data Transfer Rate](#data-transfer-rate)
   - 2.5 [Applications](#applications)

3. [Maximum Data Transfer Rate Supported by CAN](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#maximum-data-transfer-rate-supported-by-the-can-protocol)

4. [Handling Message Priority and Arbitration](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#maximum-data-transfer-rate-supported-by-the-can-protocol)
   - 4.1 [Message Identifier](#message-identifier)
   - 4.2 [Arbitration](#arbitration)
   - 4.3 [Priority-Based Arbitration](#priority-based-arbitration)
   - 4.4 [Bit-wise Arbitration](#bit-wise-arbitration)
   - 4.5 [Non-Destructive Arbitration](#non-destructive-arbitration)
   - 4.6 [Message Transmission](#message-transmission)

5. [Different Message Types Supported by CAN](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#maximum-data-transfer-rate-supported-by-the-can-protocol)
   - 5.1 [Data Frames](#data-frames)
   - 5.2 [Remote Frames](#remote-frames)

6. [Error Detection and Error Handling in CAN](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#maximum-data-transfer-rate-supported-by-the-can-protocol)
   - 6.1 [Cyclic Redundancy Check (CRC)](#cyclic-redundancy-check-crc)
   - 6.2 [Acknowledgment (ACK)](#acknowledgment-ack)
   - 6.3 [Error Frames](#error-frames)
   - 6.4 [Error Passive and Bus Off States](#error-passive-and-bus-off-states)
   - 6.5 [Error Handling by Higher Layers](#error-handling-by-higher-layers)

7. [Difference Between CAN 2.0A and CAN 2.0B](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#difference-between-can-20a-and-can-20b)

8. [CAN FD (Flexible Data-rate) vs Classical CAN](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#can-fd-flexible-data-rate-vs-classical-can)

9. [Handling Network Management and Node Synchronization](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#handling-network-management-and-node-synchronization)
   - 9.1 [Network Configuration and Initialization](#network-configuration-and-initialization)
   - 9.2 [Address Assignment and Node Identification](#address-assignment-and-node-identification)
   - 9.3 [Time Synchronization](#time-synchronization)
   - 9.4 [Heartbeat Monitoring and Node Health Monitoring](#heartbeat-monitoring-and-node-health-monitoring)
   - 9.5 [Bus Monitoring and Diagnostics](#bus-monitoring-and-diagnostics)
   - 9.6 [Network Management Protocols](#network-management-protocols)
   - 9.7 [Node State Machines](#node-state-machines)

10. [Significance of the CAN Identifier and its Use in Message Filtering](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#significance-of-the-can-identifier-and-its-use-in-message-filtering)
    - 10.1 [Message Routing](#message-routing)
    - 10.2 [Message Prioritization](#message-prioritization)
    - 10.3 [Message Filtering](#message-filtering)
    - 10.4 [Addressing](#addressing)
    - 10.5 [Identification and Decoding](#identification-and-decoding)

11. [Maximum Length of a CAN Message](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#maximum-length-of-a-can-message)

12. [Handling Electromagnetic Interference and Noise in CAN](https://github.com/KetanMe/Introduction-to-Control-Area-Network-CAN-/tree/main?tab=readme-ov-file#electromagnetic-interference-and-noise-in-can)

## UNIT IV. **CAN Bus Data Transmission (RPM, Speed, Temperature)**
1. [Introduction](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#introduction)
2. [MCP2515 CAN module](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#mcp2515-can-module)
    - 2.1 [Interfacing with ESP8266](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#interfacing-with-esp8266)
        -2.2  [Pin connections](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#interfacing-with-esp8266)
3. [Hardware Implementation](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#interfacing-with-esp8266)
    - 3.1 [Wiring and Termination Resistors](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#wiring-and-termination-resistors)
    - 3.2 [Importance of 120 Ohm Termination Resistor](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#importance-of-120-ohm-termination-resistor)
    - 3.3 [Effects of Incorrect Termination Resistance](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#effects-of-incorrect-termination-resistance)
4. [Code for Sending RPM, Speed, and Temperature on CAN Bus](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#code-for-sending-rpm-speed-and-tempreature-on-can-bus)
    - 4.1 [Explanation of the Code](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#explaination-of-the-code)
        - 4.1.1 [Libraries and Constants](#1-libraries-and-constants)
        - 4.1.2 [Global Variables and Structs](#2-global-variables-and-structs)
        - 4.1.3 [Functions](#3-functions)
        - 4.1.4 [Setup Function](#4-setup-function)
        - 4.1.5  [Loop Function](#5-loop-function)
        - 4.1.6 [State Logic](#6-state-logic)
        - 4.1.7 [Sending Data via CAN](#7-sending-data-via-can)
5. [Output](https://github.com/KetanMe/RPM-speed-and-tempreature-sending-using-CAN/tree/main?tab=readme-ov-file#explaination-of-the-code)
   
