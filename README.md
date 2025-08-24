# PSOO-2025
Gerenciamentos de Chamados


Esse trabalho é referente ao Projeto Integrado Multidisciplinar do curso de Análise e Desenvolvimento de Sistemas da  UNIP  São José dos Campos, criado em equipe.

<p align="center">
      <img src="img/203549358.jpg" alt="logo da Fatal System" width="400">
      <h2 align="center"> Fatal System</h2>

## Desafio <a id="desafio"></a>
O desafio consiste em criar um sistema de gerenciamento de chamados triados por uma Inteligência Artificial (IA).

O sistema deve permitir que chamados abertos pelos usuários sejam analisados automaticamente pela IA, que irá propor soluções inteligentes para a equipe de TI responsável. A equipe, ao receber essas propostas, deve validar a veracidade das soluções sugeridas, podendo aceitá-las, ajustá-las ou rejeitá-las.

Conforme as respostas são tratadas, todo o histórico dos chamados é armazenado em um repositório centralizado, garantindo rastreabilidade e aprendizado contínuo. Esse histórico pode ser acessado tanto pela equipe de TI quanto pelo administrador e pela própria IA, permitindo consultas, análises e apoio na tomada de decisões em futuras ocorrências.

O objetivo principal é otimizar o fluxo de atendimento, reduzir a sobrecarga da equipe de TI e melhorar a eficiência do processo de resolução de chamados dentro da organização.

## Backlog do Produto

### 1. Gerenciamento de chamados

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|   1  |    Alta    | O sistema deve permitir que o usuário crie um novo chamado, informando título, descrição, categoria e prioridade.                                                                                              |            |      |          R01         |    ❌   |
|   2  |    Alta    | O usuário deve poder revisar os dados preenchidos antes de confirmar o envio do chamado.                                                                                                                       |            |       |          R02         |    ❌   |
|   3  |    Alta    | O sistema deve permitir anexar um ou mais arquivos ao chamado antes do envio e também após o chamado ter sido criado (enquanto estiver em aberto)                                                              |           |      |          R03         |    ❌   |
|   4  |    Alta    | Antes de enviar o chamado, o sistema realiza uma primeira checagem para garantir que todos os campos obrigatórios estejam preenchidos.                                                                         |           |       |          R04         |    ❌   |
|   5  |    Alta    | Se o sistema identificar um campo em branco, o chamado não é enviado e o funcionário é informado para preencher os dados.                                                                                      |           |      |          R05         |    ❌   |
|   6  |    Alta    | Caso a dupla checagem seja concluída com sucesso, o funcionário envia o chamado para a equipe de suporte.                                                                                                      |            |      |          R06         |    ❌   |
|   7  |    Alta    | Sistema permite anexar mais arquivos em um chamado já existente.                                                                                                                                               |             |       |          R07         |    ❌   |
|   8  |    Alta    | O sistema deve permitir que o usuário visualize os chamados criados, de acordo com o seu nível de acesso.                                                                                                      |             |      |          R08         |    ❌   |


### 2. Gerenciamento de Usuário

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|  9  |    Alta    | Como Administrador, eu gostaria de ser o primeiro usuário do sistema, já devidamente pré inserido no banco de dados, para que possa acessar a aplicação.                                                       |          |      |          R09         |    ❌   |
|  10  |    Média   | Como Administrador, eu quero cadastrar novos usuários na plataforma, para que somente pessoas autorizadas possam acessá-la.                                                                                    |           |      |          R10         |    ❌   |
|  11  |    Média   | Como usuário, eu quero acessar a aplicação através de uma interface de login, para que somente usuários autorizados possam utilizar o sistema.                                                                 |          |     |          R11         |    ❌   |
|  12  |    Média   | Como usuário autorizado, eu quero acessar o sistema através de um login, para utilizar a aplicação.                                                                                                            |            |      |          R12         |    ❌   |
|  13  |    Média   | Como usuário autenticado, eu quero poder fazer o logout da aplicação de forma segura, para que meus dados não fiquem acessíveis a terceiros.                                                                   |           |       |          R13         |    ❌   |
|  14  |    Média   | Como Administrador, quero poder editar os dados dos usuarios, caso os mesmos solicitem.                                                                                                                        |            |      |          R14         |    ❌   |
|  15  |    Média   | Como Administrador, eu quero visualizar a lista de usuários cadastrados, para que eu possa gerenciar quem tem acesso ao sistema.                                                                               |            |       |          R15         |    ❌   |
|  16  |    Média   | Como Administrador, eu quero redefinir a senha de um usuário, para que eu possa ajudá-lo caso ele não consiga acessar a conta.                                                                                 |            |       |          R16         |    ❌   |
|  17  |    Média   | Como Administrador, eu quero excluir usuários do sistema, para que possa revogar o acesso de usuários a aplicação.                                                                                             |           |       |          R17         |    ❌   |
|  18  |    Baixa   | Como Administrador, ter a capacidade de denominar niveis de acesso ao sistema de acordo com a função do funcionario.                                                                                           |             |       |          R18         |    ❌   |





