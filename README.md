# InnoveLogic - document
## Where are we going?
Documentation about Innovelogic

In this repository give detail about InnovaLogic organization's projects and details.

Our Project List
- ###Automated Logic Modelling Tool for Circuit Designing

#####Group Name: Tech Antz

### Introduction
Nowadays students and the Electric Circuit designers are really engaging with testing and
making assumptions for the output for a given real-time scenario relevant to digital
electronic circuits. When focusing about the effective way of doing the above task, it mainly
causes to save time and minimize the cost rather than generating Boolean expressions
manually which need to think of the output for a particular digital electronic circuit.
Sometimes it may come up with wrong output result due to some mistakes of a person. But
with this autonomous process, it will generate an accurate output.
In our proposed solution we analyze the given image of a logic circuit diagram and derive
the logical model of that. At the same time we analyze any real world scenario which is
given according to the proposed format, and derive the logical model behind that.

###Background & Motivation
Digital logic circuit is an electronic circuit used in computers to perform logical operations
on its two or more input signals. These circuits are made up of various logic gates. AND,
OR, NOT are the basic logic gates, which can be used as building blocks to describe the
behavior of circuit. Normally when a designer designing a circuit that person has to do
figure out what are the inputs outputs and the relevant relationships among the conditions.
Based on that he has to derive the truth table and figure out the Boolean expression related to
that scenario. Then that person draw the logic circuit diagram and based on that he starts to
design the real circuit.
When bringing out the real world scenario to a Digital logic circuit, there are some
difficulties in figure out correct inputs, outputs and conditions. Even though there are correct
inputs, outputs and conditions, it is a great task to derive the Digital logic circuit by
considering all the relationships among those conditions. And also it gets a long time period
1and more cost to derive the truth table and figure out the Boolean expression related to any
real world scenario.

###Problem in Brief
When deriving the real world scenario and image of a logic circuit diagram to a Digital
circuit diagram, the basic thing is to identify the inputs, outputs and conditions. Not only that
but also it much important to build up relationships between among all above facts.
Therefore if those things are not exactly the correct ones, it may cause to occur failures or
undefined stage in Digital Logic circuits. And also the people who are interested in building
Digital logic circuits are eager to know about the output of a drawn sketch of a Logic circuit
diagram or in any given real world scenario. As a result this is much helpful for them to
check whether that they are ahead to the correct target or not.
If there is a tool to test the Logical problems and simulate the behavior of those problem can
be helpful for the people who are interested in Circuit designing. And this is much helpful
for them to achieve their targets effectively and efficiently with an accurate output in a short
span of time with less cost. If they are getting a failure or undefined stage then they can
change their requirements and adjust to simulate a acceptable output from the Digital logic
circuit.

###Aim
The aim of this project is to guide people who are interested in designing circuits to
logically model the real world scenarios and also checking out the correctness of the
hand-drawn logic circuit diagrams.

###Objectives

- Extract the features of the image of hand-drawn circuit diagram.
- Identify the components of the logic circuit diagrams such as the logic gates which have been used to draw the diagram.
- Identify the connections among those components to derive the logical model.
- Derive the logical model related to the hand-drawn logic circuit diagram.
- Extract the text which was entered by the end user according to the proposed format.
- Identify the inputs and outputs of each statements which was provided.
- Identify the relationships among the statements.
- Develop a structure which helps to model the extracted data.
- Derive the logical model of the given scenario.
- Evaluate the proposed system and verify it with the help of third party.

###Proposed Solution
The proposed solution for the above problem is to introduce a automated logic modelling
tool for circuit designing to get a vast advantage for the ones who are interested in Circuit
designing. This may cause to achieve their target with the correct vision of all the inputs,
outputs and all the other necessary conditions related to real world scenarios. And also they
can immediately check the relevant output for an image of a hand drawn sketch of Logic
circuit diagram.

- ##### Deriving the logical model of hand-drawn logic circuit diagram. 
Under this module the provided image of the hand-drawn circuit diagram will be
analyzed. After extracting the features of the image, the recognition of the inputs,
outputs, components and the connection among them. Based on the recognized elements,
the Boolean expression of the given logic circuit diagram will be derived.

- ####Recognition of inputs and outputs of given real world scenario
In this module we are proposing a format that user has to follow when providing the
scenario. The user has to provide the scenario as statements and each statement should
contain inputs and outputs according to any preferred order. The system identify the
particular inputs and outputs of each statements.

- ####Identify the relationship among statements which are given and derive the logical
model
This module mainly focuses on the relationships which can be identified among each of
the statements based on the inputs and outputs which were identified earlier. Moreover a
data structure should be implemented to keep the data already acquired. Also this module
responsible for derivation of ultimate Boolean expression of the provided scenario.

