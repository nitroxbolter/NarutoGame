# Estrutura do Servidor TFS

## Base Técnica

Base sugerida:

- TFS 1.4.2.
- Scripts Lua.
- Banco de dados MySQL/MariaDB.
- Cliente OTCv8.

## Organização Recomendada

Exemplo de estrutura futura do servidor:

```text
server/
  data/
    actions/
    creaturescripts/
    globalevents/
    movements/
    npc/
    spells/
    talkactions/
    weapons/
  mods/
  schemas/
  tools/
```

## Sistemas no Servidor

| Sistema | Responsabilidade |
| --- | --- |
| Ranks | Promoções, requisitos e permissões |
| Jutsus | Spells, cooldowns, custos e requisitos |
| Elementos | Afinidades, bônus e resistências |
| Missões | Storage, progresso e recompensas |
| Profissões | Coleta, XP, ferramentas e crafting |
| Economia | Moedas, lojas, mercado e sinks |
| Bosses | Respawn, instâncias, loot e eventos |
| Casas | Permissões, aluguel e armazenamento |
| Eventos | Calendário, invasões e sazonalidade |

## Storages

Criar uma tabela ou convenção para storages:

```text
10000-10999: Tutorial e academia
11000-11999: Ranks e promoções
12000-12999: Elementos
13000-13999: Jutsus
14000-14999: Missões da aldeia
15000-15999: Profissões
16000-16999: Dungeons e bosses
17000-17999: Eventos
```

## Boas Práticas

- Separar scripts por sistema.
- Usar constantes para ids importantes.
- Documentar storages.
- Evitar lógica duplicada em NPCs.
- Criar funções utilitárias para requisitos.
- Testar promoções e missões com personagens novos.

## Checklist Técnico

- [ ] Definir versão exata do TFS.
- [ ] Definir estrutura de pastas real do projeto.
- [ ] Criar padrão de storages.
- [ ] Criar padrão de configuração para jutsus.
- [ ] Criar padrão de missão.
- [ ] Criar padrão de profissão.

