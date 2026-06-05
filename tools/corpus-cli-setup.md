# Corpus CLI Setup

## Objective

Set up Corpus Client CLI and authenticate successfully.

## Installing UV

```powershell
python -m pip install uv
```

## Clone Repository

```powershell
git clone https://code.swecha.org/corpus/corpus-client-cli.git
```

## Create Virtual Environment

```powershell
uv venv --python 3.14
```

## Install Dependencies

```powershell
uv sync
```

## Run CLI

```powershell
uv run corpus-client --help
```

## Troubleshooting

### Login Failed

Issue:

```text
Incorrect phone number or password
```

Resolution:

Used the correct API URL and credentials.

## Lessons Learned

- Working with CLI tools
- Using UV package manager
- API authentication
- Reading source code for debugging
