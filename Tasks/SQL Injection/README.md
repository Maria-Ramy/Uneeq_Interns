# 🔍 SQL Injection Detection & Exploitation Tool  

This Python-based tool is designed to identify and exploit **SQL Injection vulnerabilities** in web applications. It serves as an educational resource for security professionals and learners, helping them understand SQL Injection techniques and defensive measures.  

---

## 💡 Key Features  

- ✅ Detects SQL Injection vulnerabilities using **error-based** and **boolean-based** techniques.  
- ✅ Automates **payload injection** to test for potential weaknesses.  
- ✅ Offers **UNION-based SQL Injection** exploitation to retrieve database information.  
- ✅ Includes **customizable payloads** and **error messages** for enhanced detection.  
- ✅ Provides **detailed response analysis** for better insight.  

---

## ⚙️ Requirements  

- **Python 3.x**  
- **requests** library  

### 📥 Installation  

Ensure dependencies are installed by running:  

```bash
pip install requests
```  

---

## 🚀 How to Use  

### Clone the Repository  

```bash
git clone https://github.com/your-username/sql-injection-tool.git
cd sql-injection-tool
```  

### Run the Script  

```bash
python3 sql_injection_tool.py
```  

### Provide the Target URL  

Enter the URL in the following format:  

```
http://example.com/page.php?id=
```  

### Detection & Exploitation  

- If a vulnerability is found, the script will prompt you to attempt **exploitation**.  
- It uses **UNION-based SQL Injection** to extract **database details** if possible.  

---

## 🧪 How It Works  

### **Detection**  
- Sends various **SQL injection payloads** to test for vulnerabilities.  
- Analyzes responses for **error messages** or unexpected behavior.  

### **Exploitation (If Vulnerable)**  
- Attempts to retrieve **database names** using **UNION-based SQL Injection**.  
- Searches responses for **database-related identifiers** such as `information_schema`.  

---

## ⚠️ Legal Disclaimer  

This tool is meant strictly for **educational** and **authorized security testing** purposes. **Unauthorized use** on systems without permission is **prohibited**. The author is **not liable** for any misuse or unintended consequences.  

---

**Happy and responsible hacking!** 🚀💻  
