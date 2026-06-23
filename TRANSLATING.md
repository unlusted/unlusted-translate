# Translation Guide

Thank you for helping translate Unlusted. This guide covers everything you need to get started.

## Getting started

1. **Create an account** at [translate.unlusted.com](https://translate.unlusted.com)
2. **Pick a language** from the project dashboard
3. **Start translating** — no technical setup required, everything happens in the browser

New translations are reviewed before going live. Once approved, they ship with the next platform update.

## Translation guidelines

### Tone
Unlusted is a premium adult platform. Translations should feel natural, confident, and professional in the target language. Avoid overly literal translations — prioritise clarity and natural phrasing over word-for-word accuracy.

### Placeholders
Some strings contain placeholders like `{name}`, `{amount}`, or `{date}`. These must be kept exactly as-is in your translation — they are replaced with real values at runtime.

Example:
```
English:  "Welcome back, {name}"
Spanish:  "Bienvenido de nuevo, {name}"  ✓
Spanish:  "Bienvenido de nuevo, nombre"  ✗
```

### Special characters
Ellipses (`...`), em dashes (`—`), and other punctuation should follow the conventions of the target language, not necessarily match the English source.

### Legal and policy strings
The platform includes translated Terms & Conditions and Privacy Notice content. These should be translated accurately and naturally. If you are unsure about a legal term, leave a comment on the string in Weblate and a maintainer will assist.

### Adult content context
Some strings relate directly to adult content, live streaming, and creator monetisation. Translate these naturally for an adult audience in the target language — there is no need to soften or sanitise the meaning.

## Suggesting a new language

Open an issue in this repository with:
- The language name and code (e.g. `Swedish` / `sv`)
- Whether you are able to contribute translations yourself

We will add the language to Weblate and notify you when it is ready.

## Crediting contributors

Active contributors are listed by username in the [README](./README.md) language table. If you have made significant contributions and would like to be credited, open an issue or leave a comment in Weblate.

## Questions

Open an issue in this repository or reach us at [support@unlusted.com](mailto:support@unlusted.com).
