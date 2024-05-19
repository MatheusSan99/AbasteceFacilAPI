# CheckPriceAPI

## Visão Geral

A **CheckPriceAPI** é uma solução dedicada a fornecer informações de preços para diversos produtos na cidade de Joinville (futuramente outras cidades). O objetivo é facilitar o acesso a dados atualizados de preços para consumidores e empresas, permitindo uma tomada de decisão mais informada.

## Produtos Monitorados

Atualmente, a API cobre os seguintes produtos:

- **Gasolina** (Todos os tipos)
- **Cesta Básica** (futuro)
- **Peixes** (futuro)
- **Churrasco** (futuro)
- **Gás de Cozinha** (futuro)
- **Mercado** (futuro)

## Status do Projeto

Este projeto está em desenvolvimento contínuo e será integrado a um aplicativo móvel futuramente. Estou focado em garantir a precisão e a atualidade dos dados fornecidos, além de expandir as funcionalidades e a cobertura de produtos.

## Funcionalidades Planejadas

- **Atualização Diária de Preços**: Garantindo que os dados estejam sempre atualizados.
- **Filtros de Pesquisa**: Permitir que os usuários filtrem os preços por localidade específica dentro de Joinville.
- **Comparação de Preços**: Facilitar a comparação de preços entre diferentes fornecedores e locais.
- **Histórico de Preços**: Fornecer um histórico de preços para análise de tendências.

## Estrutura da API

A estrutura básica da API é organizada em endpoints que permitem o acesso e a manipulação dos dados de preços. A seguir, um exemplo de como será a estrutura de endpoints:

### Endpoints

#### Gasolina

- `GET /api/v1/prices/gas`
  - Retorna os preços de todos os tipos de gasolina.

#### Cesta Básica

- `GET /api/v1/prices/basic-needs`
  - Retorna os preços dos itens da cesta básica.

#### Peixes

- `GET /api/v1/prices/fish`
  - Retorna os preços de diferentes tipos de peixes.

#### Churrasco

- `GET /api/v1/prices/barbecue`
  - Retorna os preços dos itens relacionados a churrasco.

#### Gás de Cozinha

- `GET /api/v1/prices/cooking-gas`
  - Retorna os preços do gás de cozinha.

#### Mercado

- `GET /api/v1/prices/market`
  - Retorna os preços de diversos produtos de mercado.

## Uso Futuro

A CheckPriceAPI será integrada a um aplicativo móvel, proporcionando uma experiência de usuário aprimorada e acessível. O aplicativo permitirá:

- **Notificações de Preços**: Receber alertas quando os preços atingirem um valor desejado.
- **Favoritos**: Salvar produtos e preços favoritos para fácil acesso.
- **Avaliações de Consumidores**: Permitir que os usuários compartilhem suas experiências e avaliações dos fornecedores.

## Contribuição

Este projeto não está aberto publicamente a contribuições. Se você estiver interessado em colaborar, por favor, entre em contato

## Contato

Para mais informações ou dúvidas, entre em contato pelo email: **99matheussan@gmail.com**
