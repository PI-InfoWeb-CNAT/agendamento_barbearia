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
| **_O problema_**    | Marcar, cadastrar e checar os horários disponíveis para os serviços ofertados pela barbearia. |
| **_afetando_**      | O barbeiro Mateus, pois com o site, melhorará o agendamento de serviços, assim como a própria divulgação de seu negócio. |
| **_cujo impacto é_**| Dificuldade no agendamento do atendimento, dificuldade na contratação dos serviços, perda de clientes (empresas e profissionais) e não realização de serviços (clientes). |
| **_uma boa solução seria_** | Um sistema na Internet que permita aos profissionais e empresas informar a disponibilidade de horários de atendimento, facilitando o agendamento desses atendimentos para seus clientes. E para os clientes, um sistema que facilite a busca de profissionais e empresas para agendamento de um atendimento. |

### 3. Descrição dos Usuários

| Nome | Descrição | Responsabilidades |
|:---  |:--- |:--- |
| Administrador/Funcionário  | Realiza as atividades básicas para o início da operação do sistema, além de controlar a agenda de servoços | Mantém o cadastro de serviços; consulta a situação das agendas de serviços; mantém a agenda de atendimento; confirma o agendamento de clientes e exclui o agendamento de clientes |
| Cliente | Realiza as atividades relacionadas ao agendamento do serviço | Realiza o próprio cadastro no sistema; consulta a agenda de serviços e disponibilidades de atendimento; agenda um serviço; consulta seus agendamentos e cancela um agendamento |

### 4. Descrição do Ambiente dos Usuários

Atualmente, se surgiu a necessidade de muitas vezes entrar em contato com uma pessoa específica para se realizar um determinado serviço, porém graças as novas tecnologias que nasceram nesce século, não se é mais preciso realizar este contato cara a cara. 

É muito mais prático fazer este contato por meio de um computador, pois dessa forma, o cliente não precisa realizar viagem alguma, para muitas vezes ser recebido com uma recusa.

Esta é a ideia central do nosso sistema, arranjar uma forma mais simples de fazer esta operação, além de facilitar a organização do negócio como um todo para o profissional; agendando, confirmando, especifícando e confirmando serviços.

### 5. Principais Necessidades dos Usuários

Para o administrador, sua principal necessidade é de conseguir organizar e consultar sua lista de agendamentos para cortes da forma mais eficiente possível.

Para os clientes é conseguir agendar, confirmar ou cancelar os cortes de forma prática e rápida.

### 6.	Alternativas Concorrentes

Alternativas concorrentes serião as redes sociais num geral, como whatsapp ou instagram, pois nelas o cliente poderia entrar em contato com o profissional e agendar o serviço desejado. 

Porém essas plataformas não são específicas para esse tipo de interação, portanto seria bastante possível que com o número muito alto de agendamentos o profissional se confundir, e acabar esquecendo de um ou outro agendamento.
### 7.	Visão Geral do Produto

Basicamente nosso sistema procura a maior eficiencia do agendamento, confirmação, especificação e apagamento do serviço. Além de promover o próprio negócio com o site.

### 8. Requisitos Funcionais

| Código | Nome | Descrição |
|:---  |:--- |:--- |
| RF01 | Entrar no sistema | Usuários devem logar no sistema para acessar as funcionalidades relacionadas ao agendamento |
| RF02 | Gerenciamento de Serviços |  Funcionário mantém a relação de serviços prestados pela empresa ou profissional |
| RF03 | Gerenciamento da Agenda | Funcionário registra os horários disponíveis de atendimento, confirma e cancela o agendamento de clientes |
| RF04 | Cadastro de Clientes | Cliente deve realizar o auto cadastramento |
| RF05 | Consulta de Agendas | Cliente consulta agendas de atendimento dos serviços disponíveis, podendo agendar um serviço  |
| RF06 | Consulta de Agendamento | Cliente consulta atendimentos agendados, podendo cancelar um agendamento |


### 9. Requisitos Não-funcionais

 |Código | Nome | Descrição | Categoria | Classificação|
|:---  |:--- |:--- |:--- |:--- |
| RNF01 | Design responsivo | O sistema deve adaptar-se a qualquer tamanho de tela de dispositivo, seja, computador, tablets ou smart phones. | Usabilidade| Obrigatório |
| RNF02 | Criptografia de dados| Senhas de usuários devem ser gravadas de forma criptografada no banco de dados. | Segurança | Obrigatório |
| RNF03 | Controle de acesso | Só usuários autenticados podem ter acesso ao sistema, com exceção ao auto cadastramento do usuário. | Segurança | Obrigatório |
| RNF04 | Tempo de resposta |A comunicação entre o servidor e o cliente deve ocorrer em tempo hábil | Performance | Desejável |
| RNF05 | Sistema Web | A aplicação deve ser um site. | Arquitetura | Obrigatório |
| RNF06 | Dados pessoais | Os clientes não devem visualizar dados de outros clientes (na agenda, por exemplo). | Privacidade | Obrigatório |
