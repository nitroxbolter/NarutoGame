# Estrutura do Cliente OTCv8

## Objetivo

O cliente deve reforçar a identidade ninja e deixar sistemas complexos fáceis de entender.

## Módulos Sugeridos

```text
client/
  modules/
    game_shinobi_profile/
    game_jutsu_book/
    game_mission_board/
    game_professions/
    game_elements/
    game_rank_progress/
    game_events_calendar/
    game_boss_tracker/
  assets/
    icons/
    ui/
    effects/
```

## Interfaces Importantes

| Interface | Função |
| --- | --- |
| Perfil Shinobi | Rank, atributos, elemento, reputação |
| Livro de Jutsus | Técnicas aprendidas e requisitos |
| Quadro de Missões | Missões disponíveis e progresso |
| Profissões | XP, ferramentas, receitas e coleta |
| Elementos | Afinidades, evolução e resistências |
| Promoção | Requisitos para próximo rank |
| Calendário | Eventos e estações |
| Boss Tracker | Bosses disponíveis, respawn e recompensas |

## Experiência do Jogador

Prioridades:

- Clareza de requisitos.
- Visual ninja sem poluir a tela.
- Feedback forte ao aprender jutsu.
- Indicação de missões próximas.
- Ícones por elemento e raridade.
- Barras simples para progresso de profissão.

## Checklist

- [ ] Definir identidade visual do cliente.
- [ ] Criar ícones de elementos.
- [ ] Criar tela de jutsus.
- [ ] Criar tela de missões.
- [ ] Criar tela de profissões.
- [ ] Criar tela de rank.

