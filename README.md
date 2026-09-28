# Rede Raízes do Nordeste

Protótipo de uma aplicação web desenvolvido para o estudo de caso **“Rede Raízes do Nordeste”**, realizado na disciplina de **Projeto Multidisciplinar da UNINTER**.

## Sobre o projeto

A **Rede Raízes do Nordeste** é uma rede fictícia de lanchonetes com foco em produtos e sabores regionais. A proposta do projeto é apresentar uma solução digital que possa facilitar a experiência dos clientes e, ao mesmo tempo, representar algumas necessidades comuns de uma operação de atendimento.

O protótipo permite simular toda a jornada de um cliente, começando pela escolha da unidade, passando pela consulta do cardápio e montagem do pedido, até a finalização e acompanhamento do pedido.

Também foram incluídos recursos relacionados a **fidelidade, privacidade de dados (LGPD)** e uma simulação de integração com um serviço externo de pagamento.

---

## Identificação acadêmica

| Informação      | Detalhes                                  |
| --------------- | ----------------------------------------- |
| **Aluno**       | Wenderson Leandro Alves Dos Santos        |
| **RU**          | 4708343                                   |
| **Curso**       | CST Análise e Desenvolvimento de Sistemas |
| **Instituição** | UNINTER                                   |

---

## Tecnologias utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

* React
* Vite
* JavaScript
* HTML5
* CSS3
* Layout responsivo
* Dados simulados em `src/data.js`

---

## Estrutura do projeto

A aplicação foi organizada da seguinte maneira:

```text
src/
├── components/
├── app.jsx
├── data.js
├── main.jsx
├── styles.css
└── utils.js
```

Os componentes ficam separados para facilitar a manutenção e reutilização das partes da interface. Os dados utilizados pelo protótipo ficam concentrados no arquivo `data.js`.

---

## Como executar o projeto

Para utilizar o projeto localmente, primeiro é necessário instalar as dependências.

No terminal, dentro da pasta do projeto, execute:

```bash
npm install
```

Depois da instalação, inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O Vite irá informar no terminal o endereço para acessar a aplicação. Normalmente, será algo semelhante a:

```text
http://localhost:5173
```

---

## Funcionalidades

### Atendimento ao cliente

O protótipo possui um fluxo completo para simular a experiência de compra:

* Página inicial da Rede Raízes do Nordeste;
* Escolha da unidade;
* Cardápio específico de cada unidade;
* Filtros para facilitar a consulta dos produtos;
* Visualização das informações dos produtos;
* Adição de produtos ao carrinho;
* Alteração da quantidade dos itens;
* Remoção de produtos;
* Simulação do processo de checkout;
* Acompanhamento do andamento do pedido.

### Programa de fidelidade

Também foi criada uma área para representar um programa de fidelização dos clientes.

Nela é possível visualizar uma quantidade fictícia de pontos e simular como esse recurso poderia fazer parte da experiência do cliente.

### LGPD e privacidade

O projeto possui uma simulação de consentimento relacionada à **LGPD**.

Como se trata de um protótipo acadêmico, nenhum dado pessoal real é coletado ou enviado para serviços externos.

---

## Decisões utilizadas no desenvolvimento

A aplicação foi desenvolvida com **React e Vite**, principalmente para facilitar a divisão da interface em componentes e deixar o projeto mais organizado.

Para manter o protótipo simples, não foi utilizado um sistema de rotas externo. A navegação entre algumas partes da aplicação é feita de maneira simplificada utilizando âncoras e controle interno do front-end.

As informações sobre unidades, produtos e outros dados utilizados na aplicação foram colocadas no arquivo:

```text
src/data.js
```

Dessa forma, é possível alterar ou adicionar informações sem precisar modificar várias partes do código.

O pagamento também não é realizado de verdade. O sistema apenas representa como poderia funcionar uma integração com um serviço externo de pagamento.

A parte relacionada à LGPD segue a mesma ideia: o consentimento é apenas demonstrativo e não existe armazenamento de dados pessoais reais.

---

## Requisitos desenvolvidos

Durante a construção do protótipo foram implementados os principais requisitos propostos para o projeto:

* Interface adaptada para computador e celular;
* Componentes reutilizáveis;
* Organização dos dados simulados;
* Seleção de diferentes unidades;
* Cardápios específicos por unidade;
* Montagem e alteração do pedido;
* Finalização do pedido;
* Acompanhamento do status;
* Programa de fidelidade;
* Simulação de consentimento LGPD;
* Simulação de pagamento externo;
* Documentação das principais decisões do projeto.

---

## Limitações do projeto

Por ser um protótipo desenvolvido para fins acadêmicos, algumas funcionalidades não possuem uma implementação completa de produção.

Entre as principais limitações estão:

* Não existe um back-end conectado à aplicação;
* Não há banco de dados;
* Não existe sistema de login ou autenticação;
* Os dados são simulados localmente;
* O carrinho funciona somente durante a utilização da aplicação;
* O pagamento não é realizado de forma real;
* O acompanhamento do pedido é simulado pelo front-end;
* Não existe integração real com serviços externos;
* Questões como escalabilidade, segurança e alta disponibilidade foram consideradas apenas de forma conceitual.

---

## Testes recomendados

Para testar o funcionamento do protótipo, é possível seguir alguns cenários:

1. Abrir a página inicial e navegar pelas diferentes áreas;
2. Testar a aplicação em computador e celular;
3. Selecionar uma unidade diferente;
4. Conferir se o cardápio é alterado de acordo com a unidade escolhida;
5. Adicionar produtos ao carrinho;
6. Aumentar ou diminuir a quantidade dos produtos;
7. Remover produtos do carrinho;
8. Finalizar um pedido;
9. Acompanhar as etapas do pedido;
10. Simular uma situação de pagamento aprovado ou recusado;
11. Verificar a área de fidelidade;
12. Testar o consentimento relacionado à LGPD.

---

## Considerações finais

O projeto **Rede Raízes do Nordeste** foi desenvolvido como uma representação de como uma rede de lanchonetes poderia utilizar recursos digitais para melhorar o atendimento e organizar a experiência de compra dos seus clientes.

Apesar de não possuir uma estrutura completa de produção, como servidor, banco de dados e integrações reais, o protótipo permite visualizar o funcionamento das principais etapas do sistema e demonstra a aplicação dos conceitos estudados durante o curso.

O projeto foi desenvolvido exclusivamente para **fins acadêmicos**, como parte das atividades da disciplina de **Projeto Multidisciplinar da UNINTER**.
