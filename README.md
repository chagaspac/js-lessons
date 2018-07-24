# Javascript - 1
https://www.w3schools.com/js/default.asp

Você deve ler tudo do menu JS Tutorials, de **JS HOME** até **JS Loop While**

## Atividade
### SISTEMA DE SORTEIO
**Arquivo:** tarefa1.html
Você realizará as segunites tarefas num HTML + JS. O código base já está disponivel no arquivo. Não pode usar JQuery e nenhum outro framework, você está aqui pra aprender JS!

1. Ao clicar no botão GERAR CUPOM, você deve verificar o horário atual. Dependendo do horário, você deve mostrar as segunites mensagens para o usuário:

> *Bom dia* {Fulano} (4am até 12am)

> *Boa tarde* {Fulano} (12pm até 19pm)

> *Boa noite* {Fulano} (19pm até 4am)

Sendo que, {Fulano} deve ser o conteúdo da caixa de texto "Nome". O nome do usuário deve aparecer em caixa alta (CAPSLOCK)

2. Ao clicar no botão **GERAR CUPOM**, também deve gerar um número da sorte para o usúario que deve variar de **5625 até 5731**. Esse número da sorte deve ser armazenado num ARRAY. Para outras execuções, o número da sorte **NÃO** pode ser igual a um já gerado. Caso não existam mais cupons para serem gerados, deve ser mostrado um alert para avisar o usuário de que os cupons acabaram.
A mensagem deve ser mostrada abaixo a mensagem da atividade (1), e deve estar no seguinte padrão:

> O seu número da sorte é: {Numero}!!

3. Ao clicar no botão SORTEAR!!!, o sistema deve escolher um dos números gerados e mostrar no centro da tela o número que foi sorteado no seguinte formato: 

> PARABÉNS NÚMERO {Numero}, VOCÊ ACABA DE GANHAR UMA BELONAVE DA ALIANÇA!.

5. Ao clicar no botão RESETAR, a tela deve voltar ao estado original, limpar todos os cupons gerados e mensagens.