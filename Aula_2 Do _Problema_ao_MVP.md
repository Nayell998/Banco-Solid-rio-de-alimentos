🧾 Entregáveis – Aula 2 (Do problema ao MVP)
 
🧍‍♀️ Documento de Personas
 
Persona 1 – Dona Maria (Loja de Artesanato)
 
- Idade: 52 anos
- Ocupação: Proprietária de uma pequena loja de artesanato local.
- Objetivo: Simplificar a gestão do estoque de produtos artesanais, agendar clientes para workshops e gerenciar pedidos personalizados, tudo em um só lugar.
- Desafios: Dificuldade em controlar o estoque de forma manual, perdendo tempo e produtos. Problemas em organizar os horários dos workshops e pedidos, resultando em atrasos e insatisfação dos clientes.
- Motivação: Quer ter mais tempo para se dedicar à criação de novas peças e ao atendimento dos clientes, sem se preocupar com a burocracia da gestão.
 
 
 
Persona 2 – Carlos (Pequeno Salão de Beleza) hum
 
- Idade: 38 anos
- Ocupação: Dono de um pequeno salão de beleza no bairro.
- Objetivo: Otimizar o agendamento de horários dos clientes, controlar o estoque de produtos de beleza e gerenciar os pedidos de serviços adicionais (como pacotes promocionais).
- Desafios: Dificuldade em evitar horários duplicados e controlar a disponibilidade dos profissionais. Problemas em manter o controle do estoque de produtos, resultando em falta de itens importantes.
- Motivação: Deseja oferecer um atendimento de qualidade aos clientes, sem perder tempo com tarefas administrativas e garantindo a disponibilidade dos produtos necessários.
 
 
 
📖 5 User Stories do MVP
 
1. Como dono(a) de loja, quero cadastrar meus produtos no sistema, informando nome, descrição, preço e quantidade em estoque, para ter controle do meu inventário.
2. Como dono(a) de salão, quero agendar horários para meus clientes, informando o profissional responsável, o serviço e a duração, para evitar conflitos e otimizar a agenda.
3. Como vendedor(a), quero registrar os pedidos dos clientes, informando os produtos/serviços, a quantidade e o valor total, para gerar um comprovante e controlar as vendas.
4. Como administrador(a), quero gerar relatórios de vendas, estoque e agendamentos, para analisar o desempenho do meu negócio e tomar decisões estratégicas.
5. Como cliente, quero receber lembretes automáticos dos meus agendamentos, para evitar esquecimentos e garantir a minha presença.
 
 
 
🗂️ Quadro Kanban (com responsáveis atribuídos)
 
| Coluna        | Tarefa |

|Coluna|Tarefa|Responsável|Prioridade|Prazo Estimado|Observações|
|:---|:---|:---|:---|:---|:---|
|**Backlog**|||||*Lista de todas as tarefas planejadas, mas ainda não iniciadas.*|
||Levantar requisitos detalhados com usuários potenciais|Equipe de Análise|Alta|2 dias|Entrevistar pequenos comerciantes e donos de salão para entender suas necessidades específicas.|
||Criar protótipo de baixa fidelidade (wireframes)|Pedro|Alta|3 dias|Desenhar as telas principais do sistema para validar o fluxo de navegação.|
||Definir a arquitetura do sistema (frontend, backend, banco de dados)|Maria e Thiago|Alta|2 dias|Escolher as tecnologias mais adequadas para o projeto.|
|**A Fazer**|||||*Tarefas que estão prontas para serem iniciadas.*|
||Criar tela de login e registro|Thiago|Alta|5 dias|Implementar a autenticação de usuários com segurança.|
||Configurar banco de dados inicial|Maria|Alta|3 dias|Criar as tabelas necessárias para armazenar os dados do sistema.|
||Implementar funcionalidade de recuperação de senha|Thiago|Média|3 dias|Adicionar a opção de recuperar a senha por e-mail.|
|**Em Progresso**|||||*Tarefas que estão em desenvolvimento.*|
||Criar perfil do usuário (dono de loja/salão)|João|Alta|5 dias|Permitir que os usuários personalizem suas informações de perfil.|
||Implementar funcionalidade de cadastro de produtos/serviços|Ana|Alta|7 dias|Permitir que os usuários cadastrem seus produtos ou serviços com detalhes como nome, descrição, preço, quantidade, etc.|
||Implementar sistema de agendamentos|Carla|Alta|7 dias|Permitir que os usuários agendem horários para seus clientes, informando o profissional responsável, o serviço e a duração.|
|**Em Teste**|||||*Tarefas que foram desenvolvidas e estão sendo testadas.*|
||Testar cadastro de produtos e agendamentos|Equipe de Testes|Alta|3 dias|Verificar se todas as funcionalidades estão funcionando corretamente e se não há bugs.|
||Testar a responsividade da interface em diferentes dispositivos|Equipe de Testes|Média|2 dias|Garantir que o sistema funcione bem em computadores, tablets e smartphones.|
|**Concluído**|||||*Tarefas que foram finalizadas e aprovadas.*|
||Criação das personas e user stories|Equipe EduConnect|Alta|-|-|
||Design da interface principal|Pedro|Alta|-|-|
|**Em Implantação**|||||*Tarefas que estão sendo preparadas para serem colocadas em produção.*|
||Preparar ambiente de produção|Equipe de Implantação|Alta|2 dias|Configurar o servidor e o banco de dados para receber o sistema.|
||Configurar envio de lembretes automáticos|Lucas|Média|3 dias|Integrar o sistema com um serviço de envio de e-mails ou SMS para enviar lembretes aos clientes.|


