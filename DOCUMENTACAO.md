# Documentação do Projeto — PIT II

## Identificação
**Aluno:** Markus Vinicius Melo Porto  
**RGM:** 33238588  
**Projeto:** Aplicativo de loja virtual de cupcakes gourmet

## 1. Continuidade da PIT I
A PIT I teve como foco a Situação-Problema 2, envolvendo a construção dos principais artefatos UML para representar o funcionamento de um aplicativo de venda de cupcakes.

Foram considerados:
- diagrama de caso de uso geral;
- casos de uso expandidos;
- diagrama de classes;
- diagrama de sequência.

Os principais atores identificados foram Cliente, Administrador, Entregador e Gateway de Pagamento.

## 2. Objetivo da PIT II
A PIT II dá continuidade à modelagem orientada a objetos, aproximando os artefatos UML da implementação de uma solução funcional.

O objetivo é representar o fluxo principal de compra, pagamento e entrega, além das principais entidades e regras previstas na PIT I.

## 3. Funcionalidades previstas
A aplicação deve permitir:
- consultar cupcakes;
- adicionar produtos ao carrinho;
- visualizar o resumo do pedido;
- informar dados do cliente;
- escolher uma forma de pagamento;
- selecionar a modalidade de entrega;
- finalizar o pedido;
- apresentar confirmação e status;
- representar funções administrativas de gerenciamento de produtos e pedidos.

## 4. Requisitos Funcionais
**RF01:** Exibir o catálogo de cupcakes.  
**RF02:** Permitir adicionar produtos ao carrinho.  
**RF03:** Calcular o total do pedido.  
**RF04:** Permitir o preenchimento dos dados do cliente.  
**RF05:** Permitir a escolha da forma de pagamento.  
**RF06:** Permitir a escolha da modalidade de entrega.  
**RF07:** Registrar e confirmar o pedido.  
**RF08:** Apresentar um status simplificado do pedido.  
**RF09:** Representar o gerenciamento de produtos e pedidos pelo administrador.

## 5. Requisitos Não Funcionais
- Interface responsiva.
- Navegação simples e objetiva.
- Mensagens claras de confirmação e validação.
- Organização do código por responsabilidades.
- Documentação mantida em repositório Git.

## 6. Relação com os artefatos UML
O diagrama de casos de uso orienta as funcionalidades implementadas.  
O caso de uso expandido de “Finalizar Pedido” orienta a sequência da finalização.  
O diagrama de classes fornece a base para entidades como Usuario, Cliente, Administrador, Produto, Cupcake, Carrinho, Pedido, ItemPedido, Pagamento e Entrega.  
O diagrama de sequência orienta a interação entre Cliente, Aplicativo, Carrinho, Pagamento, Gateway e Pedido.

## 7. Melhorias na PIT II
Nesta etapa, os elementos definidos na modelagem foram organizados em requisitos funcionais e não funcionais e serão representados por uma aplicação funcional.

## 8. Controle de versão
A documentação e o código da solução serão mantidos neste repositório GitHub, possibilitando acompanhar as alterações realizadas ao longo do desenvolvimento da PIT II.
