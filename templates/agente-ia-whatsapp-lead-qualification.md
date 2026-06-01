# Template: qualificacao de lead com agente de IA no WhatsApp

Este template descreve uma estrutura segura para um agente de IA qualificar leads no WhatsApp antes de transferir para o time comercial.

## Objetivo

Transformar uma conversa solta em um lead com contexto, prioridade e proximo passo claro.

## Campos minimos do lead

- nome
- empresa
- telefone
- segmento
- dor principal
- urgencia
- orcamento aproximado
- canal de origem
- etapa do funil
- resumo da conversa
- proximo passo

## Fluxo recomendado

1. Saudacao contextual.
2. Identificacao da dor.
3. Pergunta de situacao.
4. Pergunta de impacto.
5. Confirmacao de urgencia.
6. Classificacao do lead.
7. Encaminhamento para diagnostico, reuniao ou follow-up.
8. Registro no Painel Inteligente.

## Prompt operacional

Voce e um agente de IA comercial. Sua funcao e entender a dor do lead, qualificar a oportunidade e registrar os dados estruturados sem parecer um formulario. Faca uma pergunta por vez. Se o lead demonstrar urgencia, priorize agendamento. Se a dor nao estiver clara, pergunte pelo processo que mais perde tempo ou dinheiro hoje.

## Saida estruturada

```json
{
  "lead_status": "qualified",
  "segment": "educacao",
  "pain": "demora para responder leads no WhatsApp",
  "urgency": "high",
  "recommended_next_step": "diagnostico",
  "summary": "Lead precisa responder interessados fora do horario e qualificar visitas antes do time comercial."
}
```

## Aplicacao XMACNA

A XMACNA cria Funcionarios Digitais com IA que executam esse fluxo no WhatsApp, qualificam leads e atualizam o Painel Inteligente em tempo real.

Referencia: https://xmacna.ai/sdr-com-ia

Diagnostico: https://xmacna.ai/diagnostico

