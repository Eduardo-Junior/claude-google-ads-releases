# Política de Privacidade: Claude Google Ads

Última atualização: 13 de novembro de 2026 (registro técnico e relatório de problema).

O Claude Google Ads é um aplicativo para Windows que conecta o Claude Desktop às contas do Google Ads
de quem o instala. Com ele, o Claude consulta e analisa campanhas, e cada alteração só é aplicada depois
de aprovada manualmente na janela do app.

## Dados acessados

Com a sua autorização (a permissão "Google Ads" da sua Conta Google), o app acessa os dados das contas do
Google Ads a que o seu login tem acesso: contas, campanhas, grupos de anúncios, anúncios, palavras-chave,
orçamentos, lances e relatórios de desempenho.

O app pede só o escopo `https://www.googleapis.com/auth/adwords`. Ele não acessa seu Gmail, Drive,
contatos nem outros serviços do Google.

## Onde os dados ficam

- O login (token de atualização), a configuração, a lista de contas e o histórico de aprovações ficam
  apenas no seu computador, na pasta `%APPDATA%\ClaudeGoogleAds`.
- O app se comunica diretamente com a API do Google Ads. Não existe servidor do desenvolvedor no meio, e
  nenhum dado é enviado ao desenvolvedor.
- Quando você pede algo ao Claude, os dados necessários para responder são enviados ao Claude (Anthropic)
  durante a conversa, conforme a [política de privacidade da Anthropic](https://www.anthropic.com/legal/privacy).
- Para verificar atualizações, o app consulta este repositório no GitHub. Essa consulta não leva nenhum
  dado seu.
- O app guarda um registro técnico (log) em `%APPDATA%\ClaudeGoogleAds\logs`, para ajudar a resolver
  problemas. Os arquivos ficam só no seu computador e são apagados sozinhos depois de 7 dias.
- Em **Configuração → Algo deu errado?**, você pode gerar um relatório de problema. O app remove dele o
  login, os tokens, os segredos e os e-mails, e mostra o conteúdo antes. O relatório só sai do computador
  se você mesmo copiar ou enviar o arquivo para alguém.

## Compartilhamento

O desenvolvedor do app não coleta, armazena, vende nem compartilha os seus dados.

## Como revogar o acesso

1. No app, use **Configuração → Sair desta conta** para apagar o login deste computador.
2. Remova o acesso em [myaccount.google.com/permissions](https://myaccount.google.com/permissions).
3. Desinstale o app pelo Windows (**Configurações → Aplicativos**). Para apagar também a configuração,
   exclua a pasta `%APPDATA%\ClaudeGoogleAds`.

## Uso limitado

O uso e a transferência das informações recebidas das APIs do Google seguem a
[Política de Dados do Usuário dos Serviços de API do Google](https://developers.google.com/terms/api-services-user-data-policy),
incluindo os requisitos de Uso Limitado.

## Alterações

Mudanças nesta política são publicadas neste arquivo, com a data de atualização no topo.

## Contato

Abra uma solicitação em
[github.com/Eduardo-Junior/claude-google-ads-releases/issues](https://github.com/Eduardo-Junior/claude-google-ads-releases/issues).
