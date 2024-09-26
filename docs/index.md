<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Softwares para o suporte da demanda (Pizza-Express)
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Caio Takehiro Magnoli Igari
* João Pedro Gonzaga
* Felipe Berthoux de Oliveira Souza


# Descrição do Projeto

Contexto
A Pizza-Express, uma rede de 40 lojas de fast-food, enfrenta uma significativa queda de 30% em suas vendas devido à ineficiência no serviço de entrega. Para competir com um concorrente que oferece entregas em 30 minutos, a Pizza-Express planeja desenvolver um novo sistema de software que otimize sua operação de entrega, com o objetivo de reduzir o tempo de entrega para menos de 30 minutos.

Objetivos
Criar um sistema que localize a loja Pizza-Express mais próxima do cliente.
Implementar um sistema de atendimento ao pedido que permita a coleta e processamento ágil de pedidos.
Estabelecer uma infraestrutura de entrega que possibilite a entrega em 10 a 15 minutos.
Escopo do Projeto
O projeto será dividido em duas partes principais:

Sistema de Atendimento ao Pedido: Gerenciar o recebimento e processamento dos pedidos, além de localizar a loja mais próxima.
Sistema de Operações da Fábrica de Pizzas: Controlar a produção e logística das entregas.


# Análise de Requisitos Funcionais e Não-Funcionais

Requisitos Funcionais do Sistema de Atendimento ao Pedido:

RF1: O sistema deve permitir que o cliente faça pedidos online.
RF2: O sistema deve identificar a localização do cliente utilizando GPS.
RF3: O sistema deve buscar a loja Pizza-Express mais próxima.
RF4: O sistema deve processar o pedido e confirmar a entrega.
RF5: O sistema deve enviar notificações ao cliente sobre o status do pedido.

Requisitos Funcionais do Sistema de Operações da Fábrica de Pizzas:

RF6: O sistema deve gerenciar o estoque de ingredientes.
RF7: O sistema deve monitorar o tempo de preparo das pizzas.
RF8: O sistema deve coordenar a logística de entrega.

Análise de Requisitos Não-Funcionais

Desempenho:
RNF1: O sistema deve processar pedidos em até 2 segundos.
RNF2: O tempo de entrega deve ser de no máximo 15 minutos.

Usabilidade:
RNF3: O sistema deve ter uma interface amigável e intuitiva para usuários.
RNF4: O sistema deve ser acessível em dispositivos móveis.

Segurança:
RNF5: O sistema deve garantir a proteção dos dados pessoais dos clientes.
RNF6: O sistema deve implementar autenticação para acesso administrativo.

Escalabilidade:
RNF7: O sistema deve suportar aumento no número de pedidos simultâneos.

# Diagrama de Atividades

*&lt;Diagrama para visualizer as pessoas das áreas de negócios e de desenvolvimento de uma organização para entender o processo e comportamento.&gt;*

# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

Descrição dos Casos de Uso
Caso de Uso: Fazer Pedido
Ator Principal: Cliente
Pré-condições: O cliente deve estar registrado no sistema.
Fluxo Principal:
O cliente acessa o aplicativo.
O cliente escolhe os itens do menu.
O cliente confirma o pedido.
O sistema processa o pedido e localiza a loja mais próxima.
O cliente recebe confirmação do pedido.
Caso de Uso: Processar Entrega
Ator Principal: Funcionário da Loja
Pré-condições: O pedido deve ter sido recebido.
Fluxo Principal:
O funcionário recebe o pedido.
O funcionário prepara a pizza.
O funcionário organiza a entrega.
O sistema atualiza o status do pedido para "em entrega".


# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

Referências
Pressman, R. S. (2014). Software Engineering: A Practitioner's Approach. McGraw-Hill.
Sommerville, I. (2011). Software Engineering. Addison-Wesley.
UML Distilled: A Brief Guide to the Standard Object Modeling Language, Martin Fowler.
