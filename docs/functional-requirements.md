# Requisitos Funcionais

RF001 - Autenticação de usuário: tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo.
- Dados necessários: login, senha.
- Usuários: todos os níveis de usuário.

RF002 - Recuperação de senha: permite que os usuários solicitem a recuperação da senha caso a esqueçam.
- Dados necessários: e-mail do usuário.
- Usuários: todos os níveis de usuário.

RF003 - Redefinição de senha: fornece um mecanismo para redefinir a senha dos usuários que solicitaram a recuperação.
- Dados necessários: e-mail do usuário, nova senha.
- Usuários: todos os níveis de usuário.

RF004 - Visualização da agenda de serviços: permite que os usuários visualizem a agenda de serviços disponíveis na clínica.
- Dados necessários: N/A.
- Usuários: todos os níveis de usuário.

RF005 - Agendamento de serviços: permite que os usuários agendem serviços específicos.
- Dados necessários: id do usuário, id do serviço, data e horário.
- Usuários: todos os níveis de usuário.

RF006 - Verificação de disponibilidade de horário: verifica a disponibilidade do horário solicitado pelo usuário e reserva se estiver disponível.
- Dados necessários: data e horário.
- Usuários: todos os níveis de usuário.

RF007 - Confirmação de agendamento: exibe uma mensagem de confirmação ao usuário após a realização do agendamento.
- Dados necessários: id do agendamento.
- Usuários: todos os níveis de usuário.

RF008 - Cancelamento de agendamento: permite que os usuários cancelem um agendamento previamente realizado.
- Dados necessários: id do agendamento.
- Usuários: todos os níveis de usuário.

RF009 - Liberação de horário agendado: libera o horário agendado caso o usuário solicite o cancelamento.
- Dados necessários: id do agendamento.
- Usuários: todos os níveis de usuário.

RF010 - Confirmação de cancelamento de agendamento: exibe uma mensagem de confirmação ao usuário após o cancelamento do agendamento.
- Dados necessários: id do agendamento.
- Usuários: todos os níveis de usuário.

RF011 - Visualização do histórico de serviços: permite que os usuários visualizem o histórico de serviços realizados.
- Dados necessários: id do usuário.
- Usuários: todos os níveis de usuário.

RF012 - Exibição de detalhes de serviços: exibe os detalhes dos serviços, incluindo nome do cliente, data do serviço, tipo de serviço realizado e produtos utilizados.
- Dados necessários: id do serviço.
- Usuários: todos os níveis de usuário.

RF013 - Visualização do valor pago por serviços: permite que os usuários visualizem o valor pago por cada serviço.
- Dados necessários: id do serviço.
- Usuários: todos os níveis de usuário.

RF014 - Solicitação de compra de produtos: permite que os funcionários solicitem a compra de produtos para o estoque.
- Dados necessários: id do funcionário, id do produto, quantidade.
- Usuários: funcionários.

RF015 - Registro de solicitações de compra: registra as solicitações de compra de produtos realizadas pelos funcionários.
- Dados necessários: id da solicitação, id do funcionário, id do produto, quantidade.
- Usuários: administradores.

RF016 - Notificação de solicitações de compra: notifica o administrador sobre as solicitações de compra de produtos.
- Dados necessários: id da solicitação.
- Usuários: administradores.

RF017 - Gerenciamento de estoque: permite que o administrador gerencie o estoque de produtos.
- Dados necessários: id do produto, quantidade.
- Usuários: administradores.

RF018 - Cadastro de produtos: permite que o administrador cadastre novos produtos no estoque.
- Dados necessários: nome do produto, descrição, quantidade.
- Usuários: administradores.

RF019 - Atualização de produtos: permite que o administrador atualize as informações dos produtos no estoque.
- Dados necessários: id do produto, nome do produto, descrição, quantidade.
- Usuários: administradores.

RF020 - Remoção de produtos: permite que o administrador remova produtos do estoque.
- Dados necessários: id do produto.
- Usuários: administradores.

RF021 - Definição de comissões: permite que o administrador defina as porcentagens de comissão para cada serviço e profissional.
- Dados necessários: id do serviço, id do profissional, porcentagem de comissão.
- Usuários: administradores.

RF022 - Cálculo de comissões: calcula automaticamente as comissões a serem pagas aos profissionais.
- Dados necessários: id do serviço, id do profissional, valor do serviço.
- Usuários: administradores.

RF023 - Geração de relatórios de comissão: gera relatórios de comissões a serem pagas aos profissionais.
- Dados necessários: id do profissional.
- Usuários: administradores.

RF024 - Envio de lembretes de agendamento: envia lembretes aos clientes sobre os agendamentos futuros.
- Dados necessários: id do agendamento, data e hora do agendamento, detalhes do serviço.
- Usuários: clientes.

RF025 - Gerenciamento financeiro: permite ao administrador gerenciar as finanças da clínica.
- Dados necessários: N/A.
- Usuários: administradores.

RF026 - Registro de pagamentos: registra os pagamentos recebidos dos clientes.
- Dados necessários: id do cliente, id do serviço, valor pago.
- Usuários: administradores.

RF027 - Registro de valores pagos por serviço: registra os valores pagos por cada serviço no histórico de serviços do cliente.
- Dados necessários: id do cliente, id do serviço, valor pago.
- Usuários: administradores.

RF028 - Geração de relatórios financeiros: gera relatórios financeiros, incluindo o faturamento mensal da clínica, despesas e lucro.
- Dados necessários: N/A.
- Usuários: administradores.

RF029 - Envio de detalhes de agendamento: envia mensagens de texto ou e-mails aos clientes com os detalhes do serviço agendado e a data e hora do agendamento.
- Dados necessários: id do agendamento, data e hora do agendamento, detalhes do serviço.
- Usuários: clientes.
