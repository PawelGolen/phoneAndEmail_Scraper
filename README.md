# 📋 Clipboard Phone & Email Extractor (Python)

This project is a **Python utility script** that automatically extracts **phone numbers and email addresses**
from any text copied to the clipboard using **regular expressions (regex)**.

It is a lightweight automation tool useful for quick data cleaning, text parsing, and preprocessing tasks.

---

## 🔍 What the Script Does

1. Reads text directly from the system clipboard
2. Uses **regular expressions (regex)** to identify:
   - Phone numbers (with optional area codes and extensions)
   - Email addresses
3. Extracts all detected values
4. Copies the cleaned results **back to the clipboard**

---

## 📌 Supported Formats

### 📞 Phone numbers
- 415-555-0000
- (415) 555-0000
- 555-0000
- 555-0000 ext 12345
- x1234

### 📧 Email addresses
- name@example.com
- name.surname@company.co
- name+tag@domain.org

---

## 🧰 Tech Stack

- **Python 3**
- **re** – regular expressions
- **pyperclip** – clipboard access

---

## 🚀 How to Use

1. Install dependency:
   ```bash
   pip install pyperclip
   ```

2. Copy any text containing phone numbers or emails

3. Run the script:
   ```bash
   python clipboard_phone_email_extractor.py
   ```

4. Paste the clipboard contents – extracted values will be ready to use

---

## 🧠 Example Use Cases

- Cleaning contact data from raw text
- Extracting emails from logs or documents
- Preparing datasets for further analysis
- Automation of repetitive copy-paste tasks

---

## 📄 Notes

- The script operates entirely on clipboard data
- No files are read or written
- Designed as a **simple automation / utility script**

---

## 📄 License

This project is available under the **MIT License**.
