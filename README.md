# ZenSpinner

A collection of ~90 zen, stoic, and timeless quotes to replace Claude Code's default spinner verbs — so every "thinking" moment becomes a small invitation to slow down.

> *"Nature does not hurry, yet everything is accomplished."*

## Install via Claude Code

Paste this into Claude Code:

```
Add the spinnerVerbs config from https://github.com/basic-engineering/ZenSpinner/blob/main/zenspinner.json to my Claude Code settings.json (merge it in — don't overwrite anything else).
```

Claude Code will fetch the file, merge the `spinnerVerbs` block into your `~/.claude/settings.json`, and the next time you see a spinner it'll quote Marcus Aurelius instead of saying "Synthesizing."

## Install manually

Open `~/.claude/settings.json` and add the `spinnerVerbs` key from [`zenspinner.json`](zenspinner.json). Example:

```json
{
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": [
      "Nature does not hurry, yet everything is accomplished",
      "What you seek is seeking you",
      "No mud, no lotus"
    ]
  }
}
```

- `mode: "replace"` — swap out the defaults entirely
- `mode: "append"` — keep the defaults and add these too

Restart Claude Code and enjoy the calm.
