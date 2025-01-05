# ADVANCE-TASK-2---CODTECH

**Name:** SHASHANK SATISH MISHRA

**Company:** CODTECH IT SOLUTIONS PVT. LTD

**ID:** CT0806DB

**Domain:** CYBER SECURITY AND ETHICAL HACKING

**Duration:** 3 WEEKS

**Mentor:** NEELA SANTOSH KUMAR

# Overview of the project

# Project: Web Application Vulneruability Scanner

### **Objective**

### Overview of Web Application Vulnerability Scanner Project

#### 1. **Objective**
The objective of this project is to develop a tool that can automatically scan web applications for common security vulnerabilities. These vulnerabilities include SQL Injection, Cross-Site Scripting (XSS), and others. The tool is intended to help web developers, security professionals, and organizations identify weaknesses in their web applications, allowing them to address these issues and improve overall security.

#### 2. **Key Features**
- **SQL Injection Detection**: Scans the web application for potential SQL Injection vulnerabilities by injecting typical attack payloads into URLs.
- **Cross-Site Scripting (XSS) Detection**: Tests for potential XSS vulnerabilities by injecting a script into URL parameters and checking for reflected XSS.
- **Easy-to-Use GUI**: The tool features a user-friendly GUI built with `tkinter` for easy interaction. Users can simply enter the URL to scan, press a button, and view the results in a scrolling text area.
- **Real-Time Output**: The scan results are displayed in real-time in the GUI, showing detailed messages about each vulnerability found during the scan.
- **Scalable**: The design can be expanded to detect other vulnerabilities like CSRF, command injection, file upload vulnerabilities, etc.
- **URL Validation**: Ensures that the input URL is valid (must begin with `http://` or `https://`).
- **Error Handling**: Handles network issues gracefully and provides informative error messages if any problem occurs during the scan.

#### 3. **How It Works**
- **Step 1**: The user enters the target URL in the input field of the GUI.
- **Step 2**: The user clicks the "Start Scan" button, which initiates the vulnerability scanning process.
- **Step 3**: The scanner sends requests to the URL with different attack payloads, such as SQL injection strings and XSS scripts, to test the website’s security.
- **Step 4**: As the scan progresses, the results are displayed in real-time in the output text area within the GUI.
- **Step 5**: If the tool detects any vulnerabilities (like SQL Injection or XSS), it will print a message indicating the vulnerability, along with the URL or input where it was found.
- **Step 6**: After completing the scan, the user can view the full results in the output area.

#### 4. **Components Used**
- **Python**: The main programming language used to build the scanner.
- **requests**: A Python library used for making HTTP requests to the target web application. It helps in sending GET requests to check how the application responds to different input strings.
- **BeautifulSoup**: A Python library for parsing and navigating HTML. It's used to analyze the response from the server and extract content if necessary (though this basic version doesn't heavily rely on it).
- **tkinter**: A Python library for building graphical user interfaces (GUIs). It is used to create the interactive interface for entering the URL and displaying the scan results.
- **re (Regular Expressions)**: Used for detecting specific patterns (such as error messages or script tags) in the server's response, indicating vulnerabilities like SQL Injection or XSS.
- **urllib.parse**: Helps with URL encoding, especially for injecting payloads into the query strings safely.

#### 5. **Application of the Project**
- **Web Application Security Testing**: This scanner can be used by security professionals, ethical hackers, and penetration testers to quickly identify vulnerabilities in web applications.
- **Web Development**: Developers can use the scanner during the development phase to test their web applications for common security flaws.
- **Educational Use**: This tool can serve as an educational resource to demonstrate common vulnerabilities in web applications and how attackers exploit them.
- **Small to Medium Businesses**: Organizations with limited resources for security can use this tool to periodically check their websites for basic vulnerabilities without the need for expensive security tools.
- **Bug Bounty Programs**: This tool can assist security researchers and bug hunters in scanning targets for vulnerabilities during bug bounty engagements.

### Conclusion
This Web Application Vulnerability Scanner provides a practical and efficient solution to identify and mitigate common vulnerabilities in web applications. The tool’s simplicity, combined with its ability to detect key vulnerabilities, makes it a valuable resource for improving web application security. The added GUI enhances usability and accessibility, making it suitable for both technical and non-technical users.

### **Glimpes of Output**
![image](https://github.com/user-attachments/assets/0fc70687-760c-45e4-969b-b809898045a4)

![image](https://github.com/user-attachments/assets/d18f57bd-2b1c-4689-9743-b95f99fc6aa9)
