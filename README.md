# DriverPass System Design

### The Problem
New driver's have a limited amount of material to study for their exams and even fewer option to practice for the on road skills test. DriverPass plans to fill this gap in the market by providing online courses and the ability to easily book in person driving lessons online. 

### The Solution
DriverPass will require a web based application to reach the maximum amount of users on a variety of different devices between desktop and mobile. Given the limited size of the company, a managed cloud based back-end will be implemented to handle security and maintainence. 

### System Design Approach

##### Gathering Requirements
The first step was to gather requirements based on the user's needs. It is always important to consider the end user as a designer because discrepencies may exist between what a designer envisions as ideal versus an actual end user. Listening to the user eliminates any personal biases and ensures a more seamless implementation. 

##### Creating Design Documents
With the user's requirements in mind, a GANTT chart was created to establish a timeline and work began on the design documents
<figure>
<img src="https://github.com/gmurin08/cs255-driverpass/blob/main/UseCase.png?raw=true" alt="alt text" width="500" height="400">
<figcaption style="font-size: 100px;" align = "center"><b>Fig.1 - Use Case Diagram</b></figcaption>
</figure>

As depicted in the use case diagram, DriverPass requries basic functionality for users and administrators including creating reading updating and deleting data as necessary. 

##### The System

