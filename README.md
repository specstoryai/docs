# SpecStory Docs

This repo contains the source code for [Specstory's Documentation](https://docs.specstory.com).

Feed all of these docs into your LLMs context window: https://docs.specstory.com/llms-full.txt

Please open Pull Requests to suggest helpful changes!

## Connect with Us!
<p align="left">
  <a href="https://twitter.com/specstoryai"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logoColor=white" alt="X" style="vertical-align: middle;"></a>
  <a href="https://www.linkedin.com/company/specstory"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" style="vertical-align: middle;"></a>
  <a href="https://discord.gg/E47yQyEUd3"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" style="vertical-align: middle;"></a>
  <a href="https://www.youtube.com/@specstory"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube" style="vertical-align: middle;"></a>
</p>

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
