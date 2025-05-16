# README.md
"""
# PubStomp

**PubStomp** is an asynchronous pentesting toolkit designed for efficient reconnaissance, vulnerability fuzzing, and reporting against web applications.

## Features
- 🔎 Async web crawling and spidering
- 🎯 Custom wordlists for fuzzing endpoints
- 🔐 Optional XSS payload testing
- 🧪 Report generation to JSON
- 🎨 Colored terminal output with progress bars
- 💾 Configurable output and log file paths

## Installation
Install via pip from source:

```bash
pip install .
```

Or once published:
```bash
pip install pubstomp
```

## Usage
Set your output and log paths:

```bash
pubstomp --setoutput ~/targets
pubstomp --setlog ~/logs/pubstomp.log
```

Run a scan:
```bash
pubstomp example.com --depth 2 --xss --report
```

Check saved paths:
```bash
pubstomp --showoutput
pubstomp --showlog
```

## CLI Options
```bash
pubstomp -h
```
Prints all command-line options.

## License
This project is licensed under the MIT License.
"""
