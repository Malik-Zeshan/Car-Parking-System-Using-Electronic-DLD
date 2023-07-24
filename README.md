# Car-Parking-System-Using-Electronic-DLD
Car parking System to keep track the total parking slot, available slot and occupied slot. Build through DLD and Electronics concept using Basic gates, Registers, different IC's etc.
# Objectives:
The objective of our project is to show the students how a parking indicator is generally working. It shows how the parking systems work in malls or hospitals. The project is not exactly the same but its mechanism is similar to those. This project is just giving the idea of those system. 
# Equipment:
	Breadboard
	Wires
	7 segment display 
	Not Gate (7404)
	And Gate (7408)
	Or Gate (7432)
	BCD to 7 segment decoder (74LS48)
	Switches
	IC 74190 (up/down counter)
	IR LED’s
	 Resistors 
	 Battery (9V)
# Introduction:
It is a project that is designed by our team as a second semester project for DLD course. In this project we are going to be utilizing digital logics to create a parking system. Our parking system has a 7-segment display which will display the maximum number of slots available. There will be two switches used in the circuit one for number of cars entering and the other for leaving. LED will glow in case of no occupied space left.
# Working:
First we take the up/down counter IC 74190 we connect the enable input with 0 because it is active low input and we connect the parallel loading with 1 because we are not using it. For inputs we take two buttons separately for moving and down. The inputs are passed through the OR gate. The output of the OR Gate passes through to the next AND gate whose output is passed through CLK. The AND gate consists of three inputs one from the OR gate, the other is the inverted output of the terminal count or total count and ripple count. The AND gate is only deactivated when either the total count is zero or the ripple count is zero. The ripple count is only zero when it is either nine or zero displayed on the 7-segment which also results in the LED to glow.
# Conclusion: 
The following project made us understand a better learning of our DLD concepts, how to implement it, make analysis and design it more efficiently. The project consist of the very basic knowledge that we learned in the Lab. It made us improve in circuiting.
# Results:
The results as you can see in the picture the red will glow in case of all slots occupied as the 7-segment displays 0. The second time the LED will glow when the user tries to enter more cars leaving when there is already no cars in the parking slots.

