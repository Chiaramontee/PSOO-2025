### 1. Gerenciamento de chamados
| Rank | Prioridade | História do Usuário                                                                                                                                                       | Regra de negócio | STATUS |
| :--: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------:                                  | :------------------: | :----: | 
|   1  |    Alta    | O sistema deve permitir que o usuário crie um novo chamado, informando título, descrição, categoria e prioridade.                                                      |          RN01        |   ❌   |
|   2  |    Alta    |Apenas usuários autenticados podem abrir chamados de suporte no sistema.                                                                                                  |          RN02        |   ❌   |
|   3  |    Alta    | O sistema deve permitir que usuários anexem arquivos a um chamado, tanto no momento da abertura quanto enquanto ele estiver em andamento (status "Aberto"). O limite máximo é de 2 arquivos por chamado                                                                                                                 |          RN03       |   ❌   |
|   4  |    Alta     | Todos os usuários podem visualizar chamados com base nos seus papéis.                                                                                                     |          RN04        |   ❌   |
|   5  |    Alta    | A Inteligência Artificial (IA) do sistema deve categorizar e priorizar automaticamente os chamados abertos pelos usuários de acordo com os campos preenchidos.                                                                                                               |          RN05        |   ❌   |
|   6 |    Alta   |         A Equipe de TI poderá atualizar o status dos chamados durante o processo de atendimento.                                                                                                               |          RN06         |   ❌   |

### 2. Gerenciamento de usuários
|  Rank | Prioridade | Historia do Usuário                                                                                                                | Regra de negocio | STATUS |
| :--: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------: | :----: | 
|   9  |    Alta    |O sistema deve autenticar todos os usuários antes de permitir o acesso às funcionalidades                                                                                |          RN09         |   ❌   |
|   10  |    Média   | O administrador pode cadastrar novos usuários no sistema                                                                     |          RN010       |   ❌   |
|   11 |     Média    | O administrador pode editar dados dos usuários existentes.                                                      |          RN11        |   ❌   |
|   12 |     Média    | O administrador pode visualizar a lista completa dos usuários cadastrados                                                        |          RN12        |   ❌   |

### 3. Gerenciamento de relatórios
|  Rank| Prioridade | HISTÓRIA DO USUÁRIO                                                                                                                        | Regra de negocio | Status |
| :--: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------: | :----: |
|   07  |    Alta    |A equipe de TI   gera relatórios automáticos sobre os chamados registrados, permitindo filtros por status, prioridade, técnico responsável e data, e incluindo gráficos visuais da distribuição e tempo médio de resolução.                                                           |          RN07       |   ❌   |

### 4. Gerenciamento de IA
|  Rank | Prioridade | História do Usuário                                                                                                                     | Regra de negócio| Status |
| :--: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------: | :------------------: | :----: | 
|   24  |    Baixa    |A IA deve classificar automaticamente os chamados em níveis de prioridade (alta, média, baixa) com base no conteúdo e na urgência relatada.                                                              |          RN24        |   ❌   |
|   25 |    Baixa   | Somente o Admin pode atualizar o banco de dados utilizado pela inteligência artificial. .                                                                                         |          RN25       |   ❌   |
|   26 |    Baixa   | IA recebe o chamado e analisa as palavras chaves.                                                                                            |          RN26        |   ❌   |
