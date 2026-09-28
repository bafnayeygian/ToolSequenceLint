# ToolSequenceLint

Validate AI agent tool-call sequences against declarative workflow rules, ordering constraints, prerequisites, and forbidden transitions.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/ToolSequenceLint.git
cd ToolSequenceLint
python -m pip install .
```

## Usage

```bash
tool-sequence-lint --help
```

## Development

```bash
python -m unittest discover -s tests -v
```
