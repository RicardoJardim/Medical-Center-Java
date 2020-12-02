# Medical Center build with Java

Este projeto consiste numa aplicação criada em consola, que permite gerir diferentes atos medicos realizados pelos utentos num centro médico, dando enfase nos principios de Porgramação Orientada a Objetos (POO). Todos os dados são guardados em ficheiros de texto.

## Menu

Ao iniciar a aplicação, é mostrado um menu, que começa por verificar se existem os ficheiros que contêm os médicos e os pacientes, caso estes ficheiros existam é lido e colocado na lista adequada cada um dos dados presentes no ficheiro, logo de seguida é apresentado ao utilizador da aplicação uma mensagem de boas vindas, a data atual e o menu principal do centro médico.
No menu principal estão disponíveis três opções sendo uma para sair da aplicação, uma para entrar no menu de utente e outra para entrar no menu de administrador.
Ao selecionar o menu de utente é apresentada uma lista dos utentes registados em que o utilizador deverá selecionar o utente pretendido, após essa escolha é apresentada uma lista dos médicos registados, e a sua especialidade, em que, novamente, o utilizador deverá selecionar o médico pretendido. De seguida é apresentado um menu onde o utilizador deverá selecionar se pretende marcar uma consulta, ver as consultas marcadas ou avaliar um médico.
Ao selecionar o menu de administrador é necessária a introdução de uma password, de forma a que só quem a sabe tenha acesso a esse menu, estando está definida com o valor “12345”. Após ser introduzida a password correta é apresentado o menu de administrador que permite registar e consultar médicos e utentes, listar as consultas e avançar a data do calendário.

## Este centro médico permite
-Registar novos médicos e utentes, atribuindo aleatoriamente um número único;
-Listar todos os utentes registados, estando ordenados, ou não, de forma ascendente ou descendente pelo valor que gastaram;
-Listar todos os médicos registados, estando ordenados pela classificação;
-Listar todas as consultas do centro médico;
-Listar os utentes que determinado médico consultará num determinado dia;
-Avançar um dia de cada vez do calendário;
-Realizar novas consultas;
-Atribuir uma avaliação a um médico;
-Fazer pagamentos por parte dos utentes;
-Imprimir o valor total que o centro médico recebeu;
-Imprimir o número total de consultas realizadas no centro médico;
-Sair da aplicação;
-Inserir informações do centro médico através do teclado ou através de ficheiros de texto, de forma automática;

## Diagrama UML

![alt text](https://drive.google.com/file/d/1YNAOnuYQgzAAYRKDf_s-ryVxLTVhb0TA/view?usp=sharing "UML")
