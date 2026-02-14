# Datadog CLI query tool

Querying datadog from the terminal for automated purposes.

## Installation
Put the shell script somewhere on your PATH.  I like `~/.local/bin/`.

Install the datadog environment variables in your .bashrc or .zshrc file:

export DD_API_KEY=<api-key>
export DD_APPLICATION_KEY=<application-key>

## What it's doing
Sending a curl request to 'https://api.datadoghq.com/api/v2/logs/events/search'.  If that's not correct, open ddq and modify the url.

