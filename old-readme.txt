<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">
  <img src="https://i.postimg.cc/HWRH4rBx/Full-(1).png" alt="microsoft windows wallpaper">
</p>

<p align="center">An open-source activation utility for Windows and Microsoft Office, featuring multiple activation methods including HWID, Ohook, TSforge, and Online KMS. It also provides advanced troubleshooting tools and diagnostic features to help resolve activation-related issues efficiently.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-8.1%20%7C%2010%20%7C%2011-blue" alt="Windows">
  <img src="https://img.shields.io/badge/Office-Supported-green" alt="Office">
  <img src="https://img.shields.io/badge/License-Open%20Source-orange" alt="License">
</p>

<hr>
  
## How to Activate Windows / Office / Extended Security Updates (ESU)?

### 🚀 Method 1 — PowerShell (Recommended)

1. Open the **Start Menu**.
2. Search for **PowerShell** and launch it.
3. Copy and paste the following command, then press **Enter**.
   
**For Windows 8.1, Windows 10, and Windows 11:**

```powershell
irm https://get.activated.win | iex
```

---

### 📷 Full process overview:

<p align="center">
  <img src="https://i.postimg.cc/3xRbg0Lc/Screenshot-2026-05-31-080557.png" alt="#">
</p>

<p align="center">
  <em>Enter the command in PowerShell</em>
</p>

---

### 🔹 Select an Activation Method

Choose one of the following activation methods:

  1. HWID 
  2. Ohook
  3. TSforge
  4. Online KMS

<p align="center">
  <img src="https://i.postimg.cc/76dTQdDV/Screenshot-2026-05-31-081948.png" alt="#">
</p>

<p align="center">
  <em>Select the desired activation method</em>

---

### 🔹 Activation Process

</p>
    <p align="center">
  <img src="https://i.postimg.cc/fb5L1F7c/Screenshot-2026-05-31-081629.png" alt="#">
</p>

<p align="center">
  <em>Activation process completed successfully</em>
</p>


---


### 🔹 Activation Confirmation

</p>
    <p align="center">
  <img src="https://i.postimg.cc/ZnWC8cdr/Screenshot-2026-05-31-081500.png" alt="#">
</p>

<p align="center">
  <em>Windows successfully activated</em>
</p>


---

### ⚠ Alternative Command

If the main command is blocked by your ISP or DNS provider, try the following command (requires an updated version of Windows 10 or Windows 11):

```powershell
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
```

> **Note:** If the script does not launch, follow **Method 2** below.

4. When the menu appears, enter the number corresponding to one of the **Green** activation options.

---

## 🖥️ Method 2 — Traditional Method (Windows Vista and Later)

### Step 1 — Download the Script

* **Direct Script**  

  *  [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) (Direct script)
  *   [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip) (If the direct script is blocked by your browser)



### Step 2

Run the downloaded **MAS_AIO.cmd** file.

### Step 3

When the menu appears, select one of the **Green** activation options by entering its corresponding number.

---


> [!NOTE]
> - This guide is intended for educational and documentation purposes only.
> - An active internet connection is required during the activation process.
> - Temporarily disabling antivirus software may be necessary if it blocks the script execution.
> - Always download scripts from official and trusted sources.
> - Make sure you are running PowerShell with administrator privileges for best compatibility.
> - Some activation methods are designed for specific Windows or Office editions. Choose the appropriate method according to your system requirements.

---

> [!TIP]
> - Use **HWID** for permanent Windows activation whenever supported.
> - Use **Ohook** for Microsoft Office activation.
> - If one activation method fails, try another available method.
> - Keep Windows and Office updated before running the activation script.
> - Restart your computer after activation to ensure all changes are applied properly.
> - Verify activation status after completion through Windows Settings or Office Account settings.

---

## 🔗 Official Links

### Home - [https://massgrave.dev/](https://massgrave.dev/)
### GitHub - [Massgravel](https://github.com/massgravel/Microsoft-Activation-Scripts)


---

## ⚠ Disclaimer

This repository is provided for informational and educational purposes only. Users are responsible for complying with Microsoft's licensing terms and applicable laws. The repository owner does not host, modify, or distribute any activation software and is not responsible for how third-party tools are used.
