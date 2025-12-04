# Xfoods
App de delivery para todos os públicos



# Sistema de Delivery (Estilo iFood/UberEats)

Projeto desenvolvido por:
Cristhian Yamashiro Fernandes
Letícia Isabela Martins
Matheus Henrique de Oliveira
Murilo Piva

Descreveremos os principais componentes e funcionalidades do Sistema de Delivery, focando na perspectiva dos diferentes usuários.

Tema Central
Um sistema de plataforma digital que conecta Clientes a Restaurantes e Entregadores, facilitando a compra, o preparo e a entrega de alimentos de forma rápida e eficiente.

Neste projeto apresentaremos:
Histórias de Usuário
As histórias de usuário descrevem as necessidades de cada ator do sistema:

Casos de Uso
São os processos essenciais que o sistema deve suportar, como:

Cadastrar Restaurante:
Fazer Pedido:
Acompanhar Entrega:
Avaliar Serviço:
UML
Estes são os fluxos e modelos essenciais que devem ser representados nos diagramas UML.

Fluxo de Pedido
Atores: Cliente, Sistema, Restaurante.
Ações: Selecionar Itens 
→
 Revisar Carrinho 
→
 Confirmar Endereço 
→
 Realizar Pagamento 
→
 Restaurante Recebe 
→
 Restaurante Aceita


# Histórias de Usuário - Sistema de Delivery
*Ponto de Vista dos Clientes*:
Eu, como cliente, estou buscando um pedido de lanche para comer de forma rápida e fácil.
Como cliente, eu quero:

Pedir minha comida de forma simples e prática para garantir pedidos mais rápidos.

Poder cadastrar diversos endereços para pedir de onde eu estiver.

Filtrar os restaurantes por tipo de comida (como pizza, lanches, etc.) para agilizar o processo de compra.

Receber recomendações de restaurantes próximos para pedidos com entregas mais rápidas.

Ser notificado quando o pedido estiver a caminho para acompanhar em tempo real.

*Ponto de Vista dos Restaurantes*:
Eu, como restaurante, estou atendendo os pedidos do aplicativo para preparar e entregar rapidamente o pedido.
Como restaurante, eu quero:

Receber notificações de novos pedidos para prepará-los rapidamente.

Ter controle do horário de funcionamento para que nenhum pedido seja realizado fora do horário/dia de trabalho.

Ter a visualização dos pontos de atenção que clientes deixaram nas avaliações para melhorar o atendimento.

Poder gerenciar o status do pedido para retirada dos clientes ou dos entregadores.

*Ponto de Vista dos Entregadores*:
Eu, como entregador, quero aceitar entregas próximas para ganhar minha renda de forma mais rápida.
Como entregador, eu quero:

Receber notificações de restaurantes/entregas mais próximas para que o deslocamento seja melhor aproveitado.

Receber o mapa com rota dos endereços para avaliar o caminho mais vantajoso.

Notificar o cliente quando o pedido for coletado para que ele acompanhe a rota.

# Requisitos Não Funcionais (RNFs)
*1. Usabilidade*
O sistema deve ter uma Interface intuitiva, simples e rápida.

Permitir que o cliente realize seu pedido, o restaurante aceite e o motoboy entregue com poucos cliques ou toques.
Utilizar núcleos legíveis (cores e fontes) e botões com um bom tamanho em toda a aplicação.
*2. Confiabilidade*
O servidor deve garantir a retenção e a recuperação dos dados.

Deve armazenar todos os pedidos sem perder nenhum.
Em casos de erro, o sistema deve retornar de onde ocorreu o erro (mecanismo de recuperação).
*3. Performance*
Garantir alta velocidade e responsividade nas interações.

Proporcionar carregamentos rápidos ao entrar no aplicativo.
As ações de busca de restaurantes e outras interações dentro do aplicativo devem ser rápidas.
*4. Segurança*
Proteger informações sensíveis e transações financeiras.

O pagamento deve ser confiável e seguro, sem divulgar nenhuma informação do usuário.
É necessária autenticação para logar na conta ou realizar transações monetárias, prevenindo riscos legais.
*5. Compatibilidade*
Garantir o funcionamento em diversos ambientes tecnológicos.

Assegurar o funcionamento do aplicativo em diversos sistemas e aparelhos diferentes (multiplataforma).
Um cliente não pode ser impedido de realizar um pedido por não possuir um aparelho específico.
*6. Escalabilidade*
Garantir que a infraestrutura suporte o crescimento futuro.

O servidor deve ter a capacidade de suportar uma quantidade 'x' de usuários, de acordo com a especulação de usuários máximos feita pelo responsável.
*7. Manutenibilidade*
Facilitar a manutenção, correção e evolução do código.

