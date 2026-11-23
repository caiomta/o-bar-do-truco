# Game Design Document (GDD): O Resgate no Bar do Truco

## 1. Visão Geral e Premissa
* **Título Provisório:** O Resgate no Bar do Truco (ou *All-In no Bar do Truco*)
* **Gênero:** Jogo de Cartas / Roguelite de Truco / Comédia Narrativa
* **Protagonista:** **Gartô Baleno**, um jogador de truco lendário, porém atualmente na pior.

### Sinopse Narrativa
Há exatamente um mês, a esposa de Gartô Baleno terminou o relacionamento. Devastado e afogando as mágoas, Gartô acumulou uma dívida astronômica de **R$ 5.000 (5k)** em bebidas, cigarros e apostas no infame **Bar do Truco**. 

Agora, o destino lhe deu uma segunda chance: sua ex-esposa sinalizou que quer reatar. O problema? Gartô morre de vergonha de aparecer para recomeçar a vida carregando um pendura de 5k no boteco. Sabendo que sua única habilidade real é o carteado, ele propõe um desafio audacioso ao Dono do Bar: **se Gartô vencer todos os bêbados do estabelecimento e derrotar o próprio dono na mesa final, a dívida será 100% perdoada.**

---

## 2. Mecânicas Principais e Gameplay

### O Sistema de Truco: *Free for All* (4 Jogadores)
Diferente do truco tradicional em duplas, todas as partidas ocorrem no formato **Cada um por si (4 jogadores)**, aumentando o caos, o blefe e a imprevisibilidade.

* **Distribuição:** Cada um dos 4 jogadores recebe 3 cartas por mão (com *vira* e *manilhas* definidas pela regra da casa).
* **Pontuação Individual:** Cada jogador marca seus próprios pontos até atingir a meta (ex: 12 pontos).
* **Apostas e Blefes (Truco / 6 / 9 / 12):**
  * Qualquer jogador pode pedir truco na sua vez.
  * Todos os outros 3 oponentes devem responder (Aceitar, Correr ou Aumentar).
  * Se todos correrem, quem pediu leva os pontos imediatamente.
  * *Dinâmica de Mesa:* Sem parceiros para cobrir mãos fracas, a leitura de expressão dos bots e o timing do blefe são essenciais. Alianças silenciosas e temporárias podem surgir naturalmente contra quem estiver liderando o placar.

### Progressão e Loop de Jogo
1. **Escolha/Avanço de Mesa:** Gartô avança pelas mesas do bar, enfrentando trios de oponentes cada vez mais difíceis e embriagados.
2. **Vitória e Coletáveis:** Ao vencer uma mesa, Gartô recebe um **Coletável** temático deixado pelos perdedores ou pelo garçom, que vai direto para o seu **Inventário**.
3. **Preparação para o Boss:** Os itens acumulados ao longo da noite são guardados estrategicamente para a grande final.

### Coletáveis e Superpoderes (A Mesa do Boss)
* **O Confronto Final:** A última mesa é contra o **Dono do Bar e seus dois melhores amigos** (que jogam sujo e têm vantagens naturais).
* **Uso do Inventário:** Durante a partida contra o Boss, Gartô pode ativar os coletáveis acumulados. Cada item concede um **superpoder** capaz de virar o jogo (ex.: espiar a carta de um oponente, trocar uma carta da mão, forçar um blefe, alterar a *vira* da rodada, anular um pedido de 6, etc.).

---

## 3. Oponentes: Os Bebums do Mundo Pop
Os adversários nas mesas são caricaturas bêbadas inspiradas em ícones da cultura pop, cada um com seu próprio estilo de jogo, nível de embriaguez, falas e "tiques" de blefe:
* **Arquétipo Agressivo:** Pede truco na primeira rodada mesmo com cartas baixas.
* **Arquétipo Calculista:** Só aposta quando tem manilha na mão, mas entrega sinais visuais quando está nervoso.
* **Arquétipo Caótico:** Imprevisível devido ao nível de álcool; joga cartas altas sem critério e confunde a leitura da mesa.

---

## 4. Finais Possíveis

### Final Feliz: O Perdão Limpo
* **Condição:** Gartô vence todas as mesas e derrota o Dono do Bar na final.
* **Desfecho:** O Dono do Bar rasga a comanda de R$ 5.000 na frente de todos. Gartô sai do bar de cabeça erguida, sem dívidas e pronto para reatar com sua esposa de forma honesta, conquistando o perdão e um novo começo.

### Final da Derrota: O Cafajeste de Quinta Categoria
* **Condição:** Gartô perde uma mesa decisiva ou é derrotado pelo Dono do Bar.
* **Desfecho:** Humilhado e ainda devendo os 5k, a verdade vem à tona. Sua esposa percebe que ele não mudou nada, desiste de vez de confiar num "cafajeste de quinta categoria" e o larga definitivamente — deixando Gartô sozinho no balcão com a conta para pagar.

---

## 5. Próximos Passos de Desenvolvimento
* [ ] Definir a lista exata de personagens/bots do mundo pop e suas habilidades passivas.
* [ ] Criar o catálogo de coletáveis e balancear os superpoderes para a luta contra o Boss.
* [ ] Estabelecer as regras específicas de desempate (*cango*/embucho) no modo *Free for All* de 4 jogadores.
* [ ] Definir a direção de arte (ex.: 2D estilizado, *pixel art* de boteco, cartunesco) e trilha sonora.