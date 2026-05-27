# BitSota Agent Skills

Portable agent skills for BitSota / SN94 work.

## Skills

### `sn94-competition-poster`

Use this skill to create or review SN94 autoresearch competition proposals and replayable task repositories. It is problem-agnostic and fits the existing autoresearch backend replay format.

Path:

```text
skills/sn94-competition-poster/SKILL.md
```

## Install From GitHub

AgentSkills-style CLIs can install directly from this repo:

```bash
skills install AlveusLabs/bitsota-agent-skills \
  --skill sn94-competition-poster
```

If your agent expects a local skills directory, copy `skills/sn94-competition-poster` into that directory.

## Submit A Competition Proposal

Submit the finished output as a GitHub issue in:

```text
https://github.com/AlveusLabs/SN94-BitSota/issues/new?template=competition_proposal.md
```

Issue title:

```text
[Competition Proposal] <problem name>
```

Include the filled proposal template and a link to the public task repo.

## Publish Notes

Do not add secrets, mnemonics, wallet files, API tokens, production env files, or private validation datasets to this repository.
