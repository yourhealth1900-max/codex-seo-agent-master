# Config Directory

## Purpose
This directory contains configuration files for the Codex SEO Agent system settings, API keys, and environment variables.

## Structure
```
/config/
├── agent_config.yaml        # Agent behavior settings
├── api_config.yaml          # API endpoints and credentials
├── workflow_config.yaml     # Workflow automation settings
└── monitoring_config.yaml   # Performance monitoring settings
```

## Configuration Files

### agent_config.yaml
- Agent personality and behavior
- Task execution parameters
- Resource limits and thresholds
- Logging and debugging settings

### api_config.yaml
- API endpoint URLs
- Authentication credentials (use environment variables)
- Rate limiting settings
- Timeout and retry configurations

### workflow_config.yaml
- Task scheduling and triggers
- Workflow chain definitions
- Notification settings
- Error handling rules

### monitoring_config.yaml
- Performance metrics to track
- Alert thresholds
- Reporting frequency
- Data retention policies

## Security Notes
⚠️ **IMPORTANT**: Never commit sensitive data like API keys or passwords
- Use environment variables for secrets
- Add `.env` files to `.gitignore`
- Use configuration templates with placeholders
- Document required environment variables in README
