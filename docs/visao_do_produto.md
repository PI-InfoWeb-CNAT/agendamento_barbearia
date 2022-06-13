# Documento de Visão

## Sistema de Agendamento de Serviços

### Histórico da Revisão 

|  Data  | Versão | Descrição | Autor |
|:-------|:-------|:----------|:------|
| 13/06/2022 |  **`1.00`** | Versão Inicial  | Rafael Fernandes |
| 13/06/2022 |  **`1.00`** | Versão Inicial  | Maria Vitória |
| 13/06/2022 |  **`1.00`** | Versão Inicial  | Antony Gabriel |
| 13/06/2022 |  **`1.00`** | Versão Inicial  | Luís Gustavo |
| 13/06/2022 |  **`1.00`** | Versão Inicial  | Samuel Lucas |
| 13/06/2022 |  **`1.00`** | Versão Inicial  | José Jefferson |



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
| Administrador  | Dono da barbearia | Gerenciar o cadastro dos clientes e funcionários, adicionar novos serviços.	  |
| Funcionario | A pessoa que realiza os serviços | Inserir os horários em que está disponível na agenda. |
| Usuário |  A pessoa que visita o site, não precisa ser cadastrado | O usuario é quem está visitando o site; está analisando se aquele estabelecimento será adequado para suas necessidades. Ele checará os cortes e horários disponíveis. |
| Cliente | Usuário logado | Ele será quem agendará os cortes baseado na agenda do funcionário. |

### 4. Descrição do Ambiente dos Usuários

Atualmente, se surgiu a necessidade de muitas vezes entrar em contato com uma pessoa específica para se realizar um determinado serviço, porém graças as novas tecnologias que nasceram no século passado, não se é mais preciso realizar este contato pessoalmente. 

É muito mais prático fazer este contato por meio de um computador, pois dessa forma, o cliente não precisa realizar viagem alguma, para muitas vezes ser recebido com uma recusa.

Esta é a ideia central do nosso sistema, arranjar uma forma mais simples de fazer esta operação, além de facilitar a organização do negócio como um todo para o profissional; agendando, confirmando, especifícando e confirmando serviços para a barbearia.

### 5. Principais Necessidades dos Usuários

Para o administrador, sua principal necessidade é manter o cadastro dos funcionarios para fazerem os serviços que ele manda.

Para o funcionário, sua principal obrigação será marcar os horarios em que ele estará disponível para os cortes, além de realizar os cortes em sí.

O cliente precisará encontrar bons profissionais com horários convenientes para ele.

### 6.	Alternativas Concorrentes

Alternativas concorrentes seriam as redes sociais num geral, como whatsapp ou instagram, pois nelas o cliente poderia entrar em contato com o profissional e agendar o serviço desejado. 

Porém essas plataformas não são específicas para esse tipo de interação, portanto seria bastante possível que com o número muito alto de pedidos, houvesse problemas no agendamento.

### 7.	Visão Geral do Produto

Basicamente nosso sistema procura a maior eficiencia do agendamento, confirmação, especificação e cancelamento do serviço. Além de promover o próprio negócio com o site.

### 8. Requisitos Funcionais

| Código | Nome | Descrição |
|:---  |:--- |:--- |
| RF01 | Visitar o sistema | O usuário visita o site, checa cortes, horários e serviços disponíveis, mas sem realizar agendamento algum. |
| RF02 | Cadastro do cliente | O usuário se cadastra no sistema, ele pode atualizar os dados já postos ou excluir o próprio cadastro. Assim podendo realizar os agendamentos.   |
| RF03 | Cadastrar funcionario | O administrador fica responsável por realizar o cadastro ou excluir o cadastro dos funcionários. |
| RF04 | Consulta de agendas |  O cliente consulta os horarios disponiveis em determinados dias, podendo escolher o horario mais adequado para o atendimento e a realização do serviço. |
| RF05 | Gerenciamento de Serviços | Adm mantém a relação de serviços prestados pela empresa ou profissional. |
| RF07 | Gerenciamento da Agenda | Funcionário registra os horários disponíveis de atendimento. |
| RF08 | Cadastro de atendimento | O cliente marca o corte no horário em que o funcionário está disponível |

### 9. Requisitos Não-funcionais

 |Código | Nome | Descrição | Categoria | Classificação|
|:---  |:--- |:--- |:--- |:--- |
| RNF01 | Design responsivo | O sistema deve adaptar-se a qualquer tamanho de tela de dispositivo, seja, computador, tablets ou smart phones. | Usabilidade| Obrigatório |
| RNF02 | Criptografia de dados| Senhas de usuários devem ser gravadas de forma criptografada no banco de dados. | Segurança | Obrigatório |
| RNF03 | Controle de acesso | Só usuários autenticados podem ter acesso ao sistema, com exceção ao auto cadastramento do usuário. | Segurança | Obrigatório |
| RNF04 | Tempo de resposta |A comunicação entre o servidor e o cliente deve ocorrer em tempo hábil | Performance | Desejável |
| RNF05 | Sistema Web | A aplicação deve ser um site. | Arquitetura | Obrigatório |
| RNF06 | Dados pessoais | Os clientes não devem visualizar dados de outros clientes (na agenda, por exemplo). | Privacidade | Obrigatório |
