# TTS Service Demo

Piping generative AI text into Azure TTS

Made for NatHacks23 as a service to retrieve TTS audio for output from a BCI decoder model
GPT can be replaced with BCI decoder model for Brain-to-Speech capability

### Usage

Expects the following keys:
```
COGLOG_GPT_TOKEN - OpenAI secret
COGLOG_TTS_KEY   - Azure speech service key
```

With Go installed:
`go run main.go`
