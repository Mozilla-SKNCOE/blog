#HeadingSecrets message in Java

A Java program that allows a user to send a “secret message” to a friend. To encode the string you are going to use an encoding integer.
The encoding integer will be an offset value that is added to the Unicode value of each character in the string.

Example of how the encoding integer will work: The letter ‘A’ has a Unicode code value of 65. If the encoding integer for your program is 10,
your program would add 10 to the Unicode value for ‘A’ making it 75. The letter ‘K’ is represented by the Unicode value 75. 
So if the secret message was “MEET ME AT 8” and the encoding integer was 10, the encoded message is “WOO^*WO*K^*B”.

Your program should include the following methods:
A method named AskForString: This method should request that the user enter the string they would like to encode. Ask the user to enter a string that has all capital letters.
If the user does not enter a String with all capital letters the program should convert the String to a String with all capital letters. 
This method should return the String to the calling method (in this case the calling method will be the main method).

A method named Encoder: This method should accept two values: the encoding integer and the string to be encoded. 
The method should encode the String and then return the encoded String.

A method named Decoder: This method should accept two values: the encoding integer and the encoded string. 
This method should decode the String and then return the decoded String.

The main method: The main method should first ask the user to enter a string. The main method is also responsible for generating the encoding integer, which should be a random integer between 1 and 35 (HINT: You need the Random class). 

Authur:Pratik Lohakare<br>
Country:India
