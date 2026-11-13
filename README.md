# Claude Google Ads: instaladores

Este repositório guarda só os instaladores e as atualizações do app **Claude Google Ads**, que conecta o
Claude Desktop ao Google Ads e pede aprovação para cada alteração. O código-fonte é privado.

## Instalar

Baixe **[Claude-Google-Ads-Instalador.exe](https://github.com/Eduardo-Junior/claude-google-ads-releases/releases/latest/download/Claude-Google-Ads-Instalador.exe)**
e abra. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** e depois em
**Executar assim mesmo** (o instalador ainda não tem certificado de assinatura de código).

O app é instalado na pasta do seu usuário, sem pedir administrador, e **se atualiza sozinho**.

## Primeiros passos

Antes de começar, tenha o [Claude Desktop](https://claude.ai/download) instalado e o arquivo
`credentials.json` que você recebeu. Depois, abra o app e siga a aba **Configuração**:

1. **Credenciais:** clique em **Escolher arquivo** e selecione o `credentials.json`.
2. **Login no Google:** clique em **Entrar com o Google** e use o e-mail que os clientes adicionaram no
   Google Ads. Se aparecer "O Google não verificou este app", clique em **Avançado** e depois em **Acessar**.
   Marque a permissão do Google Ads.
3. **Contas dos clientes:** confira se as contas aparecem. Quando entrar ou sair cliente, clique em
   **Atualizar lista de contas**.
4. **O que o Claude pode alterar:** o padrão é **Sem dinheiro**. Nesse modo, orçamento, lances e ativar
   campanhas continuam com você.
5. **Conectar ao Claude:** clique em **Conectar ao Claude**, depois em **Fechar o Claude agora**, e abra o
   Claude de novo. Deixe marcada a opção de abrir o app junto com o Windows.

Pronto. No Claude, peça por exemplo: *"Liste minhas contas do Google Ads"* ou *"Analise as campanhas do
cliente X nos últimos 30 dias"*.

Quando o Claude propuser uma alteração, a janela do app se abre sozinha com o pedido na aba
**Aprovações**. Nada muda no Google Ads sem você clicar em **Aprovar**. O Claude só acessa o Google Ads com o
app aberto (ele fica perto do relógio do Windows).

## Segurança das atualizações

Cada versão traz o executável, a assinatura dele (`.sig`) e o arquivo `SHA256SUMS.txt`. O app só instala uma
atualização se a assinatura Ed25519 conferir com a chave embutida nele. Uma versão publicada aqui sem a
assinatura certa é recusada.

## Privacidade

Seus dados ficam no seu computador e vão direto para o Google Ads e para o Claude. Veja a
[Política de Privacidade](PRIVACIDADE.md).

## Aviso

Projeto pessoal, sem afiliação com a Anthropic ou o Google. "Claude" e "Google Ads" são marcas de seus donos.
