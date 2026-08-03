# ECU Communication & Diagnostic Validation Platform

## Overview

An Embedded Test Automation framework developed in Python for validating ECU communication and diagnostic services over CAN/CAN FD.

The framework automates ECU validation by sending diagnostic requests, verifying responses, logging communication, and generating automated test reports.

---

## Features

- ECU Communication
- CAN/CAN FD Support
- UDS Diagnostics
- Read & Clear DTC
- ECU Reset
- Diagnostic Session Control
- Security Access
- Tester Present
- Automated Regression Testing
- HTML & CSV Report Generation
- Communication Logging

---

## Technologies

- Python
- PyTest
- python-can
- CAN
- CAN FD
- UDS (ISO 14229)
- CAN TP (ISO 15765)
- YAML
- JSON

---

## Folder Structure

```
src/
diagnostics/
protocols/
tests/
reports/
scripts/
docs/
```

---

## Run

```bash
pip install -r requirements.txt

python src/main.py
```

---

## Future Improvements

- LIN Support

- Automotive Ethernet

- CAPL Integration

- CANoe Integration

- Jenkins CI/CD

- Hardware-in-the-loop Testing

---

## License

MIT
