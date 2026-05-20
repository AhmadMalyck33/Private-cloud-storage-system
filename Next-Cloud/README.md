# Next-Cloud

This project contains a Nextcloud instance running with Docker Compose.

## Setup

1. Copy the example environment file:
   ```powershell
   copy .env.example .env
   ```

2. Edit `.env` with your own values.

3. Start the services:
   ```powershell
   docker compose up -d
   ```

## Files

- `docker-compose.yml` — Docker Compose configuration for MySQL, Redis, and Nextcloud.
- `.env.example` — Example environment variables.
- `.gitignore` — Ignore local secrets and common files.

## Notes

- Do not commit `.env` to GitHub.
- Use `.env` to store sensitive values like database passwords.
