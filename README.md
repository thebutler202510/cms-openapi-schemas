
# CMS OpenAPI Schemas

This repository contains a split set of OpenAPI schema files generated from the official CMS data catalog.

## 📦 Contents

The `schemas/` folder contains modular OpenAPI JSON files:
- Each file is named `cms_schema_part_X.json`
- Each schema includes up to 100 CMS API endpoints

## 🌐 Hosting Instructions

To use with [ChatGPT Actions](https://platform.openai.com/docs/guides/gpt/actions):
1. Enable [GitHub Pages](https://pages.github.com/) in your repo settings.
2. Set source to the root or `/docs` folder.
3. Reference schema URLs like this:

```
https://<your-username>.github.io/<your-repo>/schemas/cms_schema_part_1.json
```

## 🧠 Example Use Case

Import each part into your GPT via `Actions → Import from URL`.

## 🛠️ License

Public data compiled from [data.cms.gov](https://data.cms.gov)
