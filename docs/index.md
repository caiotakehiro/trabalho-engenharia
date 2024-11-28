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

O projeto envolve o desenvolvimento de um sistema de software para a cadeia de lojas Pizza-Express, que enfrenta desafios na área de entregas. A Pizza-Express, com 40 lojas, está perdendo 30% de seu faturamento devido à concorrência, que oferece entrega em 30 minutos, enquanto a Pizza-Express promete uma hora. Atualmente, a empresa usa sistemas computacionais apenas para funções administrativas e operacionais básicas, mas esses sistemas não auxiliam no gerenciamento das entregas. Portanto a ideia principal por traz desse projeto é criar um software que a capacidade de atender dois critéros identificar a loja Pizza-Express mais próxima do cliente para agilizar a entrega, também a solução deve incluir um sistema de suporte às operações das fábricas de pizza, que funcionam apenas como centros de preparação e entrega, sem atendimento ao cliente no local.

# Análise de Requisitos Funcionais e Não-Funcionais

<h4>Requisitos Funcionais do Sistema de Atendimento ao Pedido:</h4>

* O sistema deve permitir que o cliente faça pedidos online.
* O sistema deve identificar a localização do cliente utilizando GPS.
* O sistema deve buscar a loja Pizza-Express mais próxima.
* O sistema deve processar o pedido e confirmar a entrega.
* O sistema deve enviar notificações ao cliente sobre o status do pedido.

<h4>Requisitos Funcionais do Sistema de Operações da Fábrica de Pizzas:</h4>

 * O sistema deve permitir que os funcionários gerenciem os produtos da loja.
 * O sistema deve gerenciar o estoque de ingredientes.
 * O sistema deve monitorar o tempo de preparo das pizzas.
 * O sistema deve coordenar a logística de entrega.

<h4>Análise de Requisitos Não-Funcionais</h4>

Desempenho:
 * O sistema deve processar pedidos em até 2 segundos.
 * O tempo de entrega deve ser de no máximo 30 minutos.

Usabilidade:
* O sistema deve ter uma interface intuitiva.
* O sistema deve ser acessível em praticamente todos tipos dispositivos.

Segurança:
* O sistema deve garantir a proteção dos dados pessoais dos clientes.
* O sistema deve implementar autenticação para acesso administrativo.

Escalabilidade:
* O sistema deve suportar aumento no número de pedidos simultâneos.

# Diagrama de Atividades

![Untitled diagram-2024-10-03-142100](https://github.com/user-attachments/assets/baa19540-5a4c-426f-9b5f-0979601f9869)


# Diagrama de Casos de Uso

![373124980-a17ade7c-fe42-4f86-8be4-d4bb853ef874](https://github.com/user-attachments/assets/3652b666-4610-4f0d-8f3b-9d90c00859b6)


# Descrição dos Casos de Uso
![373150877-b33d7edb-083a-4037-a6fe-a892b2ee93bc](https://github.com/user-attachments/assets/2276a7dc-6258-4e22-bb9f-fd98219119b4)

---
![373150872-27058387-99df-4750-bfcb-aec161bce4d1](https://github.com/user-attachments/assets/f805880b-0a4f-4972-b0f2-9ddc8af27f5c)

---
![373150863-4d4b2a54-ca01-4733-8b6f-caee0badfad3](https://github.com/user-attachments/assets/a1a507cc-9a10-4b51-ac93-52c4d3f18d75)



# Diagrama de Sequência

![Captura de tela 2024-11-28 164330](https://github.com/user-attachments/assets/edf0933b-a994-4839-8c6b-b01c0a16123c)

# Diagrama de Classes

![390887257-ac662f12-87b7-42d4-8d58-2bfc4cb853a4](https://github.com/user-attachments/assets/d81ca75b-933d-45fb-ac46-e815e1b06383)


# Diagrama de Estados
![Complete_State_Diagram_Pizza_Express](https://github.com/user-attachments/assets/55a11858-ad7f-478f-8119-d4f01f9bf274)


# Diagrama de Implantação

![Complete_Deployment_Diagram_Pizza_Express](https://github.com/user-attachments/assets/e3841d87-6c70-4114-86dc-3d81dac9faf0)


# Referências

Referências
Pressman, R. S. (2014). Software Engineering: A Practitioner's Approach. McGraw-Hill.
Sommerville, I. (2011). Software Engineering. Addison-Wesley.
UML Distilled: A Brief Guide to the Standard Object Modeling Language, Martin Fowler.
