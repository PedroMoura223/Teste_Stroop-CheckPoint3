# Teste_Stroop-CheckPoint3
Versão da aplicação teste Stroop, atendendo aos requerimentos do Checkpoint 3



Mapeamento de Funcionalidades:

| Código/Funcionalidade | Descrição | Codificação |
| --------------------- | --------- | ----------- |
| RF002/Iniciar a sessão| O aluno/professor precisa clicar no botão "Entrar" para ter acesso a aplicação. | Home.html (linha 30) <br> Home.css (linhas 55 a 69) |
| RF003/Cadastrar S.E.  | O aluno/professor precisa colocar os dados do Sujeito experimental | Cadastro.html (Da linha 38 a 175) <br> Cadastro.css |   
| RF004/Ver Info na escolha de grupos | O aluno/professor pode acessar o botão info para ver informações sobre a escolha do grupo. | Cadastro.html (Linha 38  a 49) |  
| RF005/Escolher grupo | O alunoprofessor precisa escolher um grupo para poder prosseguir na aplicação | Cadastro.html - (Linha 164 a 181)  |


RF006 - Iniciar teste - manu.html - (Linha 43)
Neste ponto o usuário pode clicar no elemento button para iniciar o teste, pelo falo de outros requisitos estarem finalizados, o requisito inicar o teste se considera feito.

RF007 - Iniciar contagem - Teladeaplicacao.html - (Linha 230 a 252)
Neste ponto é iniciado e configurado um cronômetro assim que é começado o teste, no fim, a hora inicial, a hora final e o tempo total gasto são armazenados com a função localStorage().

RF008 - Ver estímulo - Teladeaplicacao.html - (Linha 52 a 252) 
Neste ponto é configurada a aplicação do teste, os estilos são apresentados em ordem dentro do retângulo que é um canvas, os botões vão trocando entre si aleatoriamente suas posições, e no fim, os acertos, erros são computados.

RF011 - Ver Relatório de desempenho -Relatório.html - (Linha 37 a 63)
Neste ponto são trazidos os dados armazenados com a função localStorage(), os mesmo são exibidos em uma espécie de tabela, as variáveis são: Erros, Acertos, Hora inicial do teste, Hora final do teste e Tempo total gasto.

