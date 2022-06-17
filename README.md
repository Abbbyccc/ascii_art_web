Welcome to the ASCII Art Generator. This is a program that can translate text into ASCII art that uses a web interface to receive and output data.

The method/algorithm we used is such:

Before translating the text, we prepare a library. Each letter in the text file containing the ASCII art representation of all the numbers, letters and punctuation is numbered with its ASCII code.

When the text is submitted, we take each letter one by one, and look at it's ASCII code. We can then go to this point in the text file, and return the ASCII art for that letter/symbol/number.  
We loop through the submitted text letter by letter until the whole phrase has been read.
We then return the completed block of ASCII art.


The authors are Chiachi Chien, Sabelo Mcanyana, and Jack Rowand.  


Instructions for use:


Please navigate to the folder "ascii-art-web" that you have downloaded from Github.

Run the program by typing "go run main.go". You may get a prompt from your firewall asking for permission. Please grant permission.

Open your browser of choice

Type "http://localhost:8080/asciiart" into the browser and press Enter.

To use the Ascii Art Generator, please type the words you would like to be transformed to ASCII art into the text box.

Next, choose your font by clicking one of the three buttons next to the font name.

When you click on the "Submit" button, you will see your text displayed as ASCII art below. Da DA!