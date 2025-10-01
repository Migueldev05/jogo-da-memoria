LER – Levantamento de Requisitos (Jogo da Memória) 

O documento a seguir menciona e desenvolve os requisitos funcionais e não-funcionais a respeito do Projeto de Reposição do dia 27/09/25, o Jogo da Memória, desenvolvido por Tiago Alves da Silva e Miguel Moreira da Silva. 



Requisitos Funcionais: 

● RF1: O sistema deve permitir ao jogador selecionar a dificuldade do jogo (Fácil, Médio ou Difícil), alterando a quantidade de cartas disponíveis. 

● RF2: O sistema deve permitir habilitar o modo multijogador, em que dois jogadores se alternam nas jogadas. 

● RF3: O sistema deve exibir de forma dinâmica as informações da partida: quantidade de jogadas, tempo decorrido e pontuação. 

● RF4: O sistema deve controlar a vez do jogador no modo multijogador, alternando quando ocorre erro. 

● RF5: O sistema deve contar pontos individualmente para cada jogador no modo multijogador. 

● RF6: O sistema deve exibir uma mensagem de vitória ao final da partida: Para jogador único → mensagem de conclusão. Para multijogador → vencedor ou empate. 

● RF7: O sistema deve embaralhar e distribuir as cartas em cada nova partida. 

● RF8: O sistema deve permitir que cartas sejam clicadas para virar e mostrar seu emoji. 

● RF9: O sistema deve identificar pares iguais: Se forem iguais, mantêm-se virados. Se forem diferentes, voltam a ficar escondidos após um breve intervalo. 

● RF10: O sistema deve impedir que mais de duas cartas sejam viradas ao mesmo tempo. 

● RF11: O sistema deve iniciar a contagem de tempo apenas após a primeira jogada. 

● RF12: O sistema deve permitir que o jogador reinicie a partida clicando em “Iniciar Jogo”. 

● RF13: O sistema deve oferecer um botão para alternar o modo de alto contraste, alterando o esquema de cores para preto e amarelo. 



Requisitos Não-funcionais: 

● RNF1: O texto “Escolha a dificuldade” deve ser exibido ao lado da caixa de seleção para orientar o jogador. 

● RNF2: Cada nível de dificuldade deve mostrar entre parênteses a quantidade de cartas correspondentes. 

● RNF3: A opção Multijogador deve estar acompanhada de um rótulo textual “Multijogador” para indicar sua função. 

● RNF4: A caixa de seleção de Multijogador deve indicar visualmente seu estado ativado (preenchido com azul e com marcador de “confirme” em branco). 

● RNF5: Botões e caixas devem apresentar efeito visual de destaque ao passar o mouse (hover). 

● RNF6: As cartas devem iniciar com o ícone interrogação (❓), representando que estão viradas. 

● RNF7: As cartas devem aumentar de escala levemente ao passar o mouse, para indicar seleção. 

● RNF8: Ao serem viradas, as cartas devem mudar de cor de fundo e revelar o emoji ou ícone correspondente. 

● RNF9: Quando um par for encontrado, as cartas devem permanecer reveladas e manter a nova cor de fundo. 

● RNF10: A interface deve ser responsiva, adaptando a grade de cartas em telas pequenas. 

● RNF11: O sistema deve apresentar cores contrastantes (modo normal e modo alto contraste) para garantir acessibilidade visual. 

● RNF12: O sistema deve ser leve o suficiente para rodar em navegadores comuns sem lentidão perceptível. 

● RNF13: O temporizador deve atualizar em intervalos de 1 segundo.