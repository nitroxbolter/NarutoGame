# Estrutura da Ideia — Servidor Naruto no TFS 1.4.2 + OTCv8

> Documento original de referência do projeto. A visão-mãe atual e mais completa fica em [docs/00-visao-geral.md](docs/00-visao-geral.md).

## Visão do Projeto

A proposta do servidor é se diferenciar dos servidores tradicionais de Naruto, nos quais o jogador escolhe ou controla diretamente personagens famosos do anime, como Naruto, Sasuke, Kakashi ou Itachi.

Neste projeto, o jogador cria a própria identidade dentro do universo ninja. Em vez de “ser” um personagem da obra, ele será um ninja original, com evolução própria, escolhas de estilo de combate, progressão de rank, especialização elemental e construção individual de poder.

O foco do jogo é oferecer uma experiência de progressão mais autoral, com sensação de carreira ninja, aprendizado técnico, crescimento gradual e liberdade para montar builds diferentes. O universo do anime serve como base temática, visual e narrativa, mas a jornada do jogador é própria.

## Pilar Central da Proposta

O conceito principal do servidor é:

- O jogador não joga como um personagem do anime.
- O jogador cria sua própria identidade ninja.
- A progressão acontece como em uma carreira dentro do mundo shinobi.
- Técnicas icônicas do anime existem no jogo, mas são aprendidas como jutsus e não recebidas por “ser” determinado personagem.

Isso muda completamente a fantasia principal do jogo:

- Em servidores comuns: “eu sou o Naruto”.
- Neste servidor: “eu sou um ninja do meu clã, com meus elementos, meu treinamento e minhas técnicas”.

Esse diferencial dá mais longevidade ao servidor, mais variedade de builds e mais espaço para sistemas de progressão, economia e conteúdo de médio e longo prazo.

## Fantasia do Jogador

A fantasia principal do jogador deve ser a de viver a trajetória de um ninja dentro do mundo de Naruto.

Ele começa como alguém comum dentro da aldeia, com pouco poder, poucos recursos e poucas técnicas. Aos poucos, evolui por esforço, treinamento, missões, estudo de jutsus, combate contra ameaças maiores e conquista de reconhecimento. O jogador deve sentir que construiu sua força e não apenas herdou um personagem pronto.

### Sensações que o servidor deve entregar

- Evolução real de iniciante para elite ninja.
- Liberdade para escolher o estilo de combate.
- Descoberta gradual de técnicas mais avançadas.
- Valor no treinamento, e não só no level.
- Recompensa por dedicação, especialização e planejamento.
- Imersão em uma vila ninja viva, com missões, economia e ameaças globais.

## Estrutura de Progressão

### 1. Identidade Própria do Jogador

Ao entrar no jogo, o personagem não é um herói conhecido do anime. Ele é um ninja original. Isso permite criar:

- Nome próprio.
- Aparência própria.
- Caminho de evolução próprio.
- Escolhas de build próprias.
- Especializações próprias.

Esse sistema pode abrir espaço futuramente para:

- Clãs jogáveis.
- Traços iniciais.
- Afinidades naturais.
- Talentos passivos.
- Especializações avançadas.

### 2. Progressão por Rank Ninja

A progressão social e funcional do personagem pode seguir a hierarquia ninja clássica. Exemplo:

- Estudante da Academia.
- Genin.
- Chunin.
- Jonin.
- ANBU (ou especialização avançada).
- Kage / Hokage.

Cada rank pode desbloquear:

- Novas áreas.
- Novos NPCs.
- Novas missões.
- Novos exames.
- Acesso a técnicas mais complexas.
- Equipamentos melhores.
- Responsabilidades e conteúdos mais perigosos.

A promoção de rank não deve depender só de level. O ideal é exigir combinação de fatores:

- Level mínimo.
- Missões concluídas.
- Prova prática.
- Prova teórica ou escolha de respostas.
- Bosses específicos derrotados.
- Reputação com a aldeia.

