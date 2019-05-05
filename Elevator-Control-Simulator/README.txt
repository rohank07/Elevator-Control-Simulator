Elevator Control Simulator

Authors: Abubakar Abdulsalam, Ezwad Rahman, Gurveer Dhindsa, Kartik Vashisth, Rohan Katkar 

Contents:
This zip contains
	L3G7_milestone_2 - Project folder
		/.project & /.classpath - Project files for Eclipse IDE
		/src - Source code
			/configuration
				/configuration.txt - Text file containing floor requests
			/main
				/Floor.java - Floor subsystem used to simulate arrival of passengers
				/FloorRequest.java - Used by Floor subsystem to pass necessary information
				/Scheduler.java - Scheduler subsystem used to accept input and send commands
				/SchedulerElevators.java - Scheduler creates a new instance of this for every
				                           elevator that sends a registration message 
				/Elevator.java - Elevator subsystem used to simulate movement to pick/drop passengers
			/test
				/FloorTest.java - JUnit tests for Floor class
				/FloorRequestTest.java - JUnit tests for FloorRequest class
				/ElevatorTest.java - JUnit tests for Elevator class 
				/SchedulerElevaorTest.java - JUit tests for SchedulerElevators class
		/.README.md - this file 
		/.settings - Eclipse IDE Settings
		/bin - Build output folder
		/.travis.yml - Travis script for continuous integration
		/.pom.xml - Maven project configuration
		
Set up and running:
1. Unzip the files contained in L3G7_milestone_2
2. In Eclipse IDE, import the project (as an existing project) into your current workspace
3. Right click on each Java file (Scheduler.java, Elevator.java, Floor.java) in this order.
(It is recommended to open a new console for each running program)

Responsibility breakdown:
Each group member was equally responsible for the coding part of this iteration.
Also, each group member contributed to creating the UML class diagram and state machine diagram
	