O sistema deve ser organizado para que novas pessoas na equipe consigam entender com facilidade o código e o trabalho feito.
É essencial que todos os códigos sigam um padrão para facilitar futuras manutenções e evoluções.

# 5w's e 2w's


*What*
O que será desenvolvido?

Será desenvolvido o XFOODS, uma plataforma completa de delivery com:
App para clientes realizarem pedidos.
Sistema para restaurantes gerenciarem cardápio e entregas.
Dashboard administrativo com métricas.
Integração com pagamento online.
Sistema de entrega com rastreamento básico.What
Item statusDraft


*Why*
Por que o projeto será feito?

Para atender a alta demanda de pequenos restaurantes que não têm dinheiro para pagar taxas elevadas de plataformas como iFood, oferecendo:

Taxas menores.
Interface simples.
Mais autonomia para o restaurante.
Uma solução acessível de delivery local.


*Who*
Por quem será feito:

Desenvolvedor Backend | 2 |
API, banco, autenticação

Desenvolvedor Frontend | 2 |
App cliente + painel restaurante

Desenvolvedor Mobile | 1 |
Versão Android (WebView híbrida ou Flutter)

UI/UX Designer | 1 |
Layouts, telas, experiência do usuário

Infraestrutura / DevOps | 1 |
Deploy, servidor, CI/CD

Segurança | 1 |
Proteção de dados, segurança da API

Gerente de Projetos | 1 |
Cronograma, comunicação, entregas


*Where*
Onde o projeto será desenvolvido?

Repositório no GitHub
Comunicação via Discord / WhatsApp / Teams
Tarefas organizadas em GitHub Projects / Trello
Deploy em AWS ou Azure
Banco de dados em PostgreSQL
Serviços em contêiner com Docker


*When*
Quando será feito? (Cronograma com datas)

CRONOGRAMA OFICIAL DE ENTREGAS:

Planejamento | Documento 5W2H, requisitos iniciais |
05/12/2025

Arquitetura do Sistema | Diagramas, definição de banco e API |
12/12/2025

Protótipo UI/UX | Telas no Figma |
20/12/2025

Backend – Módulo 1 | Cadastro/login, restaurantes, produtos |
10/01/2026

Backend – Módulo 2 | Pedidos, entregadores, pagamentos |
25/01/2026

Frontend – Web Cliente | Tela inicial, cardápio, carrinho |
05/02/2026

Frontend – Restaurante | Dashboard, pedidos, relatórios |
20/02/2026

Mobile App | Versão Android funcional |
10/03/2026

Testes + QA | Testes unitários e integração |
20/03/2026

Deploy Final | Sist. rodando na AWS + documentação |
30/03/2026


*How*
Como será desenvolvido?

Metodologia:

Metodologia: Ágil (Scrum)
Sprints de 2 semanas
Reuniões rápidas diárias (15 minutos)
Entregas incrementais
Tecnologias:

Backend: Python (FastAPI) ou Node.js
Frontend Web: React
Mobile: Flutter
Banco: PostgreSQL
Infra: Docker + AWS EC2
Segurança: JWT, HTTPS, criptografia de senhas
Ferramentas:

GitHub (repositório e versionamento)
GitHub Projects (quadros)
Figma (design)
Postman (testes)
Trello opcional


*How much*
Quanto vai custar o projeto? (Estimativa para investidores)

Backend | 2 |
2 × R$ 7.000 = R$14.000

Frontend | 2 |
2 × R$ 6.500 = R$ 13.000

Mobile | 1 |
R$ 7.500

UI/UX | 1 |
R$ 5.500

DevOps | 1 |
R$ 6.500

Segurança | 1 |
R$ 7.000

Gerente | 1 |
R$ 8.000

Custo mensal total = R$ 61.500
Duração estimada: 4 meses
Custo final = R$ 246.000


*Designação de tarefas e responsabilidades*

A designação de tarefas e responsabilidades será feita a partir de características e facilidades de cada pessoa da equipe em :

Gerente de Projeto

Planejar cronograma
Acompanhar entregas
Comunicação com os investidores
Backend

Criar API
Gerenciar banco
Segurança dos dados
Frontend

Construção das telas
Integração com API
Mobile

Versão Android do app
UX/UI

Telas, protótipos, experiência do usuário
DevOps

Deploy, CI/CD
Docker, servidores
Segurança

Proteção contra invasões
Testes de vulnerabilidade


*Desenvolvimento da relação de equipe*

Como manter a equipe motivada e unida

Reuniões curtas e práticas
Reconhecimento de boas entregas
Bônus por tarefa concluída
Ambiente leve e respeitoso
Transparência total com metas
Premiações internas dadas pelos investidores
Demonstrações quinzenais
