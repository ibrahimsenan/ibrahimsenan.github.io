---
layout: post
title:  "CareBud Architecture"
date:   2019-01-05
image: CB.arch.png
---

CareBud is an application that helps patients and older peoples to be connected to there doctors, also monitored by there family members. Which will be monitored by a SmartWatch attached to the patient and transmitting data and reports such as (Body Temperature, Heartbeat, and Blood Preusser) to CareBud app. 
Thereafter the application will process it (Analysis, Report, and Encrypt) and it will transmit that data as encrypted data and store it in CareBud Backend(Aws Cloud).

***Common terms used in this section***

- **CareBud App**: App designed to manage all user’s data which include and performs all required processes in the client side such as (Encryption, Decryption, Key management, Access Control, Users Account Management and Sending, and Receiving data from Could Backend).

- **CareBud Backend**: is Ubuntu server that hold database server MongoDB NonSql Database for creating, updating, and delete user encrypted data using RESTful APIs.

- **AWS Cloud**: Amazon Web Services EC2 Cloud service used to hold Ubuntu server and CareBad backend which provided by AWS.

- **RESTful APIs**: Representational State Transfer is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.

- **Smart Watch (Virtual Smart Watch)**: is virtual smartwatch created to simulate data coming or reported from patients’ body and provided to CareBud App which will check patient health status and sending Json data every ten seconds.


***User Entities used in this Project***

- **Patient**: (P1) is the main aspect in this project and he/she has an account that contain specific diagnosis and health reports that been taken by virtual smart watch and other reports are provided by the patient himself.
- **Doctor**: (D1) Doctor is responsible to watch patient health reports status, he/she will be notified if their critical reports and it can interact with patient totally and give his diagnosis on that health reports also sharing doctor advises.
- **Relatives**: (R1) an entity related to patient which play if the patient want one of his family members to be reported with his health reports.