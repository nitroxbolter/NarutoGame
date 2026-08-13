# Visão Geral

## Papel da documentação

Este documento serve como visão-mãe do projeto. Ele define a essência do servidor, o escopo do MVP, a lógica de progressão e a direção de design que todas as outras páginas precisam respeitar.

O objetivo da documentação não é ser só explicativa. Ela precisa funcionar como um guia de desenvolvimento, com regras, tabelas, fluxos, dependências, checklists e decisões pendentes.

## Proposta

O servidor propõe uma jornada ninja autoral dentro do universo de Naruto, **sem limites de nível para o personagem, skills ou domínio dos jutsus**. O jogador cria sua própria identidade shinobi e evolui gradualmente, focando na maestria individual de suas técnicas prediletas.

## Diferencial

Em vez de vender a fantasia de “ser Naruto” ou “ser Sasuke”, o projeto vende a fantasia de “ser um ninja original dentro de uma aldeia viva”.

Isso permite:

- **Identidade Única de Build:** Os jutsus ganham nível com base no uso repetido (quanto mais usa, mais forte fica), permitindo que um jogador de nível baixo tenha uma técnica muito mais poderosa que um de nível alto por pura dedicação.
- **Limitação Estratégica:** Spellbar limitada a no máximo **8 jutsus habilitados**, incentivando a especialização em vez de ter um arsenal genérico infinito.
- **Hokage Competitivo:** O título de Hokage pertence ao jogador com maior nível do servidor, disputado dinamicamente pelos top 3 personagens de maior nível, exigindo derrotar um boss a cada 5 dias e sendo perdido imediatamente na morte.
- **Risco Real (Morte e Debuffs):** A morte causa perda de EXP/skills e drop automático da mochila, acumulando "Feridas" (debuff progressivo de atributos e regeneração que deve ser tratado).
- **Sistema de Injusts e PK:** Sistema clássico de Skulls (White, Red a partir de 10 kills, Black a partir de 50) com perda de kills por morte ou quests, sofrendo restrições de tráfego e quests em áreas específicas.
- **Economia e Clãs ativos:** Distribuição de loot de bosses por dano causado e clãs com benefícios de XP e double loot em eventos.

## Fantasia principal

O jogador deve sentir que:

- Entrou na academia.
- Aprendeu técnicas básicas como Bunshin no Jutsu, Henge e Kawarimi.
- Fez missões pequenas de escolta, captura, patrulha e coleta.
- Ganhou reputação.
- Subiu de rank.
- Treinou corpo e mente.
- Dominou elementos como Katon, Suiton, Raiton, Doton e Fuuton.
- Enfrentou ameaças maiores, como ninjas renegados, bosses de vila e criaturas lendárias.
- Virou alguém respeitado por mérito, como acontece com shinobi que conquistam liderança, reconhecimento ou cargo especial.

## Pilares do projeto

- Identidade própria antes de personagem pronto.
- Progressão antes de fanservice.
- Jutsus como conquista, não como presente automático, com mestre, pergaminho e requisito de rank.
- Economia útil em todas as fases.
- Profissões integradas à vila e ao crafting.
- Bosses e dungeons como objetivos de grupo, inspirados em missões de escolta, resgate, invasão e contenção.
- Eventos e estações para manter o mundo vivo.
- Expansão gradual por aldeias, regiões e sistemas.

## Escopo inicial recomendado

| Área | MVP |
| --- | --- |
| Aldeia | Konoha |
| Ranks | Academia até Chunin ou Jounin inicial |
| Elementos | 5 básicos |
| Atributos | Level, treino, mentalidade e chakra |
| Profissões | Pesca, lenha, plantas, mineração e coleta de materiais shinobi |
| Missões | Academia, D, C e B |
| Conteúdo de grupo | 2 a 4 dungeons iniciais |
| Bosses | Bosses locais, invocações corrompidas e 1 boss de evento |
| Cliente | UI básica para missão, atributos, jutsus e profissões |

## O que fica fora do MVP

- Kekkei genkai profundo e combinações elementais complexas.
- Guerra entre vilas.
- Sistema avançado de títulos políticos (além do Hokage dinâmico).
- Economia avançada entre jogadores.
- Mais de uma aldeia jogável no lançamento.
- Bosses lendários de escala final (Otsutsuki).

## Estrutura da documentação

A documentação principal foi reorganizada para refletir os temas da pasta e o fluxo do projeto:

- Conceito e visão geral.
- Mundo e história.
- Criação de personagem e sistema de chakra.
- Progressão e combate.
- Economia, equipamentos e PvP.
- Planejamento, roadmap e princípios de projeto.

## Próximos arquivos centrais

| Arquivo | Objetivo |
| --- | --- |
| [CHECKLIST_DESENVOLVIMENTO.md](CHECKLIST_DESENVOLVIMENTO.md) | Ordem de execução prática |
| [DECISOES_PENDENTES.md](DECISOES_PENDENTES.md) | Decisões que ainda não foram fechadas |
| [README.md](README.md) | Índice principal da wiki |

## Referência de anime

A base conceitual segue elementos clássicos de Naruto:

- Konoha como aldeia inicial.
- Academia Ninja como tutorial.
- Exame Chunin como marco de progressão.
- ANBU, Sannin e Hokage como cargos especiais.
- Clãs, elementos, invocações e selamentos como parte da fantasia shinobi.
- Akatsuki, ninjas renegados e bijuus como conteúdo de médio e alto nível.