#### Regras Especiais para o Hokage
O Hokage representa a liderança máxima da aldeia e é um título dinâmico e competitivo:
- **Critério de Elegibilidade:** O cargo será disputado entre os 3 personagens de maior nível do servidor. O jogador com o maior nível ativo assume o título.
- **Manutenção do Título:** A cada 5 dias, o Hokage deve derrotar um boss específico para provar que é digno e manter o seu cargo.
- **Condição de Perda:** Se o Hokage morrer de qualquer forma (para monstros, players ou bosses), ele perde o título automaticamente, permitindo que a liderança alterne entre os 3 personagens mais fortes.

### 3. Level como Base de Poder

O level representa a evolução geral do ninja e é um dos pilares centrais do crescimento. **Não há limite máximo (cap) de nível, de skills ou de nível dos jutsus.**

O level define principalmente:

- Vida máxima.
- Chakra máximo.
- Dano base geral.
- Resistência geral.
- Requisitos para aprender técnicas.
- Acesso a conteúdos mais perigosos.

### Ideia de função do level dentro do servidor

- Level = maturidade geral do personagem.
- Não deve decidir tudo sozinho. Ele atua em conjunto com a maestria dos jutsus e treino físico/mental.
- Dois jogadores do mesmo nível ainda podem ser diferentes entre si.
- Como não há cap, a progressão de longo prazo é infinita.

## Atributos Principais

A base do servidor pode girar em torno de três eixos de evolução: nível, treino e mentalidade.

### 1. Nível

Responsável por:

- Vida.
- Chakra.
- Força geral.
- Sobrevivência.
- Requisitos de progressão.

### 2. Treino

Treino representa o desenvolvimento físico e corporal do ninja.

Impacta principalmente:

- Taijutsu.
- Dano físico básico.
- Ataques corpo a corpo.
- Eficiência com armas ninja físicas.
- Resistência corporal.

Esse atributo reforça a ideia de que o jogador pode construir um ninja mais físico, agressivo e de combate direto.

### 3. Mentalidade

Mentalidade representa o domínio interno de chakra, disciplina, foco e capacidade técnica.

Impacta principalmente:

- Poder de ninjutsu.
- Quantidade adicional de chakra.
- Eficiência no uso de jutsus.
- Escalonamento de dano elemental.
- Controle de técnicas avançadas.

Esse atributo favorece jogadores que querem investir em técnicas, combos, utilidade e poder de chakra.

### 4. Resultado Prático da Combinação

A combinação desses três eixos gera estilos diferentes de personagem:

- Level alto + treino alto = ninja resistente com bom combate físico.
- Level alto + mentalidade alta = ninja forte em jutsus e chakra.
- Treino alto + mentalidade média = híbrido funcional.
- Mentalidade muito alta + elementos raros = foco em ninjutsu avançado.

Isso é importante porque cria diversidade de builds sem depender apenas de vocações fixas.

## Sistema de Elementos

Um dos pilares mais fortes do servidor deve ser a afinidade elemental.

### Conceito Base

O jogador escolhe um elemento principal no início da jornada ou em um momento inicial controlado do progresso. Esse elemento representa sua afinidade base e define o primeiro conjunto de técnicas que ele poderá estudar.

### Elementos iniciais sugeridos

- Katon (fogo).
- Suiton (água).
- Raiton (raio).
- Doton (terra).
- Fuuton (vento).

### Função do Elemento Base

O elemento base define:

- Primeira árvore de jutsus liberada.
- Estilo visual inicial do jogador.
- Primeiros combates especializados.
- Rotas de build no early e mid game.

### Aprendizado de Novos Elementos

O jogador pode aprender todos os 5 elementos ao longo de sua jornada, mas isso exige um progresso gradual e de alta dificuldade:

- **1º Elemento (Inicial):** Escolhido livremente durante a criação do personagem.
- **2º Elemento:** Exige rank intermediário (Chunin), missão elemental e treino básico com mestre.
- **A partir do 3º Elemento:** O aprendizado torna-se extremamente difícil. Exigirá requisitos complexos, incluindo níveis mínimos dos elementos anteriores, realização de missões especiais e requisitos de nível do personagem.

