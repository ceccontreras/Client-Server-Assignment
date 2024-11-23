Prime Number Client/Server Application
Overview
This project demonstrates a simple client/server application where the client sends a number to the server
to determine if it's a prime number. The server processes the number, checks if it is prime, and sends the
result ("yes" or "no") back to the client. The client then displays the result in its GUI.

Features
Client Application:

Accepts user input for a number.
Sends the input to the server for processing.
Displays the server's response (whether the number is prime).
Server Application:

Receives a number from the client.
Determines if the number is prime using a custom algorithm.
Sends the result ("yes" or "no") back to the client.
Displays logs of received numbers and their results.
Prerequisites
Java 8: This application uses JavaFX, which is only included in JDK 8.
IDE: Any Java-compatible IDE such as IntelliJ IDEA or Eclipse.
Network: Both client and server should run on the same machine for testing purposes (using localhost).
How to Run
Set up Java 8:

Install JDK 8 and ensure it's configured in your IDE.
Adjust your project's Java version settings to use JDK 8.
Run the Server:

Start the Server application first to open a socket on port 8000.
Run the Client:

Start the Client application.
Enter a number into the input field and press Enter to check if it is prime.
Check Results:

The client will display the server's response.
The server will log the request and the result.
