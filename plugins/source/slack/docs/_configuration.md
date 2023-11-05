```yaml copy
kind: source
# Common source-plugin configuration
spec:
  name: slack
  path: cloudquery/slack
  registry: cloudquery
  version: "VERSION_SOURCE_SLACK"
  tables: ["*"]
  destinations: ["DESTINATION_NAME"]

  # Slack specific configuration
  spec:
    token: "<YOUR_BOT_TOKEN_HERE>"
```