Isso cria senso de conquista e evita que todos tenham todos os elementos muito cedo.

### Possibilidades Futuras

Com evolução do projeto, isso pode se expandir para:

- Kekkei Genkai por combinação de elementos.
- Jutsus únicos de linhagem.
- Especializações secretas.
- Mestres elementais por vila.
- Pergaminhos raros para técnicas especiais.

## Sistema de Jutsus

### Filosofia do Sistema

Os jutsus não devem ser entregues automaticamente apenas porque o jogador subiu de nível. O ideal é que o jogador precise aprender, desbloquear, treinar e dominar técnicas.

Isso aproxima o servidor da fantasia de estudo e evolução ninja.

### Estrutura de Aprendizado

Cada jutsu pode depender de requisitos como:

- Nível mínimo.
- Rank ninja mínimo.
- Elemento necessário.
- Mentalidade mínima.
- Missão específica.
- Mestre NPC.
- Item de aprendizado, como pergaminho.
- Custo em dinheiro ou recursos.

### Tipos de Jutsu

Os jutsus podem ser organizados em categorias:

- Ninjutsu ofensivo.
- Ninjutsu defensivo.
- Jutsus de mobilidade.
- Jutsus utilitários.
- Genjutsu.
- Taijutsu especial.
- Técnicas supremas / ultimates.
- Invocações no futuro.

### Relação com Personagens do Anime

Em vez de o jogador “ser o Sasuke” para usar uma técnica famosa, ele aprende técnicas inspiradas ou diretamente baseadas no repertório de personagens do anime.

Exemplo conceitual:

- Um usuário de katon avançado pode aprender técnicas icônicas de fogo.
- Um usuário de raiton pode acessar técnicas relâmpago inspiradas em personagens famosos.
- Um jogador com progressão especial pode aprender técnicas lendárias, desde que cumpra os requisitos.

Dessa forma, o anime vira fonte de técnicas, não de classes prontas.

### Progressão de Domínio e Nível do Jutsu

Os jutsus possuem seu próprio nível de domínio, sem limite máximo (cap).
- **Evolução por Uso:** O nível de um jutsu aumenta à medida que o jogador o utiliza em combate. Quanto mais usar, maior será o nível daquele jutsu.
- **Progressão Lenta:** A progressão de nível do jutsu é extremamente lenta, exigindo dedicação contínua.
- **Especialização Única:** Um jogador de nível geral mais baixo pode ter um jutsu muito mais forte e evoluído do que um jogador de nível mais alto, se focar e treinar exaustivamente apenas aquela técnica. Os jogadores podem optar por se especializarem em um único jutsu em vez de espalharem seu treino por várias técnicas.
- **Spellbar Limitada:** Para incentivar decisões estratégicas de build, cada jogador poderá ter no máximo **8 jutsus habilitados** simultaneamente na sua barra de magias (spellbar).

O domínio melhorado do jutsu impacta:

- Dano.
- Custo de chakra.
- Tempo de recarga.
- Alcance.
- Efeitos secundários.

## Estilos de Combate

O servidor pode se apoiar em estilos de combate construídos organicamente a partir dos atributos e técnicas do jogador.

### Arquétipos possíveis

- Ninja físico: foco em treino, taijutsu, armas e pressão curta distância.
- Ninja elemental: foco em mentalidade, chakra e combos de ninjutsu.
- Ninja híbrido: equilíbrio entre dano físico e técnicas.
- Ninja tático: foco em utilidade, controle, debuffs e movimentação.
- Ninja especialista: foco em um elemento com alta eficiência.
- Ninja versátil: múltiplos elementos com poder moderado.

Essa estrutura permite liberdade sem precisar prender o jogo a vocações clássicas demais.

## Mundo e Estrutura das Aldeias

### Aldeia Inicial

A aldeia principal inicial pode ser Konoha, funcionando como centro do early e mid game.

