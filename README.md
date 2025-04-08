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

Use of Fabric

The workload that was used in Microsoft fabric was Real-Time Intelligence, which was used to provide  analytical solutions for real-time data streams relating  to external factors that affect water extraction from boreholes  such as high temperature and ground motion (earthquakes)

The items types used were;
Eventstream  that provides  a stream of events related to observations of water properties such as water levels, pressure and extent of salinity.
Data Gen2  which is used for to ingest data such as inventory of equipment used for water extraction such as pumps.
Microsoft Fabric Activator  that enables automated processing of events that trigger actions. For example, use of an  Activator to notify you by email when a value such as temperature  in an eventstream deviates from a specific range 

Use of AI

The AI used is the Azure AI proxy playground  which comprise of;
DALL·E playground that was used to generate revised prompts 
Gpt  models which were used to illustrate how to use workloads and item types in Microsoft fabric
Github copilot for Azure which is used for generation of code used for analyzing equipment used by water engineers.
We also used Gpt model to aid in fabrication of braille learning material for water engineers who could be partially or fully visually impaired. The Gpt assisted in determining dimensions of texts and other illustrative graphics.


# Innovation
Does the solution have real world relevance? Does it solve a clearly defined problem that could be beneficial to others?
The solution does have a real world relevance as most companies rely on Internet of Things (IoT)  (which are devices that monitor various parameters such as pressure or extent of salinity in water) however most companies are unable to analyse such information so as to derive accurate insights.

Our team has already reached out to companies that specialise in water management so as to evaluate the feasibility of the solution. The companies are; 

1.Alma water

2. Siemens

3. Davis and Shirtliff

