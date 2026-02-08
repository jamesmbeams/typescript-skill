# typescript-skill

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that encodes Matt Pocock's TypeScript best practices for AI-assisted code generation.

Compiled from Matt Pocock's publicly available teachings at [Total TypeScript](https://www.totaltypescript.com). Not affiliated with or endorsed by Matt Pocock or Total TypeScript.

## What's covered

- `type` vs `interface`
- Enums → const objects & union types
- `satisfies` and `as const satisfies`
- TSConfig best practices (`@total-typescript/tsconfig`)
- Return type annotations
- Generics, `NoInfer<T>`, and `infer`
- Discriminated unions
- Branded / nominal types
- Template literal types
- Utility types
- Method signature style
- Module augmentation
- Type predicates & assertion functions
- Common anti-patterns
- Runtime validation with Zod

## Install

```bash
mkdir -p ~/.claude/skills/typescript-skill
curl -o ~/.claude/skills/typescript-skill/SKILL.md \
  https://raw.githubusercontent.com/jamesmbeams/typescript-skill/main/SKILL.md
```

## Usage

Once installed, Claude Code picks it up automatically when writing or reviewing TypeScript. You can also invoke it manually:

```
/typescript-skill
```