Funções de Konoha no começo do projeto:

- Spawn inicial.
- Área de tutorial.
- NPCs principais.
- Academia ninja.
- Primeiro hospital.
- Loja básica.
- Quadro de missões.
- Mestres de treino.
- Exames de progressão.
- Primeiro núcleo econômico.

### Expansão Futura

Com o desenvolvimento, outras aldeias podem ser abertas como conteúdo adicional:

- Sunagakure.
- Kirigakure.
- Kumogakure.
- Iwagakure.
- Vilas menores e territórios neutros.

Cada aldeia futura pode ter:

- Missões próprias.
- Afinidades elementais favorecidas.
- NPCs exclusivos.
- Jutsus únicos.
- Facções locais.
- Economia regional.
- Eventos e conflitos.

### Estrutura do Mundo

O mapa pode ser dividido por camadas de progressão:

- Zona segura da aldeia.
- Campos de treino.
- Florestas e estradas.
- Áreas de bandidos e ninjas renegados.
- Ruínas e templos.
- Campos de guerra.
- Covis de chefes.
- Regiões das bijuus.
- Dimensões ou áreas especiais de ameaça Otsutsuki.

## Sistema de Missões

As missões devem ser uma das principais formas de dar direção ao jogador e alimentar a economia.

### Funções das Missões

- Gerar dinheiro.
- Dar experiência.
- Liberar progressão de rank.
- Introduzir lore.
- Ensinar sistemas.
- Guiar o jogador pelo mapa.
- Oferecer reputação com a aldeia.

### Categorias de Missões

- Missões da academia.
- Missões de rank D, C, B, A e S.
- Missões de caça.
- Missões de coleta.
- Missões de escolta.
- Missões de patrulha.
- Missões de investigação.
- Missões de história principal.
- Missões de progressão elemental.
- Missões para aprender jutsus.
- Missões diárias e semanais.

### Progressão de Recompensas

As missões podem recompensar com:

- Dinheiro.
- Experiência.
- Itens.
- Pergaminhos.
- Reputação.
- Materiais de crafting.
- Títulos.
- Liberação de conteúdo.

Isso ajuda a manter um loop saudável entre combate, exploração, economia e progressão.

## Economia do Servidor

A economia precisa ser funcional e útil desde o início, para que o dinheiro tenha valor real.

### Fontes de Dinheiro

- Missões.
- Loot de monstros e chefes.
- Venda de itens coletados.
- Recompensas de eventos.
- Contratos especiais.

### Principais Gastos do Jogador

- Aprendizado de jutsus.
- Compra de armas ninja.
- Compra de armaduras e roupas.
- Consumíveis.
- Pergaminhos.
- Materiais especiais.
- Taxas de progressão.
- Viagens futuras entre aldeias.
- Crafting e aprimoramento.

### Objetivo Econômico

A economia deve evitar dois extremos:

- Dinheiro inútil demais.
- Dinheiro escasso demais ao ponto de travar a diversão.

O ideal é que o dinheiro seja sempre relevante para:

- Melhorar build.
- Se preparar para conteúdos fortes.
- Desbloquear técnicas.
- Comprar equipamentos de qualidade.
- Participar de sistemas de crafting e progressão.

### Possibilidades Futuras

- Mercado entre jogadores.
- Leilão.
- Profissões secundárias.
- Crafting de armas e pergaminhos.
- Sistema de coleta de recursos.
- Economia regional por aldeia.

## Clãs no Servidor
Os clãs no jogo funcionarão como o sistema tradicional de guildas (Guilds), servindo como núcleos sociais e de organização de jogadores.
- **Eventos de Clã:** O jogo contará com eventos focados em clãs.
- **Benefícios de Clã:** A participação em eventos de clã garantirá bônus de experiência temporários (XP extra) e double loot para os membros, incentivando a cooperação.

## Itens e Equipamentos

A identidade dos itens deve seguir a fantasia ninja, sem depender de equipamentos genéricos de MMORPG.

