# SpecStory Docs

This repo contains the source code for [Specstory's Documentation](https://docs.specstory.com).

Feed all of these docs into your LLMs context window: https://docs.specstory.com/llms-full.txt

Please open Pull Requests to suggest helpful changes!

## Development

Install the Mintlify CLI to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Troubleshooting

* Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.

* Page loads as a 404 - Make sure you are running in a folder with mint.json