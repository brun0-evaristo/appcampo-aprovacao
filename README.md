# APP CAMPO · página de confirmação de cadastro

Página pública e estática usada pelos botões **Aprovar** e **Recusar** do e-mail de novo cadastro do APP CAMPO (Vaporenge).

- Não guarda dados e não tem segredos.
- O link do e-mail traz um código assinado depois do `#` (que o navegador não envia ao servidor). O servidor confere a assinatura e o prazo.
- Abrir a página não muda nada: só o botão de confirmação aprova ou recusa.

O código do aplicativo fica em outro repositório, privado.
