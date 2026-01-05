\# Requisitos Funcionais – Projeto Amazon E-commerce

\#\# 1\. Objetivo  
Este documento descreve os requisitos funcionais identificados durante a análise e os testes do fluxo de compra do e-commerce da Amazon.    
Os requisitos foram levantados com base no comportamento observado do sistema em ambiente de produção.

\---

\#\# 2\. Escopo  
Este documento contempla os seguintes fluxos:  
\- Busca de produtos  
\- Visualização e seleção de produtos  
\- Carrinho de compras  
\- Checkout (parcial, sem finalização da compra)

\---

\#\# 3\. Requisitos Funcionais

\#\#\# 3.1 Busca

RF01 — O sistema deve permitir que o usuário busque produtos pelo nome utilizando a barra de busca    
RF02 — O sistema deve permitir que o usuário filtre os resultados da busca    
RF03 — O sistema deve permitir que o usuário clique em um produto listado nos resultados    
RF04 — O sistema deve direcionar o usuário para a página de detalhes do produto selecionado  

\---

\#\#\# 3.2 Produto

RF05 — O sistema deve exibir os detalhes do produto (nome, preço, imagens, avaliações e disponibilidade)    
RF06 — O sistema deve permitir a seleção de variações do produto, quando disponíveis (cor, tamanho, memória, etc.)    
RF07 — O sistema deve exibir opções de outros vendedores para o mesmo produto, quando aplicável    
RF08 — O sistema deve exibir o preço do produto por vendedor    
RF09 — O sistema deve exibir o valor do frete associado a cada vendedor    
RF10 — O sistema deve permitir a alteração da quantidade antes de adicionar o produto ao carrinho    
RF11 — O sistema deve permitir a adição do produto ao carrinho quando disponível  

\---

\#\#\# 3.3 Carrinho

RF12 — O sistema deve permitir o acesso ao carrinho por meio do ícone correspondente    
RF13 — O sistema deve direcionar o usuário para a página do carrinho    
RF14 — O sistema deve exibir os produtos adicionados ao carrinho    
RF15 — O sistema deve exibir a quantidade de cada produto no carrinho    
RF16 — O sistema deve permitir a alteração da quantidade dos produtos no carrinho    
RF17 — O sistema deve exibir o subtotal dos itens adicionados    
RF18 — O sistema pode exibir mensagens informativas relacionadas a frete ou elegibilidade    
RF19 — O sistema deve permitir que o usuário avance para o checkout a partir do carrinho  

\---

\#\#\# 3.4 Checkout

RF20 — O sistema deve exigir autenticação do usuário para acesso ao checkout    
RF21 — O sistema deve permitir a seleção ou cadastro de endereço de entrega    
RF22 — O sistema deve validar a compatibilidade do endereço com os produtos selecionados    
RF23 — O sistema deve permitir a seleção do método de pagamento    
RF24 — O sistema deve exigir a seleção obrigatória de uma opção de frete    
RF25 — O sistema deve permitir o avanço pelas etapas do checkout até a confirmação do pedido    
\> Nota: a finalização real da compra está fora do escopo de testes deste projeto.

\---

\#\# 4\. Observações  
\- Os requisitos foram inferidos a partir de testes do tipo caixa-preta.  
\- Não houve acesso à documentação interna da plataforma.  
\- Comportamentos específicos estão documentados nos relatórios de teste, observações e bug report.

\---

\#\# 5\. Documentos Relacionados  
\- Plano de Teste  
\- Cenários de Teste  
\- Casos de Teste  
\- Test Report  
\- Bug Report  
\- Test Observations  
