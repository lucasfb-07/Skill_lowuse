# lowuse

Skill do Claude Code para respostas enxutas: curtas e diretas, sem perder fatos técnicos. Ligue com `/lowuse` e desligue dizendo "modo normal".

É só um arquivo de texto (`SKILL.md`). Não tem hooks, scripts nem permissões de ferramenta.

## Instalar numa máquina

Windows (PowerShell):

```powershell
git clone https://github.com/lucasfb-07/Skill_lowuse.git "$env:USERPROFILE\.claude\skills\lowuse"
```

Linux, macOS ou WSL:

```bash
git clone https://github.com/lucasfb-07/Skill_lowuse.git ~/.claude/skills/lowuse
```

Reinicie as sessões do Claude Code que estavam abertas.

## Atualizar

Windows:

```powershell
git -C "$env:USERPROFILE\.claude\skills\lowuse" pull
```

Linux, macOS ou WSL:

```bash
git -C ~/.claude/skills/lowuse pull
```

## Remover

Apague a pasta `~/.claude/skills/lowuse`.
