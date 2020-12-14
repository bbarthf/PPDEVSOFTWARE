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
- Criar cadastramento com validação no banco de dados firebase<br>
- Criar perfil "Quero Adotar" e "Quero doar". <br>
  Quero Doar: Perfil onde será cadastrado os cards de pets e o dono poderá incluir ou retirar os pets quando desejados, os pets que apareceram no feed serão os peds       cadastrados pelo os seus donos<br>
  Quero Adotar: Perfil para quem está procurando um pet para adotar, o usuário irá realizar o cadastramento demonstrando o interesse pelo tipo de pet que seja e navegará no feed para o encontrar. <br>
- Criar link entre dono e usuário da adoção, onde quando o usuário desejar entrar em contato com o dono do pet o sistema abrirá um diálogo diretamente com o número de whatsapp cadastrado no sistema de "Quero doar".<br>
- Dsenvolver login por biometria<br>
- Melhorar diálogo de decisão<br>
- Criar geolocalização para melhor demonstrar os pets diponíveis na região do usuário que deseja adotar. <br>
- Melhorar layout das telas<br>
- CRUD completo no firebase para inserir, excluir, alterar e ler do banco de dadoas firebase. <br>

# DOCUMENTAÇÃO:
- Diagrama de casos de USO:

- Diagrama de Classes:



# AUTOR
Brenda Barth Ferreira <br>
