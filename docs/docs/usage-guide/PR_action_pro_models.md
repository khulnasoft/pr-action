## PR-Action Pro Models

The default models used by PR-Action Pro are a combination of Claude-3.5-sonnet and  OpenAI's GPT-4 models.

Users can configure PR-Action Pro to use solely a specific model by editing the [configuration](https://pr-action-docs.khulnasoft.com/usage-guide/configuration_options/) file.

For example, to restrict PR-Action Pro to using only `Claude-3.5-sonnet`, add this setting:

```
[config]
model="claude-3-5-sonnet"
```

Or to restrict PR-Action Pro to using only `GPT-4o`, add this setting:
```
[config]
model="gpt-4o"
```
