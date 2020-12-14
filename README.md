# VIAJEI
Projeto academico de prática profissional de desenvolvimento de software - USF Analise e Desenvolvimento de Sistemas

Descrição: Projeto de sistema de gerenciamento de viagens corporativas, aprovações dos superiores das áreas e integração com a área financeira. 
Técnologia: Java NetBeans modelador, FrontEnd Java Swing  e Banco de Dados MySql + com API microsoft Flow + Movimentações financeiras realizadas pelo PIX. 

![Capturar](https://user-images.githubusercontent.com/69700727/102127739-a3598180-3e2b-11eb-90e5-c9d541dc298d.PNG)

# Status
Em andamento.

# Objetivo
O projeto foi desenvolvido na universidade São Francisco - Itatiba na disciplina de prática profissional de desenvolvimento de software.
O objetivo deste programa é realizar o gerenciamento de viagens corporativas:
- Cadastro,exclusão, consulta e atualização de adiantamento de viagem.<br>
- Solicitação de aprovação do adiantamento de viagem, com fluxo de aprovação pela API microsoft flow.<br> 
- Criação do relatório de viagem e prestação de contas.<br> 
- Solicitação de aprovação de relatório de viagens, com fluxo de aprovação pela API microsoft flow.<br> 
- Consulta saldo de conta corrente e movimentações financeiras realizadas pelo PIX.

# Desenvolvimento
Este projeto esta totalmente em JAVA, JAVA SWING e tem suporte do banco de dados MySql onde utilizamos a aplicação do MySQL no XAMP(Rodando no servidor Local).
Atualmente foram geradas as classes:
- IMAGENS (Imagens do sistema).<br> 
- MODEL(Classe cor do sistema adiantamento de Viagens).<br> 
- VIEW (Classes de interface graficas: Menu principal, cadastras adiantamento e consultar adiantamento).<br> 
- CONTROL (Classe controladora onde é realizada a integração entre a interface e os valores e consultar do banco de dados).<br> 
- DAO (Classe de conexão diretas com banco de dados onde é aplicados os comandos SQL no programa).<br> 

# Requisitos
Até o momento, foi utilizado apenas as ferramentas: NetBeans 8.0.1<br> 
Kit XAMP - Apache + MariaDB + PHP + Perl: https://www.apachefriends.org/pt_br/download.html <br>
Para desenho de documentação foi utilizado o software:https://online.visual-paradigm.com/ <br> 
Tutorial para trabalhar com CRUD com java SWING: https://www.youtube.com/watch?v=wExUVfZfgfk&list=PLdvD02W3316JtVoctAc_Dg_1PefHgaFYI&index=1 <br>

# Funcionamento
- O usuário irá logar no menuPrincipal e escolher o item de menu de sua preferencia <br>
- Ao abrir o usuário poderá incluir adiantamento, excluir, alterar e limpar a tela <br>
- No menu de cadastro de adiantamento o usuário poderá clicar no botão buscar para consultar algum ID de adiantamento e assim realizar as operações do seu desejo no menu de cadastro de adiantamento <br>

# Movimentos futuros
- Criar cadastramento completo (MODEL, VIEW E CONTROLE) de acordo com o diagrama de classes da aba "Documentação"<br>
- Criação de vinculado das tabelas do banco de dados MySql com os eventos do microsoft Flow e gerar fluxo de aprovação por e-mail. <br>
- Vinculo API do PIX para vincular todos os movimentos de conta corrente, obter buscar e relatórios.<br>

# DOCUMENTAÇÃO:
- Diagrama de casos de USO:[DiagramaCasosDeUso.pdf](https://github.com/bbarthf/PPDEVSOFTWARE/files/5691527/DiagramaCasosDeUso.pdf) <br>
- Diagrama de Classes: [DiagramaDeClasseV3.pdf](https://github.com/bbarthf/PPDEVSOFTWARE/files/5691531/DiagramaDeClasseV3.pdf)<br>

# AUTOR
Brenda Barth Ferreira <br>
