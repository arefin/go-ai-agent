# go-ai-agent
Code following Thorsten Ball's How to Build an Agent tutorial at <https://ampcode.com/how-to-build-an-agent>. This repo was created for the June 5, 2025 meeting of the [Sacramento Software Engineers](https://www.sacswe.org) Meetup.

> **Note:** To run the code you will need an Anthropic API key set in the environment variable ANTHROPIC_API_KEY.

## Development Setup
Copy `env.example.sh` to `env.sh` and add your Anthropic API key.
Run `source ./env.sh` before starting development.

## How to run the examples in each subdirectory.
```bash
# Download the dependencies
go mod tidy
# Run it
go run main.go
```