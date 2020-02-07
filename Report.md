Name: Neeley Pate

EID: nap2552

Team Number:

## Questions

1. Why does your program need a setup and a loop?

	setup: happens once, sets initial variables and input / output
	loop: holds the actual code that's being run on the board / processor

2. What is the downside to putting all your code in a loop?

    one downside is the program will constantly loop, which must be accounted for when writing code

3. Why does your code need to be compiled?

    it takes the code that's written, checks it, and puts it into a language that the board / processor can understand (assmebly)

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

	the ratio between the on and off states becomes more inaccurate (less uniform, sometimes go smaller to larger to smaller)
	ideas: operating at higher frequencies for more accuracy; having user-controlled switches that go down gradually and could stabilize at each level;
		somehow having more control over the RMS voltage to ensure a more accurate estimate, and more accurate periods

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    it completes the circuit and allows the information to pass through the logic analyzer

6. What is the difference between synchronous and asynchronous communication?

    synchronous: run at the same pace
	asynchronous: run at different speeds

7. Profile of UART: Sent X bytes in Y time 

    sent "Hello" (6 bytes) in .512 ms

8. Profile of SPI: Sent X bytes in Y time

    

9. Why is SPI so much faster than UART?

    SPI: uses strong drive mode to drive the bus
	UART: uses push pull (has to rely on outside devices)

10. list one pro and one con of UART

    pro: only needs two wires for data communication
	con: can't hold several slave or master systems

11. list one pro and one con of SPI

    pro: very fast, synchronous
	con: requires more wires to connect than UART or I2C

12. list one pro and one con of I2C

    pro: only requires two pins to support multiple slaves
	con: lines are open drain --> require a pull up or pull down resistor

13. Why does I2C need external resistors to work?

    resistors are used to provide default states for signal line or GPIO pins

## Screenshots

Procedure A, step 1:
(arduino-lab-1-neeley-pate/img/FirstSSLab1FYDE.png)

Procedure A, step 4:
(img/SecondSS_lab1_FYDE.png)

Procedure B, UART:
(img/ThirdSS_Lab1.png)

Procedure B, SPI:
![Put path to your image here ->](img/placeholder.png)
