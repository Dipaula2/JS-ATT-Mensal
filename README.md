Update Date Script

Este repositório contém um script em JavaScript que altera dinamicamente a data exibida em uma página HTML. Ele foi desenvolvido para exibir o próximo mês nos últimos 5 dias do mês atual.

Funcionalidades
Exibe o nome do mês e o ano em português.
Automaticamente muda para o próximo mês se estiver nos últimos 5 dias do mês atual.
Ao chegar no final de dezembro, muda para janeiro do próximo ano.
Como funciona
O script faz o seguinte:

Obtém a data atual do sistema.
Define uma margem de 5 dias antes do final do mês para que o mês seguinte seja exibido.
Verifica se o dia atual está dentro dos últimos 5 dias do mês. Se sim, ele atualiza o mês exibido para o próximo mês. Caso seja dezembro, ele altera o ano para o próximo.
O mês e o ano formatados são atualizados nos elementos HTML que possuem a classe .update-date.
Estrutura do Projeto
O projeto consiste basicamente em um arquivo HTML que contém o script JavaScript embutido, e os elementos HTML que são atualizados dinamicamente.

index.html: Contém o código HTML e o script responsável por alterar a data.
Como executar
Clone este repositório ou faça o download do arquivo index.html.
Abra o arquivo index.html em um navegador.
A data será automaticamente atualizada de acordo com o mês atual e os últimos 5 dias do mês.
Personalização
Você pode modificar os seguintes parâmetros para ajustar o comportamento do script:

daysBeforeSwitch: Define a quantidade de dias antes do final do mês em que a mudança para o próximo mês acontece (atualmente configurado para 5).
monthNames: Array contendo os nomes dos meses. Pode ser ajustado para outros idiomas, se necessário.
