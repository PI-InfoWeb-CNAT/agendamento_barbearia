# Documento de Visão

## Sistema de Agendamento de Serviços

### Histórico da Revisão 

|  Data  | Versão | Descrição | Autor |
|:-------|:-------|:----------|:------|
| 25/05/2022 |  **`1.00`** | Versão Inicial  | Rafael Fernandes |
| 25/05/2022 |  **`1.00`** | Versão Inicial  | Maria Vitória |
| 25/05/2022 |  **`1.00`** | Versão Inicial  | Antony Gabriel |
| 25/05/2022 |  **`1.00`** | Versão Inicial  | Luís Gustavo |
| 25/05/2022 |  **`1.00`** | Versão Inicial  | Samuel Lucas |
| 25/05/2022 |  **`1.00`** | Versão Inicial  | José Jefferson |



### 1. Objetivo do Projeto 

O projeto da Barbearia do Matheus tem como objetivo prover uma solução simples e dinâmica para o atendimento dos clientes do estabelecimento.

### 2. Descrição do Problema 

|         __        | __   |
|:------------------|:-----|
| **_O problema_**    | a dificuldade do Mateus de administrar a barbearia, e dos clientes de serem atendidos. |
| **_afetando_**      | O barbeiro Mateus, pois sendo o unico funcionario do estabelecimento, ele seria o mais interessado na automação e organização de seu serviço. Também afetaria os cliente, pela dificuldade que eles passam em marcar os seus serviços. |
| **_cujo impacto é_**| A dificuldade na administração do serviço para o usuário, assim gerando falta de alcance, a perda de clientes, limitando a margem de lucro e podendo acarretar em problemas financeiros.  |
| **_uma boa solução seria_** |Um site web que permita os clientes ver os serviços ofertados pela barbearia; marcar, confirmar e cancelar os próprios cortes, e ver os horarios disponíveis. E ao Mateus gerenciar serviços, atendimentos e cadastros.|




### 3. Descrição dos Usuários

| Nome | Descrição | Responsabilidades |
|:---  |:--- |:--- |
| Administrador/Funcionário  | É o dono e o único funcionário da barbearia, a pessoa que tomará conta do site e realizará os serviços | Gerenciar a agenda de atendimentos, de serviços e gerenciar o cadastro dos clientes e funcionários.  |
| Cliente | O consumidor da barbearia e usuário do site | gerenciar a própria agenda, gerenciar o próprio cadastro, consultar os serviços e horários disponíveis |

### 4. Descrição do Ambiente dos Usuários

Atualmente, se surgiu a necessidade de muitas vezes entrar em contato com uma pessoa específica para se realizar um determinado serviço, porém graças as novas tecnologias que nasceram nesce século, não se é mais preciso realizar este contato cara a cara. 

É muito mais prático fazer este contato por meio de um computador, pois dessa forma, o cliente não precisa realizar viagem alguma, para muitas vezes ser recebido com uma recusa.

Esta é a ideia central do nosso sistema, arranjar uma forma mais simples de fazer esta operação, além de facilitar a organização do negócio como um todo para o profissional; agendando, confirmando, especifícando e confirmando serviços.

### 5. Principais Necessidades dos Usuários

Para o administrador, sua principal necessidade é de conseguir organizar e consultar sua lista de agendamentos para cortes da forma mais eficiente possível.

Para os clientes é conseguir agendar, confirmar ou cancelar os cortes de forma prática e rápida.

### 6.	Alternativas Concorrentes

Alternativas concorrentes seriam as redes sociais num geral, como whatsapp ou instagram, pois nelas o cliente poderia entrar em contato com o profissional e agendar o serviço desejado. 

Porém essas plataformas não são específicas para esse tipo de interação, portanto seria bastante possível que com o número muito alto de pedidos, houvesse problemas no agendamento.

### 7.	Visão Geral do Produto

Basicamente nosso sistema procura a maior eficiencia do agendamento, confirmação, especificação e cancelamento do serviço. Além de promover o próprio negócio com o site.

### 8. Requisitos Funcionais

| Código | Nome | Descrição |
|:---  |:--- |:--- |
| RF01 | Entrar no sistema | Usuários devem logar no sistema para acessar as funcionalidades relacionadas ao agendamento |
| RF02 | Gerenciamento de Cadastro do Cliente | O cliente deve realizar o auto cadastramento, ele também pode editar os dados ou excluir o cadastro. O adm pode gerenciar o cadastro de todos os seus clientes.  |
| RF03 | Consulta de agendas | cliente consulta os horarios disponiveis em determinados dias, podendo escolher o horario mais adequado para o atendimento e a realização do serviço. |
| RF04 | Gerenciamento de Serviços |  Funcionário/adm mantém a relação de serviços prestados pela empresa ou profissional |
| RF05 | Gerenciamento da Agenda | Funcionário/adm registra os horários disponíveis de atendimento, confirma e cancela o agendamento de clientes |
| RF07 | Gerenciamento de Agendamento | Cliente consulta atendimentos agendados, podendo cancelar, confirmar ou editar um agendamento |

### 9. Requisitos Não-funcionais

 |Código | Nome | Descrição | Categoria | Classificação|
|:---  |:--- |:--- |:--- |:--- |
| RNF01 | Design responsivo | O sistema deve adaptar-se a qualquer tamanho de tela de dispositivo, seja, computador, tablets ou smart phones. | Usabilidade| Obrigatório |
| RNF02 | Criptografia de dados| Senhas de usuários devem ser gravadas de forma criptografada no banco de dados. | Segurança | Obrigatório |
| RNF03 | Controle de acesso | Só usuários autenticados podem ter acesso ao sistema, com exceção ao auto cadastramento do usuário. | Segurança | Obrigatório |
| RNF04 | Tempo de resposta |A comunicação entre o servidor e o cliente deve ocorrer em tempo hábil | Performance | Desejável |
| RNF05 | Sistema Web | A aplicação deve ser um site. | Arquitetura | Obrigatório |
| RNF06 | Dados pessoais | Os clientes não devem visualizar dados de outros clientes (na agenda, por exemplo). | Privacidade | Obrigatório |
