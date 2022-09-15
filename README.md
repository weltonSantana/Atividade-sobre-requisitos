# Atividade - sobre - Requisitos

Essa atividade tem como objetivo **definir dois requisitos funcionais** de um sistema qualquer, bem como a descrição do **caso de uso expandido** e do **User story** para os requisitos, será feito também o **protótipo** da tela de cada um dos requisitos.

# Requisitos Funcionais

Para essa atividade foi escolhido os seguintes requisitos: 

* registro de usuário
* Agendamento de consulta



# User Story

As histórias de usuários de forma resumida são descrições de recursos curtas e objetivas com a perspectiva do usuário ou cliente.

Para escrever histórias de usuários, a forma mais comum e mais simples é o: **como, quero e para que**.

Sendo esse o método mais popular no meio, criado pelo cofundador da Scrum Alliance, Mike Cohn, a formula será assim:

"**Como** [um tipo de usuário] **quero** [algum recurso específico] **para que** [algum benefício] seja recebido"

Aplicando aos requisitos funcionais teremos:

1. Registro de usuário
  
  "**Como** um novo usuario do sistema **eu quero** criar uma conta nova, com meu nome completo, email e senha **para que** eu tenha acesso a pagina de login e por conseguinte aos recursos do sistema"
  
2. Agendamento de consulta
 
 "**como** um paciente da clinica **eu quero** agendar uma nova consulta com o clinico geral **para que** eu possa realizar exames de rotina e verificar se a saude está em dia"
  


# Caso de uso expandido

Um caso de uso basicamente é uma sequnecia de ações por um sistema que gera um resultado de valor observavel para um ator em particular.

Sua descrição expandida é bastante utilizada para descrever detalhadamente o fluxo do caso de uso, logo, descreve quais eventos acontecem para garantir o sucesso do mesmo. 

Aplicando aos requisitos funcionais teremos:

RQ01 - Registro de Usuários

*Atores:*
  
  Usuário/Cliente - cria uma nova conta no sistema;
  
*Descrição Geral:*
 
 Cadastrar uma nova conta no sistema para ter acesso aos recursos presente nele;
 
*Pré-condição:*

  Para criar uma nova conta, o ator não deve ter uma conta já existente;
 
*Fluxo Principal:*

  1. O ator ao ter acesso a pagina inicial do sistema, selecionará a opção "Cadastre-se";
  2. O sistema irá apresentar uma tela de cadastro com um breve formulario pedindo como informações, o nome do usuario, o email e a senha;
  3. Após preencher todos os campos corretamente, o ator confirma o cadastro no botão "Cadastrar";
  

*Fluxo alternativo:*
 
*FA01* - Botão de logar com uma conta já existente:

1. Na tela de cadastro, o ator irá clicar em um botão no rodapé do formulario escrito "tenho uma conta";
2. O sistema irá apresentar uma tela de login solicitando e-mail e senha;
3. O ator preenche os campos de e-mail e senha e confirma a entrada no sistema apertando o botão "Entrar"



RQ02 - Agendamento de Consulta

*Atores:*
  
  Ator principal - Recepcionista;
  Ator secundario - Paciente;

*Descrição Geral:*
 
 O Ator-recepcionista tem que acessar o sistema e agendar a consulta do paciente;

*Pré-condição:*

 O Ator-recepcionista precisa estar logado no sistema
 
 *Fluxo Principal:*
 
 1. O Ator-recepcionista fará login no sistema;
 2. O sistema apresentará uma tela com um menu de opções;
 3. O ator seleciona a opção de consulta
 4. O sistema apresentará uma tela para agendar a consulta;
 5. O ator principal informa o CPF do ator secundario(paciente);
 6. O sistema mostrará uma tela com os dados do paciente;
 7. O ator principal seleciona a opção de agendamento;
 8. O sistema mostará uma tela com a data e os horários disponíveis e os respectivos médicos disponíveis;
 9. O ator principal seleciona a data e o horario escolhido pelo paciente e clica no botão de confirmar consulta;
 10. O sistema exibe uma mensagem de consulta agendada com sucesso.
 
 *Fluxo alternativo:*
 
*FA01* - Ator secundario(paciente) não está cadastrado no sistema:

1. O sistema apresentará uma tela de cadastro de cliente/paciente;
2. O ator principal(recepecionista) escolhe a opção de cadastrar paciente;
3. O sistema retornará para o passo de numero 6.



