# Ai e-commerce support agent

an n8n project that handles customer support and e-commerce tasks using ai and automated tools.

## Features

- order lookup
- inventory lookup
- order cancellation
- human escalation
- shipping webhook
- interaction and error logging
- webhook authentication

## Workflows

- customer support agent
- tool - get order
- tool - check inventory
- tool - cancel order
- tool - human escalation
- order shipped webhook

## Stack

- n8n
- openrouter / deepseek
- n8n data tables
- webhooks

## Security

webhooks use header authentication.

## Testing

tested:
- valid and invalid orders
- inventory lookup
- allowed/rejected cancellation
- human escalation
- shipping updates
- missing input
- ai errors
- invalid authentication
- hallucination prevention
