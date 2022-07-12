## :computer: Projeto

O Teste Stroop como aplicação web têm como objetivo, facilitar na administração do Teste Stroop realizado no Departamento de Psicologia da UFC pela Professora Daniely Tatmatsu, a disciplina de Análise Experimental do Comportamento (AEC), obrigatória do 4° semestre do curso de Psicologia da UFC, que até então era executada em folhas de papel. O projeto foi desenvolvido durante a disciplina de Projeto Integrado I no semestre 2022.1 pela equipe SMD FORCE, formada por <a href="#">Guilherme Cavalcante Pires de Castro Studart</a>, <a href="#">Francisco Thales Rodrigues Andrade</a>, <a href="#">Edvando Ferreira Guilherme</a>, <a href="#">Jonathan Oliveira Silva</a> e <a href="#">Pedro Augusto Sousa Moura</a>.


## :pushpin: Requisitos funcionais
Versão da aplicação teste Stroop.



Mapeamento de Funcionalidades:

| Código/Funcionalidade | Descrição | Codificação |
| --------------------- | --------- | ----------- |
| RF001/Ver tutorial | O aluno/professor pode visualizar um tutorial sobre como fazer o teste na aplicação. | tutorial.html (Linhas 39 a 49) |
| RF002/Iniciar a sessão| O aluno/professor precisa clicar no botão "Entrar" para ter acesso a aplicação. | index.html (Linha 30) |
| RF003/Cadastrar S.E.  | O aluno/professor precisa colocar os dados do Sujeito experimental | cadastro.html (Linhas 38 a 175) |   
| RF004/Ver Info na escolha de grupos | O aluno/professor pode acessar o botão info para ver informações sobre a escolha do grupo. | cadastro.html (Linhas 38  a 49) |  
| RF005/Escolher grupo | O aluno/professor precisa escolher um grupo para poder prosseguir na aplicação. | cadastro.html (Linha 164 a 181)  |
| RF006/niciar teste | O aluno/professor precisa clicar no botão "Iniciar" para começar o Teste. | menu.html (Linhas 40 a 47) |
| RF007/Iniciar contagem | Ao iniciar o teste um contador começar a contabilizar o tempo.  | teladeaplicacao.html (Linhas 230 a 252) |
| RF008/Ver estímulo | Durante o Teste, o aluno/professor precisa ver o estímulo de cada folha | teladeaplicacao.html (Linhas 52 a 252) |
| RF009/Ver alternativas de respostas | Durante o Teste, o aluno/professor precisa selecionar uma das alternativas de respostas. | teladeaplicacao.html (Linhas 52 a 252)|
| RF010/Ver tela de descanso | O aluno/professor precisa vizualizar uma tela de intervalo com um cronômetro decrescente, após ter concluído 4 folhas do teste. | descanso.html (Linhas 40 a 123) |
| RF011/Ver tela final | O aluno/professor precisa vizualizar uma tela de conclusão após finalizar o teste.| final.html (Linhas 40 a 58) |
| RF012/Gerar o relatório com as variáveis do teste (tempos, acertos e erros) | Após a conclusão do teste, o aluno/professor precisar ver, resumidamente, seu desempenho. | teladeaplicacao.html (Linhas 290 a 315) e relatorio.html(Linhas 60 a 266) |
| RF013/Ver erros e acertos totais | Neste ponto o usuário pode analisar a quantidade de erros e acertos gerais obtidos pelo mesmo na execução do teste | relatorio.html (Linhas 135 a 136) |
| RF014/Ver erros e acertos por tipo | Neste ponto o usuário pode analisar e erros e acertos de uma maneira mais específica, desta vez por tipo de folha | relatorio.html (Linhas 137 a 140) |
| RF015/Ver tempo total gasto | Neste ponto o usuário observa todo o tempo gasto para a realização de teste | relatorio.html (Linhas 141) |
| RF016/Ver tempo gasto por tipo | Neste ponto o usuário observa o tempo gasto com cada tipo de folha | (Linhas 142 e 143) |
| RF017/Sair da aplicação | Após iniciar a sessão, o aluno/professor pode sair da aplicação a qualquer momento ao clicar no ícone "home". | cadastro.html, gráfico.html e final.html (linha 31) <br> menu.html (linha 30) <br> tutorial.html e relatorio.html (linha 32) <br> teladeaplicação.html (linha 38) <br>  
