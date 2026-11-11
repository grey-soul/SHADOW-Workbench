# SHADOW

### Intelligence Workbench — Educational Cybersecurity Project

SHADOW is a local-first educational cybersecurity and research workbench built with Python, HTML, CSS and JavaScript.

## Features

- DNS Lookup — resolve domain names through the system DNS resolver.
- URL Inspector — inspect URL components without connecting to the destination.
- Hash Generator — generate SHA-256, SHA-1 and MD5 hashes.
- Dark green responsive dashboard.
- Local-only web server.

## Requirements

- Python 3.9 or newer.
- Kali Linux, Linux, macOS or Windows.
- No external Python packages required.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Shadow.git
cd Shadow
```

## Run

```bash
python3 app.py
```

Open the dashboard in your browser:

http://127.0.0.1:8080

Stop the server with:

```bash
CTRL+C
```

## Project Structure

```text
Shadow/
├── app.py
├── README.md
└── static/
    └── index.html
```

## Security and Responsible Use

SHADOW is intended for educational purposes and authorized research.

- The web server listens only on 127.0.0.1.
- DNS lookup uses the system resolver.
- URL inspection is static and does not connect to the target.
- Hash generation is performed locally.
- No external Python dependencies are required.

## Version

1.0.0

## License

Choose and add an appropriate open-source license before distributing the project.