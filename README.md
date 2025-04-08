# VisualizationForAll
This a Github repository for a project that would be beneficial to water engineers
# VisualizationForAll solution documentation
VisualizationForAll is a water management platform that analyses equipment used such as pipes while taking into account internal factors such as pressure surges in pipes as well as using external factors such as ground motion (earthquakes) or even high temperature from the environment.
Below is the solution architecture of the solution

![image](https://github.com/user-attachments/assets/09858649-67ae-47a6-bcd6-6886f175a27c)

# Alignment with the hackathon goal
Does the solution fit into the hackathon goal of designing, building and deploying a functional real world AI application using Microsoft fabric?
The solution aligns with the hackathon goal  as we are addressing a real world problem pertaining to enhancing operations of water  engineering companies and ensuring inclusive digital learning to people who are either  visually impaired or have limited knowledge of Information Technology.

The solution is an AI application which utilises Azure AI proxy playground especially GPT 4, so as to provide insights on performance of equipment used for water extraction such as pumps while using three-dimensional software.
Below is a video demonstration;
https://youtu.be/YaWbm4kgBLE

Additionally, the  visualization we seek to acheive is also targeting water engineers who strain to understand how software such as how Microsoft Fabric works. We are using Auto Card (three-dimensional) software together with Azure AI proxy playground so as to design plastic braille material which is easier to visualise through touch rather than sight.
Below is a video demonstration;
https://youtu.be/Q4NB53KcXyw 

# Technology Fabric and AI
Does the solution usee multiple fabric features and workloads and leverage built in AI capabilities and those from Azure AI

Fabric

The workload that was used in Microsoft fabric was Real-Time Intelligence, which was used to provide  analytical solutions for real-time data streams relating  to external factors that affect water extraction from boreholes  such as high temperature and ground motion (earthquakes)

The items types used were;
Eventstream  that provides  a stream of events related to observations of water properties such as water levels, pressure and extent of salinity.
Data Gen2  which is used for to ingest data such as inventory of equipment used for water extraction such as pumps.
Microsoft Fabric Activator  that enables automated processing of events that trigger actions. For example, use of an  Activator to notify you by email when a value such as temperature  in an eventstream deviates from a specific range 
![image](https://github.com/user-attachments/assets/987c97f1-ef77-4c7d-97c9-3e47e7266aef)

