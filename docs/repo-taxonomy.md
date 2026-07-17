# Repository Taxonomy

## Topic convention

Every repository should have:

- exactly one lane topic: `lane-trading`, `lane-cyber`, or `lane-infra`
- one status topic: `status-core`, `status-active`, `status-archive`, `status-hibernate`, `status-utility`, or `status-deprecated`
- theme topics that describe the repo role

## Canonical classification

| repo | lane | status | themes |
|---|---|---|---|
| project-umbrela | trading | core | market-ai, paper-trading, operator-cockpit |
| worm-trading-agent | trading | active | market-ai, paper-trading, execution-backend, observability |
| worm-magotshtora | trading | archive | market-ai, regime-overseer, research-archive |
| worm-sa21magot | trading | archive | prediction-market, negative-edge, research-archive |
| worm-grasiax | cyber | core | pentest, offensive-security, operator-toolkit |
| worm-venice-agent | cyber | hibernate | purple-team, operator-agent, security-research |
| red-notes | cyber | active | offensive-security, cheatsheets, pentest |
| worm-magotarena | cyber | deprecated | pentest, distro-scaffold, deprecated |
| worm-search | infra | core | operator-control-plane, newtab, launcher |
| worm-mistral-cli | infra | utility | llm-cli, utility |
| worm-tiktok-bot | infra | utility | content-bot, telegram-bot |
| dotfiles | infra | active | dotfiles, environment-config, offensive-security |
| worm-homedir-vault | infra | utility | encrypted-backup, vault |
| 0xvoidworm.github.io | infra | active | github-pages, writeups |
| 0xvoidworm | infra | core | profile-readme, repo-index |