### Categorias de Itens

- Kunais.
- Shurikens.
- Senbons.
- Bombas de fumaça.
- Talismãs.
- Pergaminhos.
- Roupas ninja.
- Armaduras leves.
- Coletes de rank.
- Faixas e acessórios.
- Itens de cura.
- Itens de recuperação de chakra.

### Papel dos Equipamentos

Equipamentos podem oferecer:

- Ataque físico.
- Defesa.
- Chakra extra.
- Bônus de mentalidade.
- Bônus de treino.
- Resistência elemental.
- Redução de custo de jutsu.
- Velocidade ou mobilidade.

### Qualidade dos Itens

Estrutura sugerida:

- Comum.
- Aprimorado.
- Raro.
- Elite.
- Lendário.

### Filosofia de Itemização

Os itens devem complementar a build do jogador e não substituir o valor da progressão pessoal. O poder principal vem do ninja, enquanto o equipamento melhora e especializa seu desempenho.

## Bosses e Conteúdo de Alto Nível

Os bosses devem ser baseados nas grandes ameaças do universo Naruto, funcionando como objetivos de progressão, desafio e recompensa.

### Categorias de Bosses

- Vilões clássicos do anime.
- Membros de organizações criminosas.
- Ninjas renegados lendários.
- Bijuus.
- Invasores Otsutsuki.
- Bosses especiais como Momoshiki e outros inimigos de escala superior.

### Função dos Bosses

- Conteúdo de grupo.
- Teste de build.
- **Loot por Dano:** A distribuição de recompensas e itens raros de bosses será baseada proporcionalmente no dano causado por cada jogador ou grupo ao boss.
- Fonte de materiais especiais.
- Requisito de progressão em missões.
- Eventos globais do servidor.

### Papel das Bijuus

As bijuus podem ser conteúdo central de endgame ou mid/late game, com alto valor temático.

Ideias de uso:

- Bosses de mundo.
- Eventos periódicos.
- Cadeias de missões especiais.
- Recompensas únicas.
- Sistemas futuros ligados a selamento ou fragmentos de chakra.

### Otsutsuki e Escala Final

Inimigos como Momoshiki podem representar o topo do conteúdo, com foco em:

- Mecânicas especiais.
- Lutas em equipe.
- Alta exigência de progressão.
- Recompensas raras e prestígio.

## Loop Principal do Jogador

O loop principal do servidor pode ser estruturado assim:

1. Receber missões na aldeia.
2. Treinar atributos e evoluir level.
3. Ganhar dinheiro e recursos.
4. Aprender novos jutsus.
5. Melhorar equipamentos.
6. Avançar no rank ninja.
7. Enfrentar áreas mais perigosas.
8. Derrotar bosses e desbloquear conteúdo novo.
9. Desenvolver novos elementos e especializações.
10. Participar do conteúdo de alto nível.

Esse loop ajuda a manter direção clara sem perder a liberdade de build.

## Diferenciais do Servidor

Pontos que tornam o projeto diferente de outros servidores de Naruto:

- O jogador não controla personagens do anime.
- O jogador cria sua própria identidade ninja.
- O sistema é baseado em progressão de carreira shinobi.
- Técnicas são aprendidas por requisitos e estudo.
- Elementos têm papel central na build.
- Treino e mentalidade criam diversidade real de evolução.
- O anime fornece o universo e os jutsus, mas não prende o jogador a classes prontas.
- A economia tem valor prático no progresso.
- As aldeias e ranks estruturam a sensação de mundo vivo.

## Estrutura Inicial Recomendável para Desenvolvimento

Para organizar o projeto e evitar escopo excessivo no começo, uma boa versão inicial pode focar em:

### MVP do Servidor

- 1 aldeia principal: Konoha.
- Progressão até Chunin ou Jonin inicial.
- 3 a 5 elementos base.
- Sistema de level, treino e mentalidade.
- Conjunto inicial de jutsus por elemento.
- Missões básicas por rank.
- Economia funcional simples.
- Itens ninja básicos.
- Alguns bosses principais.
- 1 ou 2 eventos marcantes.

