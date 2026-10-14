---
layout: default
title: Privacidade
lang: pt-BR
home_path: /pt-BR/
support_path: /pt-BR/support/
privacy_path: /pt-BR/privacy/
terms_path: /pt-BR/terms/
permalink: /pt-BR/privacy/
---

# Política de Privacidade do Gantt Chart for Sheets

**Última atualização: 14 de outubro de 2026**

## Resumo

Este complemento não tem permissão para acessar a internet. Ele lê a lista de tarefas, cria o gráfico de Gantt e o grava em uma guia da mesma planilha. Não coletamos, armazenamos, vendemos nem compartilhamos dados pessoais por meio do complemento.

## O que o complemento pode acessar

Ele solicita exatamente estas duas permissões:

| Permissão | Escopo | Uso |
|---|---|---|
| Ver, editar, criar e excluir apenas o arquivo Google Sheets que você está usando | `spreadsheets.currentonly` | Ler a lista de tarefas e gravar o gráfico em outra guia do mesmo arquivo |
| Exibir e executar conteúdo da web em mensagens e barras laterais | `script.container.ui` | Exibir o menu e as caixas de diálogo do complemento |

O Google acrescenta seu nome e endereço de e-mail à tela de instalação do Google Workspace Marketplace. Esse requisito vale para todos os complementos publicados. O código do complemento não lê essas informações; nós não as recebemos nem armazenamos.

O complemento não acessa o Google Drive, outras planilhas, e-mail, contatos ou calendário. Ele também não tem a permissão `script.external_request` e, portanto, não pode fazer conexões externas.

## O que é armazenado e onde

O armazenamento de complementos do Google dentro da sua conta guarda:

1. Preferências por planilha: ignorar fins de semana e destacar o caminho crítico.
2. Sua chave de licença, caso tenha uma. Ela pode conter o plano, a data de validade e a referência da compra, mas não contém seu nome ou e-mail.

Ao desinstalar o complemento, o Google remove essas informações. Você também pode apagar a chave a qualquer momento: acesse **Extensões → Gantt Chart for Sheets → Licença**, deixe o campo vazio e confirme.

## Dados recebidos quando você compra uma licença

As compras são processadas pelo provedor de pagamento, não pelo complemento. Ao comprar o Pro, recebemos uma referência do pedido e o endereço de e-mail para enviar a chave. Não vemos nem armazenamos os dados do seu cartão. Um script separado do Google Apps Script gera e envia a chave; a referência e o e-mail ficam no armazenamento privado da nossa conta.

Usamos esses dados somente para emitir ou reenviar a chave e manter registros exigidos por lei. Não os usamos para marketing nem os compartilhamos com terceiros. Guardamos os dados apenas pelo período exigido pelas normas fiscais e os apagamos depois. Quando permitido por lei, você pode solicitar a exclusão antes.

## Como protegemos os dados

**Durante a transmissão:** Os dados da planilha não saem da infraestrutura do Google. O complemento é executado no Google Apps Script e grava o gráfico no mesmo arquivo. O Google protege com TLS as conexões entre o navegador e o script. O complemento não tem permissão para acessar redes externas.

**Armazenamento:** Não mantemos cópias dos dados da planilha. Nomes de tarefas, datas, responsáveis e demais informações são processados na memória enquanto o gráfico é criado e não permanecem depois. Preferências e chave, quando houver, ficam no `PropertiesService` do Google, criptografado pelo Google em repouso. Não conseguimos ler esses valores.

**Controle de acesso:** Não existe um meio para que a Slowgrain acesse os dados da sua planilha. Não há funcionários, prestadores ou processadores com acesso a esses dados. O projeto do Apps Script publicado pertence a uma única conta Google. O segredo usado para assinar chaves não é enviado ao repositório nem incluído no código publicado.

## Retenção e exclusão

- Não retemos dados de planilhas.
- O Google exclui preferências e chave quando você desinstala o complemento; você também pode apagar a chave manualmente.
- A referência do pedido e o e-mail são guardados apenas pelo período exigido pela legislação fiscal e depois excluídos. Entre em contato para pedir a exclusão antecipada quando a lei permitir.

O gráfico é gravado em uma guia da sua planilha e segue as configurações de compartilhamento do arquivo. Quem já tem acesso ao arquivo pode ver o gráfico, assim como vê a lista original. Nós não publicamos nem compartilhamos o gráfico.

## APIs do Google Workspace e modelos de IA

Não usamos dados das APIs do Google Workspace para desenvolver, aprimorar ou treinar modelos gerais ou não personalizados de IA ou aprendizado de máquina. O complemento não usa IA nem aprendizado de máquina; o cronograma é calculado com operações comuns.

O uso e a transferência de informações recebidas das APIs do Google seguem a [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), inclusive os requisitos de uso limitado.

## Crianças

Este complemento é uma ferramenta de trabalho e não se destina a crianças menores de 13 anos.

## Alterações

Se esta política mudar, atualizaremos a data acima e publicaremos a versão vigente neste endereço.

## Contato

Para dúvidas sobre privacidade ou pedidos para excluir informações armazenadas:

**slowgrain.dev@gmail.com**

Respondemos em até cinco dias úteis.
