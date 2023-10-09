
Projeto coordenado pelos professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](https://github.com/WedleySilva/espaco-innovar/tree/main/docs)
-   [Backend](https://github.com/WedleySilva/backend-innovar)
-   [Frontend](https://github.com/WedleySilva/frontend-innovar-react-native)

# Sumário
- [Regras de Negócios](https://github.com/WedleySilva/espaco-innovar/blob/main/docs/business-rules.md)
- [Requisitos Funcionais](https://github.com/WedleySilva/espaco-innovar/blob/main/docs/functional-requirements.md)
- [Requisitos Não Funcionais](https://github.com/WedleySilva/espaco-innovar/blob/main/docs/non-functional-requirements.md)

# Situação Problema

A clínica Espaço Innovar é uma conceituada instituição no setor de beleza, com mais de 4 anos de operação, oferecendo serviços de alto padrão para seus clientes. Possui um time de profissionais competentes e equipamentos avançados, visando suprir todas as necessidades dos clientes.

Ao avaliar a situação atual da clínica Espaço Innovar, foi constatado que a secretária possui diversas responsabilidades que vão além do atendimento ao cliente e do agendamento dos serviços. Ela também é encarregada de monitorar o estoque de produtos e fazer pedidos quando necessário. No entanto, esse processo manual pode levar tempo e estar sujeito a erros, já que é exigido que a secretária memorize todos os produtos que precisam ser reabastecidos e compila uma lista manualmente.

A clínica carece também de um sistema para calcular as comissões dos profissionais, o que resulta no cálculo manual realizado pela secretária. Esse processo pode ocasionar erros e insatisfação entre os membros da equipe. Outro problema é a ausência de um sistema de lembretes para os clientes sobre agendamentos futuros, o que pode levar a esquecimentos e atrasos, afetando a imagem da empresa.

Apesar disso, é notável que a clínica possui um processo de atendimento eficiente, com marcações sendo realizadas através de agendamento prévio, pessoalmente ou por telefone. A secretária registra as informações em uma agenda física e confirma a disponibilidade dos profissionais para o horário solicitado. O cliente recebe uma confirmação por mensagem de texto ou email após o agendamento ser efetivado.

Durante o atendimento, o profissional preenche uma ficha com as informações do cliente e do serviço realizado. Essa ficha é arquivada pela secretária em um local separado por cliente. No final do dia, a secretária revisa as fichas preenchidas pelos profissionais e confirma se o pagamento foi realizado pelo cliente. Todas essas informações são armazenadas em uma planilha física que contém o histórico de serviços realizados por cada cliente, além dos valores pagos.

Em relação ao estoque, a clínica realiza uma contagem manual de produtos no final de cada mês, registrando os dados em uma planilha. Esta planilha é usada para solicitar a reposição de produtos. A clínica também controla seu caixa manualmente, com o fechamento do caixa sendo feito no final do dia. Este processo é demorado e propenso a erros, pois as informações precisam ser transcritas manualmente da planilha física para uma planilha no computador.

A clínica Espaço Innovar atende em média 15 clientes por dia, com um tempo médio de atendimento de 1 hora por cliente. A equipe é composta por quatro profissionais da área de estética, sendo dois especializados em tratamentos faciais e dois em tratamentos corporais.

Em resumo, a clínica Espaço Innovar possui um serviço ao cliente satisfatório, no entanto, ainda há a necessidade de melhorias nos processos internos, como a implementação de sistemas para gerenciamento de estoque, comissões e lembretes aos clientes sobre agendamentos futuros. Tais melhorias aumentariam a eficiência e reduziriam erros nos processos manuais.

# Proposta

Em resposta à situação da clínica Espaço Innovar, propomos a criação de um sistema de gerenciamento para otimizar os processos internos e aumentar a eficiência da clínica. Este software focará em fornecer um conjunto de funcionalidades para gerenciamento de estoque, comissões e agendamentos.

Os níveis de usuários do sistema serão: administrador (gerente da clínica) e funcionários (secretária e profissionais da área de estética). O administrador terá acesso total a todas as funcionalidades do sistema, enquanto os funcionários terão acesso limitado às suas respectivas áreas de trabalho.

O sistema permitirá ao administrador gerenciar o estoque de produtos, desde a criação de uma lista de produtos em falta, ao registro de compras e controle de estoque. Os funcionários poderão solicitar a compra de produtos e registrar a utilização dos mesmos nos seus atendimentos.

O sistema também permitirá ao administrador gerenciar as comissões dos profissionais, estabelecendo as percentagens de comissão para cada serviço e profissional. O sistema fará o cálculo automático das comissões a serem pagas e poderá gerar relatórios para o administrador.

Outra funcionalidade importante será a de agendamento de serviços e o envio de lembretes aos clientes sobre agendamentos futuros. A secretária poderá agendar os serviços dos clientes, verificar a disponibilidade dos profissionais e enviar lembretes aos clientes via mensagem de texto ou email. Os profissionais poderão verificar a sua própria agenda e definir os horários de atendimento. Além disso, o sistema poderá gerar relatórios de agendamentos e cancelamentos de serviços.

Por fim, o sistema permitirá a gestão financeira da clínica, incluindo o controle de caixa, registro de pagamentos e emissão de relatórios financeiros.

Com a implementação deste sistema de gerenciamento, a clínica Espaço Innovar terá uma ferramenta eficiente para melhorar os seus processos internos, aumentar a eficiência e reduzir erros. O sistema proporcionará mais agilidade e segurança na gestão de estoque, comissões e agendamentos, além de permitir uma gestão financeira mais organizada e precisa.
