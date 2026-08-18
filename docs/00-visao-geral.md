# Visão Geral

## Papel da documentação

Este documento é a visão-mãe do NarutoGame. Ele define a essência do projeto, a filosofia de progressão e as decisões centrais que os demais documentos precisam respeitar.

A documentação do projeto não serve só para explicar o jogo. Ela também precisa orientar o desenvolvimento de sistemas, balanceamento, arquitetura e prioridades futuras.

## Proposta central

NarutoGame será um MMORPG inspirado no universo de Naruto e na lógica de progressão clássica de jogos como Tibia, mas com um personagem próprio, construção de identidade e especialização real.

O jogador não assume o papel de Naruto, Sasuke ou outro protagonista. Ele cria o próprio shinobi e constrói sua trajetória no mundo.

O objetivo de longo prazo é tornar o personagem cada vez mais forte, podendo alcançar posições de prestígio como líder de clã, Hokage ou títulos lendários.

## Filosofia do projeto

**Todo jogador pode chegar muito longe, mas ninguém domina tudo rapidamente.**

O poder do personagem deve representar:

- tempo investido;
- especialização;
- escolhas;
- treinamento;
- equipamentos;
- conhecimento do jogo;
- cooperação com outros jogadores.

A especialização recompensa poder. A versatilidade recompensa opções.

## Loop principal de gameplay

O ciclo principal do jogo deve seguir esta lógica:

1. Entrar no jogo e escolher objetivos.
2. Pegar tasks ou missões compatíveis com o rank.
3. Explorar uma região, hunt ou dungeon.
4. Matar criaturas e ganhar experiência.
5. Evoluir skills durante o combate.
6. Evoluir individualmente os jutsus usados.
7. Obter materiais, equipamentos e recursos.
8. Encontrar bosses locais ou chefes maiores.
9. Conseguir pergaminhos e materiais especiais.
10. Desbloquear novos jutsus e conteúdos.
11. Criar ou melhorar equipamentos.
12. Aumentar o rank do personagem.
13. Preparar-se para áreas e inimigos mais fortes.

O ciclo então se repete em conteúdos progressivamente mais difíceis.

## Progressão do personagem

A experiência vem principalmente de:

- criaturas;
- tasks;
- missões.

Uma task pode gerar progressão dupla: o jogador ganha a experiência das criaturas que derrota e recebe uma recompensa adicional ao concluir a task.

Além do level geral, o jogo terá progressões paralelas independentes:

- skills;
- nível dos jutsus;
- elementos;
- equipamentos;
- rank de missões;
- títulos;
- reputação;
- crafting e upgrades.

## Classes e afinidade inicial

Na criação do personagem, o jogador escolhe sua classe ou afinidade inicial.

As classes iniciais previstas são:

- Fogo;
- Água;
- Vento;
- Terra;
- Raio;
- Taijutsu.

A classe inicial define a aptidão natural do personagem e influencia principalmente:

- velocidade de evolução das skills;
- quantidade e progressão de vida;
- quantidade e progressão de chakra;
- caminho inicial de técnicas.

## Classes elementais

Personagens elementais têm maior aptidão para Ninjutsu.

Características gerais:

- Ninjutsu evolui mais rapidamente;
- há maior disponibilidade e progressão de chakra;
- existe acesso à árvore elemental correspondente;
- Taijutsu evolui mais lentamente do que em um especialista de Taijutsu;
- há menor foco natural em vida e resistência física do que na classe Taijutsu.

## Classe Taijutsu

Taijutsu é um caminho de combate próprio, não um elemento.

Características:

- evolução acelerada da skill Taijutsu;
- maior vida;
- maior resistência;
- menor quantidade e progressão de chakra;
- evolução de Ninjutsu inferior à das classes elementais;
- foco em ataques físicos;
- árvore própria de técnicas;
- não usa elementos como caminho principal.

Outros personagens ainda podem lutar fisicamente e usar armas. A diferença é que o especialista em Taijutsu possui aptidão e progressão muito superiores nesse caminho.

## Skills

As skills representam prática e treinamento.

Elas evoluem pelo uso, mantendo uma filosofia parecida com Tibia/TFS, mas adaptada ao universo Naruto.

### Taijutsu / Fist Fighting

Representa combate corporal:

- socos;
- chutes;
- ataques físicos sem arma;
- técnicas corporais.

