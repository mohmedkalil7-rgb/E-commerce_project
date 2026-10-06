# ai e-commerce support agent

an n8n project that handles customer support and e-commerce tasks using ai and automated tools.

## features

- order lookup
- inventory lookup
- order cancellation
- human escalation
- shipping webhook
- interaction and error logging
- webhook authentication

## workflows

- customer support agent
- tool - get order
- tool - check inventory
- tool - cancel order
- tool - human escalation
- order shipped webhook

## stack

- n8n
- openrouter / deepseek
- n8n data tables
- webhooks

## security

webhooks use header authentication.

## testing

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
