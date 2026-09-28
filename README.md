# Green Vital Digital Marketing Operating System

A self-hosted digital marketing and automation platform for Green Vital.

## Organizations

- Green Vital Environmental & Engineering Consultancy Company
- Green Vital Travel & Tour

## Purpose

The system is designed to centralize and automate:

- Content planning and creation
- Social media publishing
- Marketing workflows
- Customer communication
- AI-assisted research
- AI agents
- Analytics and reporting
- Media processing
- Knowledge management
- Business automation

## Core Technology

- Docker
- n8n
- Postiz
- Chatwoot
- Ollama
- Open WebUI
- PostgreSQL
- Qdrant
- FFmpeg
- Whisper.cpp
- Git
- GitHub

## Project Structure

agents/       AI agents
backups/      Backups
config/       Configuration
content/      Marketing content
data/         Local application data
docker/       Docker service configuration
docs/         Documentation
logs/         Application logs
media/        Generated and working media
scripts/      Automation scripts
workflows/    n8n and automation workflows

## Security

Secrets and credentials must never be committed to GitHub.
Environment-specific secrets belong in .env, which is excluded from Git.

## Status

Initial infrastructure setup.