### Ninjutsu / Magic Level

O Magic Level do TFS é reinterpretado como Ninjutsu.

Representa domínio e treinamento de técnicas ninja.

### Sword Fighting

Representa domínio de:

- espadas;
- katanas;
- armas compatíveis.

### Club Fighting

Representa domínio de:

- bastões;
- clavas;
- armas contundentes;
- outras armas compatíveis.

### Axe Fighting

Representa domínio de:

- machados;
- armas classificadas nessa categoria.

### Bukijutsu / Distance Fighting

Distance Fighting é reinterpretado como Bukijutsu.

Exemplos:

- kunai;
- shuriken;
- senbon;
- outras armas de distância ou arremesso.

### Princípio

**Skill é prática. Atributo é potencial.**

As skills sobem pelo uso. Os atributos vêm das escolhas de progressão do jogador.

## Atributos

Além das skills tradicionais do TFS, o jogo terá atributos distribuíveis pelo jogador.

A proposta inicial é conceder aproximadamente 5 pontos de atributo por level, valor ainda sujeito a balanceamento.

Os atributos-base considerados são:

- Força;
- Vitalidade;
- Controle de Chakra;
- Inteligência;
- Agilidade.

Cada atributo terá impacto específico nas fórmulas do jogo, ainda a serem refinadas em documento próprio.

## Vida e chakra

Vida é o principal recurso de sobrevivência.

A classe escolhida interfere em sua progressão, e a classe Taijutsu deve ter vantagem natural de vida em comparação com as classes elementais.

Chakra substitui conceitualmente a mana tradicional e é usado principalmente para executar jutsus.

Classes elementais têm maior progressão de chakra, enquanto especialistas em Taijutsu recebem menos chakra e compensam com vida, resistência e poder físico.

### Regeneração

A regeneração será importante no gerenciamento de recursos e poderá ser aumentada por:

- descanso fora de combate;
- comidas;
- pílulas;
- efeitos específicos.

Consumíveis podem combinar efeitos imediatos e regeneração gradual.

## Modos de batalha

O custo e a potência das técnicas podem ser influenciados pelo modo de batalha.

Os três modos previstos são:

- Offensive;
- Balanced / Medium;
- Defensive.

## Sistema elemental

O primeiro elemento é escolhido durante a criação do personagem.

Os elementos formam uma roda de progressão, permitindo avanço para elementos adjacentes conforme requisitos sejam cumpridos.

Novos elementos podem exigir:

- level;
- domínio do elemento atual;
- nível de jutsus específicos;
- missões;
- títulos;
- conquistas.

## Jutsus e árvores

Cada jutsu possui progressão individual e evolui pelo uso.

Quanto mais o jogador usa uma técnica, maior será o domínio específico daquela técnica.

O nível do jutsu pode aumentar:

- dano;
- alcance, quando apropriado;
- eficiência prevista para a técnica.

Cada elemento possui sua própria árvore de habilidades, com requisitos de domínio, missões, bosses, pergaminhos e outros critérios.

## Kekkei Genkai e técnicas multi-elementais

Algumas técnicas avançadas podem exigir combinação de elementos.

Esses caminhos representam técnicas especiais e Kekkei Genkai.

A filosofia geral é permitir que qualquer personagem alcance esses conteúdos em teoria, desde que cumpra os requisitos e invista o suficiente.

## Jutsus equipados

O jogador não carrega toda a coleção de técnicas na barra ativa ao mesmo tempo.

A proposta atual é permitir aproximadamente 8 jutsus equipados.

Isso força escolhas entre:

- especialização;
- versatilidade;
- preparação para hunts;
- preparação para PvP;
- preparação para bosses.

## Equipamentos, crafting e upgrades

Equipamentos terão raridades e atributos variáveis.

Isso significa que dois itens do mesmo tipo e raridade não precisam ser idênticos.

Crafting e upgrade/tier devem funcionar como pilares da progressão de equipamentos e como mecanismos de retirada de recursos da economia.

## Conteúdo do mundo

As regiões devem ter identidade própria.

Os inimigos encontrados precisam fazer sentido com o ambiente, e os bosses locais funcionam como marcos de progressão da região.

Tasks, missões, dungeons e bosses devem se conectar com a fantasia de exploração e crescimento gradual.

