# Teste_Stroop-CheckPoint3
Versão da aplicação teste Stroop, atendendo aos requerimentos do Checkpoint 3



Mapeamento de Funcionalidades:

RF002 - Iniciar a sessão - Cadastro.html (A partir da linha 88)
Neste trecho se econtra a estrutura do formulário, mas é a partir da linha 88 que se inicia o algorítimo de validação de campos e captura de dados para o inicio da sessão.

RF003 - Cadastrar S.E. - Cadastro.html (Da linha 38 a 175) 
Neste intervalo existe de maneira geral, toda a estrutura do formulário, validação de campos e paginação.

RF004 - Ver Info. na escolha de grupos - Cadastro.html (Linha 38  a 49)
Neste ponto existe a estrutura do popUp, infomando os grupos esperimentais, existe também os comandos para habilitar e desabilitar este popUp.

RF005 - Escolher grupo - Cadastro.html - (Linha 164 a 181) 
Neste trecho do código existe a estrutura radio para a seleção do grupo e o salvamento temporário da escolha utilizando a função localStorage(), a mesma será acessada em outras páginas do projeto enquanto a aplicação estiver aberta.

RF006 - Iniciar teste - manu.html - (Linha 43)
Neste ponto o usuário pode clicar no elemento button para iniciar o teste, pelo falo de outros requisitos estarem finalizados, o requisito inicar o teste se considera feito.

RF007 - Iniciar contagem - Teladeaplicacao.html - (Linha 230 a 252)
Neste ponto é iniciado e configurado um cronômetro assim que é começado o teste, no fim, a hora inicial, a hora final e o tempo total gasto são armazenados com a função localStorage().

RF008 - Ver estímulo - Teladeaplicacao.html - (Linha 52 a 252) 
Neste ponto é configurada a aplicação do teste, os estilos são apresentados em ordem dentro do retângulo que é um canvas, os botões vão trocando entre si aleatoriamente suas posições, e no fim, os acertos, erros são computados.

RF011 - Ver Relatório de desempenho -Relatório.html - (Linha 37 a 63)
Neste ponto são trazidos os dados armazenados com a função localStorage(), os mesmo são exibidos em uma espécie de tabela, as variáveis são: Erros, Acertos, Hora inicial do teste, Hora final do teste e Tempo total gasto.

