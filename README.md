# README: DVWA Installation and SQL Injection Testing

This repository provides the necessary files and instructions for setting up **Damn Vulnerable Web Application (DVWA)** using Docker. The accompanying PDF report contains detailed steps for installation, usage, and performing SQL injection tests across various security levels.

## Quick Overview

### Prerequisites
- Git
- Docker
- Burp Suite (used for SQL injection testing)

### Installation Steps

1. **Clone the Repository**
   ```
   git clone https://github.com/eystsen/pentestlab.git
   ```

2. **Navigate to the Repository**
   ```
   cd pentestlab
   ```

3. **Install Docker**
   ```
   sudo apt install docker.io
   ```

4. **Start DVWA**
   ```
   /pentestlab.sh start dvwa
   ```

5. **Access the DVWA Web Interface**
   - URL: `http://dvwa`
   - **Default Credentials**:  
     - Username: `admin`  
     - Password: `password`

## SQL Injection Testing

For details on performing SQL injection at **low**, **medium**, and **high** security levels, please refer to the full PDF report included in this repository.

## Additional Information
The PDF report provides a step-by-step guide to the entire process, including screenshots and SQL injection payloads used for testing DVWA vulnerabilities at various security levels.

