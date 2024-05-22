# Fractor Rule Doc Generator

Generate Documentation for you Fractor rules

## Installation

```bash
composer require a9f/fractor-doc-generator --dev
```

## Usage

To generate documentation from rules, use `generate` command with paths that contain the rules:

```bash
vendor/bin/fractor-doc-generator generate src/rules
```

The file will be generated to `/docs/rules_overview.md` by default. To change that, use `--output-file`:

```bash
vendor/bin/fractor-doc-generator generate src/rules --output-file docs/my_rules.md
```

Happy coding!