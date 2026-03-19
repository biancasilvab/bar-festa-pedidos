## Bar da Festa - Sistema de Pedidos <br>
Um sistema interativo e responsivo para gestão de pedidos de drinks em festas ou eventos. O projeto foi desenvolvido como uma Single Page Application (SPA) utilizando React de forma simplificada, rodando diretamente no navegador.

## Funcionalidades
O sistema possui duas interfaces principais baseadas em perfis de usuário: <br>
• O cliente: <br>
>> •Fazer Pedido: O usuário insere seu nome e escolhe um drink do cardápio (Morango, Uva com Hortelã, Limão ou Abacaxi com Hortelã). <br>
>> •Acompanhamento Real-time: Visualização imediata do status do pedido (Pendente ou Concluído). <br>


• O barman (Administração): <br>
>> •Modo Barman: Acesso protegido por senha para gerenciar a fila. <br>
>> •Concluir Pedidos: Transfere pedidos da lista de "Pendentes" para "Concluídos". <br>
>> •Remover Pedidos: Limpeza da lista de pedidos já entregues. <br>

## Tecnologias Utilizadas
Este projeto foi construído para ser leve e não requer instalação de dependências externas (Node/NPM): <br>
• **React 18**: Biblioteca principal para a interface e lógica de estado. <br>
• **Babel**: Utilizado para transpilar o código JSX em tempo real no navegador. <br>
• **CSS3 (Custom Styles)**: Estilização manual inspirada no framework Tailwind para um visual moderno e limpo. <br>
• **Hooks (useState, useCallback)**: Para gerenciamento eficiente de estados e performance. <br>

## Como Executar
Por ser um arquivo único de HTML, a execução é extremamente simples: <br>

1.Faça o download ou copie o código do arquivo ```index.html.``` <br>
2.Abra o arquivo diretamente em qualquer navegador de sua preferência. <br>
3.Nota: É necessário ter conexão com a internet, pois o navegador precisará baixar as bibliotecas do React e Babel via CDN. <br>

## Acesso de Administrador
Para testar as funções de conclusão e remoção de pedidos: <br>

Botão: Clique em "Entrar como Barman". <br>
Senha: barman123 <br>

## Estrutura do Código
Estado Centralizado: A lista de pedidos (orders) é o "coração" da aplicação, ditando o que aparece em cada coluna. <br>
Diferenciação Visual: Uso de cores (Laranja para pendente, Verde para concluído) para facilitar a leitura rápida em ambientes de festa. <br>
Segurança Simples: Implementação de um prompt de senha para alternar o estado de visualização do admin. <br>

## Nota do desnvolvedor
Esse sistema foi projetado para teste.
