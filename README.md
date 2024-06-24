Technohack Internship Tasks
This repository contains the tasks I completed during my 4-week internship at Technohack. Each task demonstrates my learning and application of various technologies and concepts.
Task 1: Finding an XSS Vulnerability Using Burp Suite
Description
The objective of this task was to identify a Cross-Site Scripting (XSS) vulnerability on a demo website using Burp Suite. This task helped me understand web security concepts and the practical application of Burp Suite for web vulnerability scanning.

Implementation
Setup Burp Suite:

Download and install Burp Suite.
Configure your browser to work with Burp Suite by setting up the proxy settings.
Interception and Analysis:

Open Burp Suite and navigate to the "Proxy" tab. Ensure that "Intercept" is turned on.
Visit the demo website in your browser and interact with various input fields and forms.
Finding the Vulnerability:

Use Burp Suite to intercept and analyze the HTTP requests and responses.
Identify any parameters that are reflected in the response without proper sanitization.
Injecting Payloads:

Use common XSS payloads such as <script>alert('XSS')</script> in the identified input fields.
Observe the response in Burp Suite and the browser to check if the payload gets executed.
Confirming the Vulnerability:

Once the payload is executed, confirm the presence of the XSS vulnerability.
Document the findings with screenshots and detailed steps.
Usage
To replicate the vulnerability discovery process:

Clone this repository.
bash
Copy code
git clone https://github.com/yourusername/technohack-internship-tasks.git
Navigate to the task1 directory.
bash
Copy code
cd technohack-internship-tasks/task1
Follow the steps outlined in the implementation section to set up Burp Suite and identify XSS vulnerabilities.
Files
xss_vulnerability_report.pdf: Detailed report of the XSS vulnerability discovery, including screenshots and step-by-step instructions.
burpsuite_project_file.burp: Burp Suite project file containing the captured HTTP requests and responses for the demo website.
