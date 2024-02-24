# README

## SharkChat

SharkChat é um aplicativo de chat simples construído usando a biblioteca `flet`.

### Como funciona

O código começa importando a biblioteca `flet` e definindo a função principal `main(pagina)`. Dentro desta função, vários elementos são criados e adicionados à página:

1. `Titulo`: Um objeto de texto que serve como o título do chat.
2. `nome_usuario`: Um campo de texto onde o usuário pode inserir seu nome.
3. `chat`: Uma coluna onde as mensagens do chat serão exibidas.
4. `enviar_mensagem_tunel`: Uma função que adiciona novas mensagens ao chat.
5. `enviar_mensagem`: Uma função que envia a mensagem do usuário para o chat.
6. `campo_mensagem`: Um campo de texto onde o usuário pode escrever sua mensagem.
7. `botao_enviar`: Um botão que o usuário pode clicar para enviar sua mensagem.
8. `entrar_chat`: Uma função que é chamada quando o usuário clica no botão "Entrar" no diálogo de alerta.
9. `popup`: Um diálogo de alerta que é exibido quando o usuário inicia o chat.
10. `iniciar_chat`: Uma função que é chamada quando o usuário clica no botão "Iniciar Conversa".

### Executando o aplicativo

Esse app tem como executar de duas maneiras em formato WEb e App modo janela nativa do sistema operacional, um jeito parecido com electron

Para executar o aplicativo em formato web, você precisa chamar a função `ft.app(main, view=ft.WEB_BROWSER)`, isso iniciará o aplicativo no navegador web. E para executar em modo janela do sistema operacional chame a função `#ft.app(main)` está comentada.

OBS: Eu deixe no codigo ambas funçoes caso queira mudar, apenas coloque # na função que nao queira mais usar. Nesse modelo `#ft.app(main)`

### Documentação do Flet

Para mais informações sobre como usar a biblioteca `flet`, consulte a [documentação oficial](https://flet.dev/docs/).

## Contribuições
Contribuições para este projeto são bem-vindas. Por favor, abra um problema ou uma solicitação de pull.

## Licença
Este projeto está licenciado sob a licença MIT.
```
Espero que isso ajude! Se você tiver mais perguntas, fique à vontade para perguntar.
