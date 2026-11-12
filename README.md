# Claude Google Ads: instaladores

Este repositório guarda só os instaladores e as atualizações do app **Claude Google Ads**, que conecta o
Claude Desktop ao Google Ads e pede aprovação para cada alteração. O código-fonte é privado.

## Instalar

Baixe **[Claude-Google-Ads-Instalador.exe](https://github.com/Eduardo-Junior/claude-google-ads-releases/releases/latest/download/Claude-Google-Ads-Instalador.exe)**
e abra. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** e depois em
**Executar assim mesmo** (o instalador ainda não tem certificado de assinatura de código).

O app é instalado na pasta do seu usuário, sem pedir administrador, e **se atualiza sozinho**.

## Segurança das atualizações

Cada versão traz o executável, a assinatura dele (`.sig`) e o arquivo `SHA256SUMS.txt`. O app só instala uma
atualização se a assinatura Ed25519 conferir com a chave embutida nele. Uma versão publicada aqui sem a
assinatura certa é recusada.

## Aviso

Projeto pessoal, sem afiliação com a Anthropic ou o Google. "Claude" e "Google Ads" são marcas de seus donos.
