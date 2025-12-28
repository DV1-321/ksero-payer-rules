![PyPI](https://img.shields.io/pypi/v/ksero-payer-rules)
![Python](https://img.shields.io/pypi/pyversions/ksero-payer-rules)
![License](https://img.shields.io/github/license/yourusername/ksero-payer-rules)
![Tests](https://img.shields.io/github/actions/workflow/status/yourusername/ksero-payer-rules/tests.yml)

# Ksero Payer Rules

Payer-specific rules and validation for medical, dental, and vision insurance cards.

## Features

- Detects payer and specialty (medical, dental, vision)
- Extracts member ID, group number, plan name, policy holder
- Validates payer-specific ID formats (UHC, Aetna, Cigna, BCBS, VSP, etc.)
- Supports TRICARE, CHAMPVA, Medicare, Medicaid

## Installation

```bash
pip install ksero-payer-rules
