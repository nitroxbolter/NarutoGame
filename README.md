# Projeto Naruto Shinobi RPG

Documentação inicial de um servidor MMORPG inspirado no universo Naruto, pensado para TFS 1.4.2 + OTCv8.

O objetivo do projeto é criar uma experiência em que o jogador não controla personagens prontos do anime. Ele cria seu próprio ninja, escolhe caminhos de evolução, aprende jutsus, sobe de rank, participa da economia da aldeia e constrói sua identidade dentro do mundo shinobi.

> Status: ideia inicial organizada para evolução pública no GitHub.

## Menu Principal

### Conceito

- [Visão geral do projeto](docs/00-visao-geral.md)
- [Documento original da ideia](estrutura-ideia-servidor-naruto.md)
- [Índice completo da documentação](docs/README.md)

### Sistemas de Jogo

- [Progressão, classes e promoções](docs/sistemas/progressao-ranks-classes.md)
- [Atributos e builds](docs/sistemas/atributos-builds.md)
- [Elementos, jutsus e invocações](docs/sistemas/elementos-jutsus-invocacoes.md)
- [Itens, equipamentos e raridade](docs/sistemas/itens-raridade-equipamentos.md)
- [Economia](docs/sistemas/economia.md)
- [Crafting, profissões e coleta](docs/sistemas/crafting-profissoes-coleta.md)
- [Missões](docs/sistemas/missoes.md)
- [Dungeons e bosses](docs/sistemas/dungeons-bosses.md)
- [Eventos e estações do ano](docs/sistemas/eventos-estacoes.md)
- [Casas e habitação](docs/sistemas/habitacao-casas.md)

### Mundo

- [Aldeias, NPCs e missões da aldeia](docs/mundo/aldeias-npcs-missoes-da-aldeia.md)
- [Mapa, regiões e exploração](docs/mundo/mapa-regioes.md)

### Técnico

- [Estrutura do servidor TFS](docs/tecnico/estrutura-servidor-tfs.md)
- [Estrutura do cliente OTCv8](docs/tecnico/estrutura-cliente-otcv8.md)

### Planejamento

- [Roadmap](docs/planejamento/roadmap.md)
- [Backlog de ideias](docs/planejamento/backlog-ideias.md)

## Pilares do Projeto

| Pilar | Descrição |
| --- | --- |
| Identidade própria | O jogador cria um ninja original, não joga como Naruto, Sasuke ou outro personagem pronto. |
| Carreira shinobi | A progressão passa por academia, Genin, Chunin, Jonin e conteúdos avançados. |
| Jutsus como conquista | Técnicas são aprendidas por treino, missões, mestres, pergaminhos e requisitos. |
| Build autoral | Elementos, atributos, equipamentos, profissões e invocações moldam o personagem. |
| Mundo vivo | Aldeias, NPCs, economia, eventos, bosses e missões sustentam a experiência. |

## Loop Principal do Jogador

1. Criar um ninja original.
2. Escolher ou descobrir afinidade elemental.
3. Treinar atributos e aprender jutsus.
4. Fazer missões da aldeia.
5. Coletar recursos, craftar e movimentar a economia.
6. Subir de rank ninja.
7. Explorar áreas perigosas, dungeons e bosses.
8. Desbloquear invocações, elementos avançados e conteúdo de alto nível.

## MVP Sugerido

- 1 aldeia principal: Konoha.
- Progressão até Chunin ou Jonin inicial.
- 5 elementos base: Katon, Suiton, Raiton, Doton e Fuuton.
- Sistema inicial de level, treino e mentalidade.
- Missões de academia, rank D, C e B.
- Economia simples com dinheiro, loot, lojas e crafting básico.
- Profissões iniciais: pesca, lenhador, herbalismo e mineração.
- Primeiras dungeons e bosses locais.
- Eventos simples semanais ou sazonais.

## Como Contribuir com a Ideia

Use esta estrutura como um caderno vivo:

- Abra issues para sugerir novos sistemas.
- Edite os arquivos dentro de `docs/` para detalhar ideias.
- Use checklists do roadmap para acompanhar evolução.
- Separe decisões técnicas de ideias de gameplay.
- Registre dúvidas no backlog antes de transformar em sistema fechado.

## Observação Legal

Este é um projeto de estudo, organização e design inspirado por temas de anime ninja. Antes de publicar ou monetizar qualquer servidor, avalie nomes, assets, marcas, personagens e direitos autorais envolvidos.

