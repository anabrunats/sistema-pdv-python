# Sistema de Ponto de Venda (PDV) em Python

Este é um sistema de **Ponto de Venda (PDV)** desenvolvido como um desafio acadêmico inteiramente em Python. O projeto simula o fluxo completo de uma venda comercial, desde o controle de estoque até o fechamento de caixa, aplicando regras de negócios reais como cálculo de comissões, impostos e geração de relatórios de desempenho.

## 🚀 Funcionalidades Implementadas

O sistema foi construído seguindo rigorosamente os seguintes requisitos de negócio:

- [x] **Cadastros Base:** Sistema de cadastro para Produtos (código, nome, valor, estoque), Clientes (código, nome) e Vendedores (código, nome).
- [x] **Validação de Venda:** Toda compra exige um cliente cadastrado e um vendedor responsável.
- [x] **Controle de Estoque Dinâmico:** O cliente pode incluir múltiplos itens na compra, desde que haja quantidade disponível em estoque. O estoque é atualizado automaticamente ao finalizar a venda.
- [x] **Emissão de Recibo:** Geração de cupom/recibo detalhado com valores individuais, totalizador da venda, data e identificação do vendedor.
- [x] **Regras Financeiras Automatizadas:**
  - Cálculo de **5% de comissão** para o vendedor sobre o valor de cada venda finalizada.
  - Cálculo de **25% de imposto** sobre o total das vendas finalizadas.
- [x] **Módulo de Relatórios:** Gerador de relatórios por período, consolidando produtos vendidos, total faturado, impostos retidos e comissão por vendedor.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Paradigma:** Programação Estrutural (Funções, Listas e Dicionários)
- **Persistência de dados:** Execução em memória (Estruturas de dados nativas do Python)
