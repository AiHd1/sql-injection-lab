# SQL Injection Lab with SQLmap

This repository provides a sandboxed environment to learn about SQL Injection and how to use SQLmap to exploit it. The lab includes a simple web application with vulnerable endpoints for educational purposes.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/sql-injection-lab.git
   cd sql-injection-lab
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start the Vulnerable Web Application:**
   ```bash
   python app.py
   ```

4. **Run SQLmap:**
   Use SQLmap to exploit the SQL Injection vulnerability. For example:
   ```bash
   sqlmap -u "http://