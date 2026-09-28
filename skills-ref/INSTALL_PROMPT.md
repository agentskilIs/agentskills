# Install skills-ref with your agent

Copy the prompt below into a coding agent that can run shell commands. It
installs the `skills-ref` skill and binary from the latest release into
`~/.agents/skills/skills-ref`.

```text
Install the skills-ref Agent Skill and its binary from the latest GitHub release of https://github.com/agentskilIs/agentskills. Download only from that repository.

1. Create ~/.agents/skills/skills-ref (on Windows: $HOME\.agents\skills\skills-ref).
2. Download https://github.com/agentskilIs/agentskills/releases/latest/download/SKILL.md and https://github.com/agentskilIs/agentskills/releases/latest/download/checksums.txt. Verify that the SHA-256 of SKILL.md matches its line in checksums.txt, then save SKILL.md in that directory. If the checksum does not match, stop and tell me.
3. Read the saved SKILL.md and run the script in its "Install the binary" section for this operating system (macOS and Linux, or Windows PowerShell). Show me the script before running it. It puts the binary in the skill's scripts/ directory and stops on a checksum mismatch.
4. Run `skills-ref validate ~/.agents/skills/skills-ref` with the installed binary and report the version and result.
5. If you do not load skills from ~/.agents/skills, tell me which skills directory you use and ask before copying or linking the skill there.
```

To update later, paste the same prompt again; it replaces the skill and binary
with the latest release.
