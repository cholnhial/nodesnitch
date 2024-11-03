# 🕵️ NodeSnitch

A simple Java tool to find and analyze node_modules directories in your system, demonstrating modern Java features for scripting.

## 🎯 Purpose

NodeSnitch helps developers identify and manage disk space usage by node_modules directories across their system. It's also a showcase for modern Java features that make the language more accessible for scripting and quick tools.

## ✨ Featured Java Improvements

### 📜 Unnamed Classes (JEP 445)
This tool demonstrates the use of [JEP 445: Unnamed Classes and Instance Main Methods](https://openjdk.org/jeps/445), which allows for simpler, script-like Java code without the traditional class boilerplate. This makes Java more approachable for beginners and better suited for small utilities.

### 🚀 Shebang Files (JEP 330)
[JEP 330: Launch Single-File Source-Code Programs
](https://openjdk.org/jeps/330) introduced support for running Java source files directly using a shebang (#!) line. This allows Java files to be executed like shell scripts, making it more convenient for command-line tools.

## 🛠️ Requirements

- Java 23 or later
- Unix-like operating system (Linux, macOS)
- Read access to your home directory

## 🏃 Usage

Simply run the script from your terminal:
1. Clone the project
2. Make it executable:
   ```bash
   cd nodesnitch
   chmod +x ./nodesnitch
   ./nodesnitch
   ```

The tool will:
1. Search your home directory for `node_modules` folders
2. Calculate the size of each directory
3. Display results sorted by size (largest first)

## 📊 Output Example

```
Scanning for node_modules directories...

Found node_modules:
/Users/dev/project1/node_modules (1.2 GB)
/Users/dev/project2/node_modules (856 MB)
/Users/dev/test/node_modules (234 MB)

Total space used: 2.29 GB
```

## 📝 License

MIT License