### 3. Gerenciamento de IA

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|  24  |    Baixa   | A IA deve classificar automaticamente os chamados em níveis de prioridade (alta, média, baixa) com base no conteúdo e na urgência relatada.                                                                    |          |       |          R24         |    ❌   |
|  25  |    Baixa   | A IA vai identificar o chamado e agrupar na sua respectiva categoria.                                                                                                                                          |          |      |          R25         |    ❌   |
|  26  |    Baixa   | IA recebe o chamado e analisa as palavras chaves.                                                                                                                                                              |            |      |          R26         |    ❌   |
|  27  |    Baixa   | A IA também deve encaminhar o chamado para o setor responsável com base na análise feita.                                                                                                                      |            |      |          R27         |    ❌   |
|  28  |    Baixa   | IA concede solução para setor responsável de TI de acordo com o sugerido pelas palavras chaves.                                                                                                                |          |      |          R28         |    ❌   |


## 📅 Tabela de Sprints
|    Período    | Link para Documentação | Link para Vídeo no YouTube |
| ------------- | ---------------------- | -------------------------- |
| xx/xx - xx/xx | [Sprint 1](#)          | [Vídeo 1](#)               |
| xx/xx - yy/yy | [Sprint 2](#)          | [Vídeo 2](#)               |
| xx/xx - yy/yy | [Sprint 3](#)          | [Vídeo 3](#)               |



<pre>1.a) Criar chamado:
O sistema deve permitir que o usuário crie um novo chamado, informando título, descrição, categoria e prioridade.
O usuário deve poder revisar os dados preenchidos antes de confirmar o envio do chamado.
O sistema deve permitir anexar um ou mais arquivos ao chamado antes do envio e também após o chamado ter sido criado (enquanto estiver em aberto).<br>
1.a.a) Checar chamado:
Antes de enviar o chamado, o sistema realiza uma primeira checagem para garantir que todos os campos obrigatórios estejam preenchidos. 
Se o sistema identificar um campo em branco, o chamado não é enviado e o funcionário é informado para preencher os dados. 
Caso a dupla checagem seja concluída com sucesso, o funcionário envia o chamado para a equipe de suporte.<br>
1.a.b) Anexar mais arquivos:
Sistema permite anexar mais arquivos em um chamado já existente.<br>
  
1.b) Visualizar chamado:
O sistema deve permitir que o usuário visualize os chamados criados, de acordo com o seu nível de acesso.<br> </pre>

### 2. Gerenciamento de Usuário
<pre>2.a) Cadastrar usuário:
Admin cadastra novo usuário.
Sistema gera matrícula.
Admin cadastra senha.<br>
  
2.b) Editar Usuario:
Adm pode editar usuários já criados<br>
  
2.c)Visualizar usuários
Adm pode visualizar funcionários cadastrados.
Adm vai denominar quais permissões os usuários possuem</pre>

### 3. Gerenciamento de IA

<pre>3.a) Priorizar e categorizar chamados:
A IA deve classificar automaticamente os chamados em níveis de prioridade (alta, média, baixa) com base no conteúdo e na urgência relatada.
A IA vai identificar o chamado e agrupar na sua respectiva categoria.
A IA também deve encaminhar o chamado para o setor responsável com base na análise feita.
O administrador poderá revisar e alterar a prioridade, se necessário.<br>
  
3.b) Aplicar solução inteligente:
IA recebe o chamado.
IA analisa palavras chaves do chamado.
IA concede solução para setor responsável de TI de acordo com o sugerido pelas palavras chaves.<br>

</pre>
</pre>

## Solução Proposta
* Priorização e Categorização de chamados por IA
* Capacidade de IA propor soluções dos chamados para Equipe de TI
* Geração de relatórios mensais, semanais e anuais dos chamados
* Criação de Usuario pelo Admin


## Tecnologias Utilizadas
* <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>
* [Astah](https://astah.net/)
* <a href="https://www.microsoft.com/en-us/sql-server/"><img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/></a>
* [Br Modelo](https://www.brmodeloweb.com/lang/pt-br/index.html)

* ## 🎓 Equipe
| Nome                          | Papel         | GitHub                                    | LinkedIn                                                      |
| ----------------------------- | ------------- |------------------------------------------ | ------------------------------------------------------------- |
| Liedson De Oliveira Silva     | Desenvolvedor |[GitHub](https://github.com/liedson-silva) | [LinkedIn](https://linkedin.com/in/liedson-silva-20b78b29


