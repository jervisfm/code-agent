# code-agent
Exploring a simple code agent

# Introduction
Some exploratory code on building a large language model (LLM) Agent.

This uses Claude API, so need some credits and API key.

Set your API key in the environment variable `CLAUDE_API_KEY`

```bash
export CLAUDE_API_KEY=your_api_key
```

# Usage

## Once set up
Initial set up.
```bash
sudo apt-get install golang
go get
go build
```

## Main Command
go run agent

## Notes
This will execute and run commands from the LLM via tools while accomplishing user tasks.

As such, it _should_ be run in an isolated / disposable environment to avoid any potential risks.

A good test environment would be github codespaces (github.com/codespaces). Files would be version controlled, so any mishaps can be reverted and that environment is isolated/can easily be recreated.
