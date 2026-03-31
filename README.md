# 🔍 Simple Port Scanner

## 📌 Description

A lightweight Python-based port scanner that checks for open ports on a target IP address.
This tool is useful for basic network reconnaissance and learning how port scanning works in cybersecurity.

---

## ⚙️ Features

* Scans common ports (21, 22, 23, 25, 53, 80, 443)
* Fast and simple execution
* Beginner-friendly code
* No external libraries required

---

## 🧠 How It Works

The tool uses Python's built-in `socket` module to attempt TCP connections to a list of common ports on a target machine.
If a connection is successful, the port is considered **open**.

---

## 🚀 Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/port-scanner.git
cd port-scanner
```

### 2. Run the script

```bash
python tool.py
```

### 3. Enter target IP

Example:

```
Enter target IP: 192.168.1.1
```

---

## 🧾 Example Output

```
Scanning 192.168.1.1...

Port 22 is OPEN
Port 80 is OPEN
```

---

## ⚠️ Disclaimer

This tool is intended for **educational purposes only**.
Do not use it on networks or systems without proper authorization.

---

## 🛠️ Future Improvements

* Add custom port range scanning
* Implement multithreading for faster scans
* Add service/banner detection
* Export results to a file

---

## 👨‍💻 Author

Aswin K

---

## ⭐ Contribute

Feel free to fork this repository and improve the tool.
Pull requests are welcome!
