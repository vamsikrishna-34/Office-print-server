Office Print Server is a network-based printing application that allows users to access the print server from devices connected to the same Wi-Fi network.
Features
Access the print server through a web browser.
Upload documents for printing.
Support for file uploads up to 25 MB.
Select the number of copies (up to 99).
Print job queue management.
Support for Windows printer integration using SumatraPDF.
Local network access.
Test and print server functionality.
Technologies & Tools
JavaScript
Node.js
HTML, CSS
Windows Printer Integration
SumatraPDF
Project Structure
lib/ – Supporting libraries
printers/ – Printer-related modules
public/ – Frontend files
test/ – Testing files
server.js – Main server application
package.json – Project dependencies
.env.example – Example configuration
start.bat – Server startup script
How to Run
Download or clone this repository.
Install the required dependencies using npm install.
Configure the environment settings using .env.example as a reference.
Run the start.bat file on Windows.
Open the server address displayed in the terminal using a web browser connected to the same network.
