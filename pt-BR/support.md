---
layout: default
title: Suporte
lang: pt-BR
home_path: /pt-BR/
support_path: /pt-BR/support/
privacy_path: /pt-BR/privacy/
terms_path: /pt-BR/terms/
permalink: /pt-BR/support/
---

# Suporte — Gantt Chart for Sheets

**E-mail: slowgrain.dev@gmail.com** — respondemos em até cinco dias úteis.

## Primeiros passos

1. Abra a planilha que contém sua lista de tarefas.
2. Escolha **Extensões → Gantt Chart for Sheets → Criar gráfico de Gantt**.
3. Uma guia **Gantt** será criada com o gráfico. A lista original não é alterada.

Execute novamente quando o plano mudar; o gráfico será reconstruído.

## Mapear uma planilha existente

A tabela pode começar em qualquer célula e as colunas podem estar em qualquer ordem. Cabeçalhos em inglês, coreano, japonês, espanhol, português, francês e alemão são reconhecidos.

Se o reconhecimento não estiver correto, escolha **Ferramentas do Gantt → Vincular e pré-visualizar planilha de tarefas**. Selecione a linha de cabeçalho e associe as colunas. Antes de salvar, confira até seis tarefas reais, as datas calculadas e a quantidade de tarefas sem início ou não agendadas. O mapeamento é salvo por guia. **Não usar** impede a inferência daquele campo.

| Campo | Exemplos de cabeçalhos | Obrigatório |
|---|---|---|
| Nome da tarefa | Task, Tarefa, Aufgabe, 作業 | Sim |
| Início | Start, Início, Début, 開始 | Sim* |
| Fim ou duração | End, Fim, Durée, 日数 | Um dos dois |
| Predecessoras | After, Predecessors, Depois de | Não |
| Progresso | Progress, Progresso, Avancement | Não |
| Responsável | Owner, Responsável, 担当者 | Não |
| WBS / tarefa superior | Level, Parent, Nível | Não |
| Esforço e capacidade diária | Total effort, Hours per day | Não |

* O início pode ficar vazio se uma predecessora permitir calculá-lo ou se a linha for uma fase com tarefas filhas.

## Datas

Use datas ISO (2026-04-03) ou células de data da planilha para evitar ambiguidades. O complemento identifica a ordem dia/mês por valores claros; sem evidências, usa a ordem comum do idioma.

## Predecessoras

Informe o ID da tarefa anterior na coluna Predecessoras. `12` começa após a tarefa 12 terminar; `12+3` adiciona três dias; `12-1` indica um dia de antecipação. Separe várias tarefas por vírgula.

## Carga de trabalho e horas

Informe os responsáveis para ver tarefas simultâneas e a capacidade diária. **Esforço total (horas)** é dividido igualmente entre as pessoas e os dias úteis planejados. **Horas por dia** prevalece quando informado diretamente para cada pessoa. Tarefas sem horas são excluídas do cálculo, sem estimativa inventada.

## Dúvidas comuns

**Uma tarefa não aparece no gráfico.** O motivo aparece abaixo do gráfico. Confira início, fim, duração e dependências circulares.

**Quero ignorar fins de semana.** Ative **Ignorar fins de semana** no menu. Feriados são configurados por guia.

**O gráfico ficou largo demais.** A escala muda automaticamente entre dias, semanas, meses e trimestres. Não há duração máxima.

**Tenho mais de 50 tarefas.** O plano gratuito permite 50; o Pro remove o limite. As tarefas acima do limite são informadas, não descartadas em silêncio.

## Chaves de licença

Compre o Pro em https://slowgrain.app/gantt-for-sheets/#pro

Para inserir a chave, acesse **Extensões → Gantt Chart for Sheets → Licença → Inserir chave de licença**. Ela fica salva na sua conta Google e só precisa ser inserida uma vez.

Se a chave não chegar, for perdida ou for recusada, escreva para o suporte com a referência do pedido. As chaves começam com `GS1.` e não têm espaços.

## Relatar um problema

Escreva para **slowgrain.dev@gmail.com** e informe:

- o que esperava e o que aconteceu
- uma captura do gráfico ou do erro
- se possível, uma cópia da planilha sem dados confidenciais

O complemento não envia dados por conta própria; anexe os arquivos que quiser compartilhar.
