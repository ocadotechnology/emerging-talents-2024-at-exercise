# *Getting Started*

Get started by creating a fork of this repository. Do feel encouraged to go above and beoynd when it comes to additional features and enhancements that are not part of this document.

### *Deadline*

* April 1st 2024

### *Submission Guidelines*

Submit the source code of your web server and web client along with any necessary configuration files.
Include documentation detailing how to set up and run the server and client locally on the chosen operating system.
Provide a brief explanation of your design choices, challenges faced, and any additional features implemented.

### *Evaluation Criteria*

* Functionality - Does the web server and client fulfill the requirements outlined in the assignment?
* Code Quality - Are the code for the server and client well-structured, readable, and properly documented?
* User Interface - Is the UI of the web client intuitive and user-friendly?
* Error Handling - How effectively are errors handled throughout the application?
* Security - Are appropriate security measures implemented to protect server resources?

# *Key Objectives*

Implement a web server that interacts with the file system, allowing users to perform basic file operations such as uploading, downloading, renaming files, and navigating through the folder structure.

### *Web Server*

Develop a web server using either Golang, Node.JS, Python or Java. Focus on a single operating system - Linux, Windows or OS X. The server shall be able to flawlessly work with the chosen operating system. All capabilities are to be exposed via HTTP requests and responses.

##### API

* __*[Optional]*__ Create API documentation that provides details about the supported requests and responses.

##### Security Considerations

* __*[Optional]*__ Implement appropriate security measures to prevent unauthorised access to files and server resources.
* __*[Optional]*__ Use techniques such as authentication and authorization to ensure data integrity and confidentiality.

##### File System Interaction

* Implement functionalities to interact with the file system (incl. upload, download, delete, rename) as well as navigating through the folder structure.
* Ensure appropriate error handling for file operations.

### *Web Client*

Create a web client with a simple user interface (UI) to interact with the web server. The web client can be developed using HTML, CSS, and JavaScript (or other). Besides the ability to navigate the file system, it should be also possible to upload, download and rename files. Looks isn't everything... unless we're talking about UI - we'd love to see one that is both intuitive and user-friendly.

##### Folder Navigation

* Allow users to navigate through the folder structure of the file system using the web client.
* Display the current directory and list its contents (files and subfolders) in the UI.
* Provide options for users to navigate into subfolders and navigate back to parent folders.

##### File Manipulation

* Allow users to upload files to the server through the web client.
* __*[Optional]*__ Implement validation to restrict the types and sizes of files that can be uploaded.
* Enable users to download files from the server through the web client.
* Ensure that downloaded files are intact and identical to the original files.
* Provide functionality for users to rename files stored on the server through the web client.
* __*[Optional]*__ Validate user inputs and handle renaming operations securely.

