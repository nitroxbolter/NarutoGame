# CHECKLIST DE DESENVOLVIMENTO

Este arquivo mostra a sequência prática recomendada para desenvolver o servidor sem improviso.

## Fase 0 - Definições

- [x] Definir visão central do jogo.
- [x] Definir público e estilo.
- [x] Definir loop principal.
- [x] Definir MVP.
- [x] Definir o que ficará fora do MVP.
- [x] Definir nomenclatura dos sistemas.
- [ ] Definir padrões finais de IDs.
- [ ] Definir padrões finais de pastas.
- [ ] Definir convenções finais de código.

## Fase 1 - Fundação técnica

- [ ] Preparar repositório.
- [ ] Preparar servidor TFS.
- [ ] Preparar OTCv8.
- [ ] Preparar banco de dados.
- [ ] Definir ambiente de desenvolvimento.
- [ ] Definir processo de backup.
- [ ] Definir logs.
- [ ] Definir tratamento de erros.
- [ ] Testar conexão servidor-cliente.
- [ ] Testar extended opcodes.

## Fase 2 - Personagem

- [ ] Criar personagem.
- [ ] Salvar personagem.
- [ ] Carregar personagem.
- [ ] Implementar atributos.
- [ ] Implementar vida.
- [ ] Implementar chakra.
- [ ] Implementar regeneração.
- [ ] Implementar elemento principal.
- [ ] Implementar rank ninja.
- [ ] Implementar reputação.
- [ ] Criar interface básica.

## Fase 3 - Jutsus

- [ ] Criar estrutura de dados dos jutsus.
- [ ] Criar sistema de aprendizado.
- [ ] Criar sistema de nível de jutsu.
- [ ] Criar ganho de experiência.
- [ ] Criar validações contra abuso.
- [ ] Criar custo de chakra.
- [ ] Criar cooldown.
- [ ] Criar dano.
- [ ] Criar efeitos.
- [ ] Criar interface de jutsus.
- [ ] Criar primeiros jutsus do MVP.

## Fase 4 - Combate

- [ ] Definir fórmula de dano.
- [ ] Implementar defesa.
- [ ] Implementar resistência.
- [ ] Implementar crítico.
- [ ] Implementar esquiva.
- [ ] Implementar status.
- [ ] Implementar morte.
- [ ] Implementar PvE.
- [ ] Implementar PvP.
- [ ] Implementar combate justo e injusto.

## Fase 5 - Missões e progressão

- [ ] Criar estrutura de missão.
- [ ] Criar estados da missão.
- [ ] Criar NPCs.
- [ ] Criar diálogos.
- [ ] Criar recompensas.
- [ ] Criar Academia.
- [ ] Criar progressão até Genin.
- [ ] Criar primeiras missões rank D.
- [ ] Criar primeiras missões rank C.
- [ ] Testar abandono e reconexão.

## Fase 6 - Mundo e conteúdo

- [ ] Criar vila inicial.
- [ ] Criar áreas seguras.
- [ ] Criar áreas de caça.
- [ ] Criar criaturas.
- [ ] Criar drops.
- [ ] Criar equipamentos.
- [ ] Criar economia inicial.
- [ ] Criar dungeon.
- [ ] Criar primeiro boss periódico.

## Fase 7 - Reputação e injustiças

- [ ] Definir ações criminosas.
- [ ] Definir PvP permitido.
- [ ] Registrar injustiças.
- [ ] Criar estados de reputação.
- [ ] Criar restrições.
- [ ] Criar missões de redenção.
- [ ] Criar sistema de morte injusta.
- [ ] Criar proteções contra abuso.
- [ ] Criar logs administrativos.

## Fase 8 - Profissões

- [ ] Criar estrutura de profissão.
- [ ] Criar profissão inicial.
- [ ] Criar progressão.
- [ ] Criar habilidades.
- [ ] Criar interface.
- [ ] Criar integração com economia.
- [ ] Testar balanceamento.

## Fase 9 - Eventos e títulos

- [ ] Criar agendador de bosses.
- [ ] Criar avisos.
- [ ] Criar registro de participação.
- [ ] Criar distribuição de recompensas.
- [ ] Criar sistema de candidatos a Hokage.
- [ ] Criar disputa pelo título.
- [ ] Criar duração do mandato.
- [ ] Criar perda do título.
- [ ] Criar proteção contra manipulação.

## Fase 10 - Testes e lançamento

- [ ] Criar testes de sistemas.
- [ ] Testar banco de dados.
- [ ] Testar reinício do servidor.
- [ ] Testar desconexões.
- [ ] Testar duplicação de itens.
- [ ] Testar abuso de experiência.
- [ ] Testar economia.
- [ ] Testar progressão.
- [ ] Testar PvP.
- [ ] Realizar teste fechado.
- [ ] Corrigir problemas críticos.
- [ ] Preparar versão MVP.

## Como usar este checklist

1. Sempre avance de cima para baixo.
2. Não implemente uma fase inteira sem fechar a anterior.
3. Cada item deve apontar para a documentação relacionada.
4. Cada implementação precisa ter testes e status.
5. Quando houver dúvida de design, consulte `DECISOES_PENDENTES.md`.
