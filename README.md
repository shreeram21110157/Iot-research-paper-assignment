# Iot-research-paper-assignment

IoT CIA 2 dataset:
https://www.kaggle.com/datasets/poojag718/rainfall-timeseries-data


IOT CIA 1:
Latex code 

\documentclass{article}
\usepackage[utf8]{inputenc}

\title{Internet of Things Architecture and
Applications: A Survey}
\author{AN Shreeram }
\date{January 2023}

\begin{document}

\maketitle

\section{Topic Summary}
This is a review of the research paper "Internet of Things Architecture and
Applications: A Survey" by Tabassum Ara, Pritam Gajkumar Shah and M. Prabhakar. The authors talk about what is Iot and how IoT devices are seemingly integrated into modern lifestyle and how it impacts. Later on they talk about its applications, architecture and its security.

\section{Key contributions from the author(s)}
The internet of things (IoT) is an expansion of Internet
where all the physical objects like home appliances,
vehicles, sensors, actuators, mobile phones etc. are also
gaining the ability to sense and communicate with each
other without any involvement of human being. IoT devices are classified into resource constrained
and resource rich devices.Resource rich devices like a
smart phone, standard personal computer or a server have
enough hardware, software and memory which support
TCP/IP protocol, where as resource constrained devices
like microcontroller based devices, sensors and actuators
do not have sufficient hardware/software capabilities that
support TCP/IP Protocol.
The authors have classified Iot into four different categories
\begin{itemize}
    \item Personal and home
    \item Enterprises
    \item Utilities
    \item Mobile
    
\end{itemize}
The authors say, according to the eight nation’s survey,
more than 50 percent of the respondents are willing
to embrace networked medical technology. When applying Iot in health sector they come across protecting patient privacy and their sensitive
data, intentional disruption etc. IoT for food
chain supply has three parts; filed devices, backbone
system and communication infrastructure.They have given a complete overview
of system architecture for an urban IoT for various applications like air quality, noise monitoring, traffic congestion, city energy consumption,
smart parking and smart lighting etc. The authors12,13 have applied IoT technology in agriculture area. IoT based monitoring system is
developed to gather environmental information to
increase the growth of the crop. 

“Architectural considerations for smart
object networking” describes how resource constrained
embedded devices can make use of IP based protocols.
Refrigerator, car, front doors, bulbs etc have been hacked.
Internet of things is becoming a playground for the
hackers.There are four different forms of communication pattern in Iot.They are 
\begin{itemize}
    \item Device to Device
\end{itemize}
Devices are generally manufactured by different companies. So, the devices are required to interoperate and communicate with each other for smooth experience.
Communication among these devices requires the different vendors to agree on
the protocol stack and their design aspects like protocols, information model used, data model used to encode, IP address configuration mechanism etc.
\begin{itemize}
    \item Device to Cloud
    \item  Device to Application Layer Gateway
\end{itemize}
Here the devices from the same vendor collect data from the environment and send it to the their own cloud for processing. Both the device and the cloud service will be of the same vendor to avoid interoperatability issues. In device to application layer gateway it is the same as the device to cloud but there will be an addition gateway through which all the data will pass through. This gateway will generally be a smartphone using IPv4 or IPv6.
\begin{itemize}
    \item Back-End Data Sharing
\end{itemize}
Normally users required to export and analyze data
in combination with data from other sources. This
architecture supports granting access to the uploaded
sensor data to third parties. It allows the data collected
from single IoT device to be aggregated and analyzed. This is generally organized into three layers: Perception layer, network layer and application
layer. Perception layer deals with
physical devices. Network layer collects data from these
devices and transmit to the application layer, where all the
processing and decision making takes place. This arrangement was not enough to address all the things that goes on behind the devices. So they updated Miao, Wu suggested five layer architecture of
Internet of Things since with the help of three/four
layer structure all the features of IoT can’t be expressed.
According to Paul reference architecture
of IoT consists of five layers. International Telecommunication Union (ITU)22
recommends that architecture of Internet of Things
may consists of five layers; 
\begin{itemize}
    \item Sensing Layer
    \item Access Layer
    \item Network Layer \item Middleware Layer \item The Application
Layer
\end{itemize}
Indu Bala Thingam24 has proposed six layer
architecture by introducing two more layers MAC layers and processing and storage
layer.

There are also huge security concerns in these Iot devices.RFID system threats, which includes abuse of
tags, reader risks and personal privacy leak.The authors27 have identified
various security challenges including authentication,
authorization, encryption and cache poisoning etc. 
Wearable IoT collects sensitive information like location
and movement activities which compromises the privacy
of the user.Sachin Babar et.al.29 has proposed a cube structure as a
modeling mechanism for security, trust and privacy in the
IoT. This structure has three dimensions; security, trust
and privacy.

Shivraj VL have proposed30 OTP scheme based
on identity based elliptic curve. Where hash function is
replaced by a new function which is based on Identity
Based Encryption (IBE) scheme.This process
is repeated desired number of times. This scheme requires
fewer resources for the operations, since the keys are not
stored. Elliptic Curve Cryptography (ECC) has much more
benefits in public key cryptosystems which are small key
length, lower consumption power, faster computation,
and small bandwidth.Pinol  have implemented a
light weight cryptography model for resource constrained
IoT using ECC for Contiki OS. A mathematical model is
developed in which all the primitive functions of ECC are
implemented. The authors have evaluated that Jacobian
coordinate system is the better choice with respect to the
improvement in performance.
IoT interconnects heterogeneous devices
manufactured by various companies. Marin
have proposed a novel key negotiation protocol where
elliptic curve cryptographic algorithm is used with 32
bit processor; NXP/Jennic 5148- and 16 bit processor;
MSP430-based IoT devices.The IoT embraces the guarantee of improving human
lives through amplification and automation.  It also helps to improve decision making
and outcomes in a various application areas like medical,
manufacturing, transportation, education etc.by
integrating various existing technologies together in
a novel way, the IoT has the high potential to reshape
human life.
\section{My Views on the Paper}
I think that Iot devices when integrated properly with enhanced security than what is existing right now is going to drastically improve our lives in every possible way. The best examples are health and agriculture. We can live longer by diagnosing all the diseases and produce more and healthier foods for consumption. Improvement in transport will greatly improve our country's economy. It will make mundane tasks easier.  We don't want all the information to be stored on the smartphone and don't want to connect all the devices to connect to the internet for security and privacy reasons. So,I think it is a great technology to develop and use it even more with necessary precaution.

\section{Agreements, pitfalls and fallacies}
I agree that all the Iot devices make our lives easier and not only for us consumers but also for the industries. The current state of Iot is not gaining trust due to the invasion of privacy of the consumers in order to collect data and process it somewhere else by the companies. There is also security concerns on how the data is being sent to the companies and whether other people can see our data. Iot devices by default do not have hardware capability to take care of encrypting the data, So generally smartphones take care of it while sending the data. There needs to be a standard protocol to be followed by all the devices and encryption of data should be improved for safe transmission of data.     

\end{document}