## Tasks, missões e rank

Tasks e missões são pilares da progressão.

O jogador ganha experiência durante a execução e pode receber recompensas adicionais ao concluir o objetivo.

As missões usarão ranks inspirados no universo Naruto, como:

- Rank C;
- Rank B;
- Rank A;
- Rank S.

Completar missões aumenta o rank e libera conteúdos mais difíceis.

## PvP e reputação

Dentro das cidades existirão áreas Non-PvP. Fora delas, o mundo pode adotar zonas de conflito abertas.

O PvP não deve depender apenas do sistema clássico de frags como punição direta. Matar jogadores afeta reputação ou criminalidade.

Jogadores com reputação negativa podem sofrer restrições de acesso, benefícios e proteção.

## Morte

Ao morrer, a proposta atual é:

- não perder equipamentos vestidos;
- perder a mochila;
- perder uma quantidade de experiência;
- perder uma quantidade de skill.

Um sistema de bênçãos pode reduzir certas penalidades.

## Clãs

Clãs funcionam inicialmente de forma parecida com guilds.

A primeira versão não deve amarrar jutsus exclusivos ou vantagens obrigatórias de combate ao clã.

## Endgame

O endgame deve ser difícil, cooperativo e parcialmente inalcançável no curto prazo.

Mesmo personagens extremamente fortes precisarão de outros jogadores para enfrentar certos desafios.

O objetivo é sempre existir um próximo nível de conquista.

## Títulos e prestígio

O jogador pode perseguir posições e títulos importantes, como:

- líder de clã;
- Hokage;
- títulos lendários;
- conquistas ligadas à progressão e feitos especiais.

## Decisões já estabelecidas

Este documento trata como princípios atuais do projeto:

- personagem próprio em vez de protagonista do anime;
- progressão longa;
- experiência através de criaturas, tasks e missões;
- jutsus com evolução individual pelo uso;
- árvores de jutsus;
- elementos desbloqueáveis progressivamente;
- técnicas multi-elementais;
- especialização versus versatilidade;
- aproximadamente 8 jutsus ativos;
- chakra como recurso central;
- Taijutsu como caminho próprio;
- skills do TFS reinterpretadas para o universo Naruto;
- atributos separados das skills;
- equipamentos com raridade e atributos variáveis;
- crafting;
- sistema de tiers e upgrades;
- chefes locais;
- bosses de grupo;
- PvP aberto fora de zonas protegidas;
- reputação e criminalidade no PvP;
- clãs inicialmente sociais;
- endgame cooperativo extremamente difícil.

## Pontos que ainda exigem documento de detalhamento

Ainda devem existir documentos específicos para:

- fórmulas de atributos;
- fórmulas de dano;
- velocidade de treino das skills por classe;
- ganho de HP e chakra por classe;
- regeneração;
- custo de jutsus;
- progressão de níveis de jutsu;
- roda elemental definitiva;
- árvores completas de jutsus;
- árvore de Taijutsu;
- equipamentos e tabela de raridades;
- geração de atributos dos equipamentos;
- crafting;
- tiers e upgrades;
- economia;
- ranks e missões;
- dungeons;
- bosses;
- PvP e reputação;
- sistema de morte e bênçãos;
- títulos;
- progressão de endgame;
- balanceamento geral.

Esses documentos detalham a visão; não precisam redefinir a essência do jogo.

## Norte de design

Quando surgir uma dúvida durante o desenvolvimento, as decisões devem respeitar estes princípios:

1. Progressão deve ser conquistada.
2. Especialização deve ser recompensada.
3. Versatilidade deve ser possível, mas custosa.
4. O jogador deve construir seu próprio shinobi.
5. Skills representam prática.
6. Atributos representam potencial e construção de personagem.
7. Equipamentos devem continuar interessantes mesmo no late game.
8. Conteúdo de alto nível deve incentivar cooperação.
9. PvP deve possuir liberdade e consequências.
10. Sempre deve existir algo difícil para alcançar.

## Resumo em uma frase

**NarutoGame é um MMORPG de progressão contínua em que o jogador constrói seu próprio shinobi através de treinamento, escolhas, jutsus, elementos, equipamentos, exploração, PvP e cooperação, podendo teoricamente alcançar qualquer poder, desde que esteja disposto a pagar o preço em dedicação e especialização.**