### O que deixar para fases posteriores

- Outras aldeias.
- Kekkei Genkai e combinações avançadas.
- Arena PvP estruturada.
- Guerra entre vilas.
- Crafting avançado.
- Sistema de invocações.
- Conteúdo Otsutsuki completo.
- Endgame com bijuus mais complexo.

## Sistema de Mortes, Feridas e Injustiças (PK)

### 1. Punição por Morte Comum
A morte no jogo carrega consequências significativas para manter a tensão do combate:
- **Perda de Recursos:** Ao morrer, o jogador perde experiência (EXP), níveis de skill e sua mochila (backpack) cai automaticamente no chão (drop total da mochila).
- **Acúmulo de Feridas:** Toda morte acumula um status chamado "Feridas". Este status piora cumulativamente a cada morte consecutiva e funciona como um debuff, reduzindo outros atributos como skills e regeneração de vida/chakra.
- **Recuperação de Feridas:** As feridas podem ser curadas gradualmente com o tempo ou utilizando itens medicinais específicos.

### 2. Sistema de Injustiças e PK (Skulls)
As mortes injustas acumulam punições específicas para controlar o PK (Player Killing) abusivo:
- **Acúmulo de Kills:**
  - Matar um jogador injustamente deixa o assassino com status de PK temporário (White Skull) e adiciona 1 kill injusto à sua ficha.
  - Ao atingir **10 kills injustos**, o jogador recebe a **Red Skull**.
  - Ao atingir **50 kills injustos**, o jogador recebe a **Black Skull**.
- **Regras de Morte no PK:** Ao morrer com White, Red ou Black Skull, as penalidades de morte são as mesmas de um jogador comum (perda da mesma EXP, skills e queda da mochila). O status de PK não aumenta a perda de itens de forma direta além da mochila comum.
- **Redução de Kills:** Para diminuir a contagem de kills injustos, o jogador pode:
  - Morrer para outros jogadores ou monstros (cada morte reduz o contador de kills).
  - Realizar missões de redenção específicas.
- **Restrições para PKs Altos:** Jogadores com alta contagem de injusts (Red/Black Skull) sofrerão restrições sociais e geográficas na vila:
  - Bloqueio de entrada em locais protegidos específicos (como templos).
  - Impossibilidade de aceitar ou completar certas missões (quests) da aldeia.

Essa divisão ajuda a lançar uma base sólida antes de expandir o universo.

## Direção de Design do Projeto

A ideia do servidor deve seguir algumas diretrizes centrais:

- Progressão antes de fanservice.
- Identidade própria antes de personagem pronto.
- Liberdade de build com limites saudáveis.
- Conteúdo com sensação de carreira ninja.
- Jutsus como conquista, não como presente automático.
- Economia útil e integrada ao progresso.
- Expansão gradual de mundo e sistemas.

## Resumo Conceitual do Jogo

Este servidor Naruto propõe uma experiência mais original e imersiva, na qual o jogador vive sua própria jornada shinobi dentro de um mundo inspirado no anime. Em vez de assumir personagens famosos, ele começa como um ninja comum, escolhe afinidades, treina corpo e mente, aprende técnicas, sobe de rank, participa da economia da aldeia e enfrenta as grandes ameaças do universo ninja.

A grande força da ideia está em unir:

- Progressão autoral.
- Construção de build.
- Universo temático forte.
- Liberdade de evolução.
- Conteúdo escalável para longo prazo.

## Próximos Passos Sugeridos

Depois desta estrutura conceitual, os próximos documentos ideais para o projeto seriam:

- Documento de sistemas base, com fórmulas e atributos.
- Documento de progressão de ranks e requisitos.
- Documento de elementos e árvore de jutsus.
- Documento de economia inicial.
- Documento de mapa inicial e fluxo de missão.
- Documento de MVP técnico para TFS 1.4.2 + OTCv8.
- Documento de monetização saudável e retenção.
