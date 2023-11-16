# 1. Requisitos Funcionais

<p align="justify">A <i>Tabela 1</i> a seguir contém os Requisitos Funcionais (RF) elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                 Requisito                                 | Prioridade | Requisitos Relacionados |
| :--: | :-----------------------------------------------------------------------: | :--------: | :---------: |
| RF01 |                Regras do jogo: As peças se localizam nas casas escuras em um tabuleiro 8x8, tendo 12 peças cada jogador, um jogador com coloração branca e o outro preta. A primeira jogada sempre das peças claras.  O objetivo do jogo é capturar ou imobilizar todas as peças do adversário.   |  Alta      |    -  |
| RF02 |                   Deve ser possível a captura das peças adversária quando uma jogada válida for realizada, sendo proibido capturar 2 ou mais peças juntas na mesma diagonal, e captura tanto pra frente quanto pra trás. Em uma jogada é obrigatório capturar o maior número de peças possíveis. |  Alta      |    RF01  |
| RF03 |          Movimentação das peças: O aplicativo deve permitir que os jogadores movam as suas peças na diagonal (frente) de acordo com as regras do jogo de damas.A peça só anda 1 casa de cada vez. Quando a pedra atinge a oitava linha do tabuleiro, ela é promovido a Dama. |  Alta      |   RF02  |
| RF04 |       Movimentos da Dama: Anda na diagonal para trás e para frente, quantas casas quiser. E a Dama não pode saltar uma peça da mesma cor. |  Alta    |     RF03       |    
| RF05 |        O usuário deve poder acessar o seu progresso no jogo.                 |  Baixa     |     RF01       |    
| RF06 |                    O usuário deve poder acessar seu nível no jogo.     |  Baixa     |    RF02         |
| RF07 |         O usuário deve poder escolher o modo e/ou a dificuldade do jogo   |  Média   |        -     |
   


<div style="text-align: center">
<p>Tabela 1: Requisitos Funcionais</p>
</div>

# 2. Referências


<a href="../README.md">VOLTAR INÍCIO</a>
