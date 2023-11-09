Mechanical requirement
- What is the vehicle? 
- Design information for the readers
- Development environment
- Schematic chart available or not. 
- Remove Vehicle size/passengers
- Price: 
- Payload: 10/50 tons, few pounds.
- 

CJ: Software Requirements: remove 0 
- SOAFEE
- Open AD Kit

CJ: Drive-by-Wire
CJ: ECU for Level 4

David: Safety and Reliability

Certificated or not. 

Vector for Support:
- 

Rahul: meta information related to this project
- Two sets of radar charts:
	- one for technical features
		- Drive-By-Wire (Propriety or open), features in auto-ware world
	- one for meta-information
		- Supportability, Open Source, Size, Sensors



Mitsudome-san:
For section "ODD", it might be better to break it down to measurable metrics to express the complexity of ODD, such as "operation velocity", "traffic density", "travel distance", etc..., instead of naming the use cases.

Mitsudome-san:
For Hardware Requirement, it might be better have clear definition of what is "low-end" and "high-end". We can also consider putting total power consumption of ECU instead.

For software requirement, maybe we can have something like this
0: Embedded OS / Proprietary OS
1: Linux (including ROS 1, Autoware.ai)
2: Linux + ROS 2 (including Autoware.auto)
3: Linux + ROS 2 + Autoware.core/universe
4: Linux + ROS 2 + Autoware.core/universe + Containerization
5: Linux + ROS 2 + Autoware.core/universe + Containerization + SOAFEE

Rahul:
- Sensors: 

David: 
- Trade-off from the charts

CJ: public road ready/prototyping/flexibility

- Automation level 
- Divide the charts to into multiple charts: 
	- Software arch for SDV/SOAFEE
	- Sensors at high speed on public road


One chart for sensors.


https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/


https://mermaid.js.org/