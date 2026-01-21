# Stirling-pdf

A self-hosted application for managing stirling-pdf.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/stirling-pdf/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/stirling-pdf" ~/.local/srv/docker/stirling-pdf
cd ~/.local/srv/docker/stirling-pdf
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install stirling-pdf
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
