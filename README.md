# Harsh Style Email

An agent skill for drafting, replying to, and revising emails in Harsh Agrawal's writing style. It uses a courteous opening, states the purpose early, and makes the next step clear. Drafts use the sender's own name and the facts they provide. The skill contains writing guidance and synthetic examples and works without a mailbox connection.

## Install in Codex

This command installs the skill for your Codex user account. It requires a version of the GitHub CLI that supports `gh skill install`.

```sh
gh skill install hsa70-ui/harsh-style-email harsh-style-email --agent codex --scope user
```

You can also [download the repository ZIP](https://github.com/hsa70-ui/harsh-style-email/archive/refs/heads/main.zip). Extract it and copy the `skills/harsh-style-email` folder to `~/.agents/skills/`. The installed file should be `~/.agents/skills/harsh-style-email/SKILL.md`. Restart Codex if the skill does not appear.

## Use it

In Codex, invoke `$harsh-style-email` or ask in plain language.

> Use Harsh Style Email to draft a polite follow-up asking when the revised agenda will be ready.

For another assistant that supports Agent Skills, install the [skill folder](skills/harsh-style-email) in the location that assistant uses for skills.
