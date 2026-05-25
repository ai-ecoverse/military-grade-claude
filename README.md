# Military-Grade Claude  Honorably Discharged

[![87% Vibe_Coded](https://img.shields.io/badge/87%25-Vibe_Coded-ff69b4?style=for-the-badge&logo=githubcopilot&logoColor=white)](https://github.com/ai-ecoverse/vibe-coded-badge-action)

> **This project has been archived.**

Military-Grade Claude served with distinction as a satirical patch that replaced Claude Code's spinner verbs with absurdly over-the-top military-themed status messages. It was always meant as a joke about meaningless "military-grade" marketing language  but not everyone shares the same sense of humor, and that's fine.

After careful consideration, we've decided to give this repo an honorary discharge. The 1,060 tactical verbs can rest easy knowing they served their purpose: making people laugh (mostly).

Thanks to everyone who contributed, installed it, or just got a chuckle out of "Exterminatus-Grade-Purification-Commencing" showing up in their terminal.

## Uninstall

If you previously installed this, remove the spinner verbs from your Claude settings:

```bash
# Remove the patched settings (or just the spinnerVerbs key)
rm ~/.claude/settings.local.json
```

Or if you have other settings in that file, use `jq` to strip just the verbs:

```bash
jq 'del(.spinnerVerbs)' ~/.claude/settings.local.json > tmp.json && mv tmp.json ~/.claude/settings.local.json
```

## License

Apache 2.0

---

*At ease, soldier. Dismissed.*
