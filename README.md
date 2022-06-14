# Meu Primeiro Jogo em *Javascript* - *Treino*
Este jogo criado foi desenvolvido pelo site do mozila - Um primeiro mergulho no Javascript

*link do artigo mozila:* https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/A_first_splash

# O que é esse jogo? O que ele faz?
Este é um estilo de jogo simples de advinhação, no qual a máquina irá escolher um determinado número entre 1 a 100; 
com isso o objetivo do jogo é fazer com que o usuário acerte o numero 'pensado'.

# primeiros passos
Titulo - Advinhe um número

Subtitulo - Selecionamos um número aleatório entre 1 e 100. 
Veja se consegue advinhar em 10 chances ou menos. 
Nós lhe diremos se seu palpite está com valor alto ou baixo.

p - digite seu palpite

botoao - enviar palpite

# rascunho 
  * O que fazer?
  *  Gerar um numero aleatório de 1 - 100
  *  Gravar o numero do turno que o jogador esta. 
      * Iniciar em 1.
  
  *  Dar ao jogador uma forma de advinhar o numero
  *  Apois a tentativa ter sido submetida, primeiro gravar em algum lugar para que o usuario possar ver as tentativas  anteriores
  *  depois, verificar se o paplite esta certo. 
  *  se estiver certo:
      * Escrever mensagem de parabéns.
      * Impedir que o jogador insira mais respostas (isso pode bugar o jogo).
      * Mostrar controle que permita ao jogador reiniciar o jogo.
 
  *  Se o palpite estiver errado e o jogador ainda tem turnos sobrando:
      * Dizer ao jogador que ele está errado.
      * Permitir que ele insira outra resposta.
      * Incrementar o número do turno em 1.
   
  *  Se o jogador está errado mas não tem turnos sobrando:
      * Dizer ao jogador que o jogo acabou.
      * Impedir que o jogador insira mais respostas (isso pode bugar o jogo).
      * Mostrar controle que permita ao jogador reiniciar o jogo.
    
  *  Quando reiniciar, tenha certeza de resetar todas as variáveis e a
        interface do jogo, então volte para o passo 1.
