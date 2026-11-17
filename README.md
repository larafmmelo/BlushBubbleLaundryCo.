# Blush Bubble Laundry Co.

Site de portfólio para uma lavanderia fictícia com coleta express, lavagem e secagem. A página mostra um fluxo completo de cliente: escolha de pacote com cálculo de preço por peso, rastreamento de pedido, agendamento de coleta, assinatura, guia de cuidados com tecidos e depoimentos.

> Todos os dados (nome da empresa, preços, depoimentos, pedido de exemplo e telefone) são fictícios.

## Funcionalidades

1. **Calculadora de peso:** um slider de 1 a 20 kg recalcula o preço. Acima de 8 kg, cada quilo extra tem um valor próprio, que muda conforme o pacote escolhido.
2. **Rastreamento de pedido:** digite o código **0427** para ver a linha do tempo (Coleta, Lavagem, Secagem, Entrega). Qualquer outro código mostra uma mensagem de "não encontrado".
3. **Agendamento:** escolha dia e horário e confirme a coleta. A confirmação aparece na tela.
4. **Antes e depois:** um slider revela a diferença entre as duas situações usando `clip-path`.
5. **Depoimentos:** navegação com setas entre três avaliações de exemplo.
6. **Assinatura:** alternância entre plano mensal (R$ 89) e anual (R$ 71 por mês, com 20% de desconto).
7. **Guia de tecidos:** ao escolher algodão, lã, seda ou jeans, a página mostra a temperatura e a secagem indicadas.

Também há animação de fundo com bolhas, que respeita a preferência de movimento reduzido do sistema operacional.

## Tecnologias

- **HTML5** semântico, com `section`, `nav`, `main`, `footer` e atributos de acessibilidade (`aria-label`, `aria-pressed`).
- **CSS3** com variáveis personalizadas (custom properties) para a paleta, layout com Flexbox e Grid, `clip-path`, `@keyframes` e media queries para celular.
- **JavaScript (ES6+)** puro, sem frameworks nem dependências. Usa um objeto de estado único e funções de renderização que atualizam o DOM.
- **Google Fonts:** *Playfair Display* para títulos e *Inter* para o texto.
