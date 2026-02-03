# Testing extension

Extension for testing extensions functionality.

## Custom commands

- This exposes the custom command "fs:grep-code". 
- This should echo back the API key provided in settings.

## Hooks

- Hoos will be invoked before model calls.
- Should echo a sentence followed by the API key provided by settings.

## Skills

- Invoke by saying "hello"
- Should respond with a greeting and the API key.

## MCP server

- Exposes a prompt "/poem-writer"
- Exposes a tool "get-key"
- Should add to the system instructions-- confirm by saying 'foo', which should get back 'bar', and then 'soda' should get back 'pop'

## Custom context

- 'new' should get back 'york city'
- 'raindrops' should get back 'on roses'