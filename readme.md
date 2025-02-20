
# Projeto MVC

Este projeto consiste em uma representação MVC do nosso futuro projeto da escola de TI 



## Definição do Produto 
Nosso produto tem como objetivo ser uma plataforma digital que conecta usuários a chefs autônomos para serviços de culinária personalizada.
O foco é oferecer soluções flexíveis para eventos exclusivos ou para o planejamento de refeições diárias. 

### Objetivo
Proporcionar alternativas com foco na qualidade e na viabilidade para pessoas que precisam cozinhar mas possuem pouco

### Público-alvo
Pessoas que possuem pouco tempo para cozinhar e precisam de serviços de culinária privados tanto para eventos específicos quanto para o dia a dia

### Contexto de uso
O uso foca em otimizar o tempo com a contratação de um chef autonomo em nossa plataforma.




## Requisitos do Sistema

### Requisitos Funcionais
1 - Cadastro e Login de Usuários:
- O usuário deve ser capaz de criar uma conta, fazer login e gerenciar suas informações (nome, e-mail, endereço, preferências alimentares, etc.).
- O chef também deve ter um processo de cadastro, onde ele pode adicionar suas especialidades culinárias, fotos de pratos e qualificações.

2 - Busca e Filtros de Chefs:
- O usuário pode buscar chefs por especialidade, tipo de cozinha (italiana, vegana, etc.), avaliações, preço e localização.
- O sistema deve permitir aplicar filtros de busca (ex: preço, experiência, tipo de comida).

3 - Avaliação e Feedback:
- O usuário deve poder avaliar a experiência com o chef após a refeição (pontuação de 1 a 5 estrelas, comentários, sugestões).
- O chef também pode dar feedback sobre a experiência, como as preferências do cliente e comportamento durante o atendimento.

4 - Gestão de Perfil de Chef:
- O chef deve ser capaz de atualizar seu perfil com fotos, descrição de sua especialidade, preços e disponibilidade.
- O chef pode ver o histórico de seus atendimentos.

5 - Gerenciamento de Pedidos:
- O sistema deve permitir que o chef visualize, aceite ou recuse pedidos.
- O usuário deve poder visualizar o histórico de pedidos, com informações sobre datas, status e detalhes.

### Requisitos Não Funcionais

1 - Segurança:
- O aplicativo deve usar criptografia de dados para proteger informações pessoais, como dados de pagamento e endereço.
- O sistema deve ter autenticação segura (ex: autenticação de dois fatores, senhas fortes).

2 - Desempenho:
- A plataforma deve ser capaz de suportar muitos usuários simultâneos (especialmente em horários de pico, como finais de semana).

3 - Escalabilidade:
- O sistema deve ser escalável para acomodar mais chefs, usuários e recursos à medida que o app cresce.
- A infraestrutura deve ser capaz de suportar a expansão para diferentes regiões.

4 - Compatibilidade:
- O aplicativo deve ser compatível com os sistemas operacionais móveis mais populares (iOS, Android).
- O layout e as funcionalidades devem ser adaptáveis a diferentes tamanhos de tela (celulares e tablets).

5 - Usabilidade:
- A interface do usuário (UI) deve ser intuitiva e fácil de usar, com uma navegação simples e clara.
- O design deve ser responsivo e garantir uma experiência consistente em diferentes dispositivos.

6 - Disponibilidade:
- O sistema deve estar disponível 99% do tempo, com o mínimo de tempo de inatividade planejada para manutenção.

### Restrições Técnicas
- IDEs: Vscode 
- Linguagem: TS
- Framework: NestJS + ReactNative
- SGBD: Postgres
- Versionamento: Git Flow
- Serviços Cloud: AWS


### Restrições Não-Técnicas
- Orçamento: Free-tier de Serviços Cloud até a expiração
- Requisitos Legais: LGPD e Convenções com a Legislação e Lojas Parceiras (appstore & play store) e termos e condições de uso padrão para uso da plataforma definida no aplicativo


## Necessidades de Stakeholders

### Clientes


### Chefs 


### Desenvolvedores


### Empresas Parceiras
## Risco do Projeto

## Riscos Operacionais

## Stack utilizada

**Front-end:** React, Redux, TailwindCSS

**Back-end:** Node, Express


## Tomadas de Decisões
## Organização da Arquitetura MVC
## Avaliação das Decisões
## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`API_KEY`

`ANOTHER_API_KEY`

## Autores

- [@octokatherine](https://www.github.com/octokatherine)

