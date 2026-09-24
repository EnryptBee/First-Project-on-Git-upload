# Computer Science 2B – Practical Assignment 04

## Practical Overview
This project was developed as part of Practical Assignment 04  for Computer Science 2B at the University of Johannesburg.  
The goal was to build a client-server network system that allows:
- Uploading simulated lunar surface images to the server
- Requesting a list of available images
- Downloading and displaying images by ID

I achieved a 78 mark for this practical.

 Server
- Runs on port  number
- Stores image metadata (ID, name, size) in a text file
- Handles requests:
  - List returns available images
  -Down <Down> → sends requested image
  - Up <ID> <Name> <Size> <Image> stores new image
Client
- JavaFX GUI for user interaction
- Uploads images to the server
- Requests and displays image list
- Downloads and shows images by ID


Project Structure
- src - Source code (Java)
- docs - Documentation + batch file
- bin - Compiled binaries it is empty when submitting
- data - Test data  one includes their test data
- lib - Optional libraries

How to Runnig it
1. Compile the source code using the batch file in docs
2. Start the server Server.java
3. Run the client Client.java
4. Use the GUI to upload, list, and download images.

 More info
- Code written in java and used Javafx
- Focused on networking UDP/DatagramPacket and GUI integration.
- Submission followed UJ guidelines and naming conventions.
  
  Marks 
Score 78%  
- Demonstrated understanding of client-server communication, file handling, and GUI design.
