# Evidências dos Testes e Correções — PIT II

**Aluno:** Markus Vinicius Melo Porto  
**RGM:** 33238588  
**Projeto:** Aplicativo de loja virtual de cupcakes gourmet

## 1. Mensagens de confirmação e erro
**Problema identificado:** o retorno após adicionar produtos e ao tentar finalizar o pedido apresentava pouco destaque.

**Correção aplicada:** foram criados estilos diferentes para mensagens de sucesso e de erro. A confirmação de inclusão no carrinho passou a informar explicitamente que o produto foi adicionado com sucesso.

**Evidência:** alteração registrada no arquivo `index.html`, nas classes `msg ok` e `msg erro`.

## 2. Validação dos campos obrigatórios
**Problema identificado:** a orientação ao usuário era pouco específica quando dados obrigatórios estavam ausentes.

**Correção aplicada:** o sistema passou a verificar nome, telefone, endereço, pagamento e entrega, informando quais campos precisam ser preenchidos.

**Evidência:** lógica de validação adicionada ao evento de finalização do formulário no `index.html`.

## 3. Acompanhamento do pedido
**Problema identificado:** o status apresentava apenas a etapa inicial.

**Correção aplicada:** foi incluída uma visualização simplificada das etapas: Pedido recebido, Pagamento confirmado, Em preparo, Saiu para entrega e Concluído.

**Evidência:** componente de etapas acrescentado na confirmação do pedido.

## 4. Responsividade
**Problema identificado:** em telas pequenas, campos e botões ficavam muito próximos.

**Correção aplicada:** foram aumentados espaçamentos e áreas de toque no formulário, além de ajustes de responsividade para melhorar a leitura e a interação.

**Evidência:** regras adicionais no media query para telas de até 600 pixels.

## 5. Área administrativa
**Problema identificado:** a visão administrativa apresentava informações muito resumidas.

**Correção aplicada:** foi acrescentada uma área de “Último pedido processado”, exibindo número do pedido, cliente, pagamento, entrega e status.

**Evidência:** nova seção administrativa e atualização dinâmica após a conclusão do pedido.

## Funcionalidades mantidas como evolução futura
- pagamento real integrado a instituições financeiras;
- autenticação de clientes e administradores;
- rastreamento real da entrega;
- persistência completa da interface administrativa;
- cadastro, edição e exclusão real de produtos pela interface;
- testes de carga com vários usuários simultâneos.
