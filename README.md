# CleverSlack

A Slack <-> Cleverbot bridge

## Running

Set your Slack token or bot Slack token as an environment variable named
`SLACK_TOKEN` and the run `mix run --no-halt`

```
SLACK_TOKEN=abc-123 mix run --no-halt
```

## Talking

The bot assumes you always directly reference him. If your bots name is "Fred"
you can talk to him like so:

```
blake: @fred: Whatsup?
fred: How are you doing?
blake: fred Good, you?
```

The rules are somewhat flexible, like permitting a single leading character and
having an optional `:` at the end of the name.
