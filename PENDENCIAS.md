# Lista de pendências de conteúdo — Portal PIJ D4571

Todos os itens abaixo aparecem no protótipo como placeholder visual
`[[entre colchetes duplos]]` (fundo Powder Blue, texto Royal Blue) ou com o
rótulo **"exemplo ilustrativo"**. Nada deve ir ao ar antes de a Comissão
Distrital preencher/validar cada item.

## Globais (aparecem em várias páginas)

| Item | Onde aparece | O que falta |
|---|---|---|
| Rótulo do ciclo (ex.: 2027/2028) | Faixa de prazo, edital, calendário | Definir o ciclo vigente |
| Datas de abertura e encerramento das inscrições | Faixa de prazo (contador), Quero ir › Prazos, Calendário | Datas oficiais do edital — hoje o site usa datas demonstrativas (01/08–31/10/2026) |
| E-mail institucional do programa | Contato, rodapé | Confirmar se contato.rye@intercambiod4571.org (último edital) segue ativo — o domínio saiu do ar |
| Endereço da secretaria | Contato | Confirmar vigência do endereço do último edital (Rua Cap. Emydio Moreira, 109 — Aparecida/SP) |
| Logo oficial | Cabeçalho, rodapé, favicon | Substituir o SVG aproximado pelos arquivos oficiais do Brand Center (lockup do distrito + "PIJ", nas versões cor, monocromática e branca já existentes em PNG) |
| Fontes licenciadas | Todo o site | O protótipo usa Open Sans/Georgia via fontes do sistema; em produção, self-host de Open Sans (e avaliar licença de Frutiger/Sentinel) |

## Home

- Foto documental do hero (intercambistas reais, com termo de imagem).
- Número de jovens já enviados pelo D4571 (bloco "Números").
- Depoimentos reais com nome, cidade, destino, ano, foto e termo de
  autorização — os 4 atuais são fictícios e rotulados.
- Três notícias reais com data (as atuais são ilustrativas).
- Foto do bloco "Seja uma família anfitriã".

## Sobre

- Nomes dos titulares das 9 funções da comissão (estrutura já montada).
- Número oficial de clubes e rotarianos do distrito (fontes divergem: 98
  clubes/1.609 rotarianos × ~50 clubes no diretório navegável).
- Foto documental da Alcione com intercambistas; foto de projeto comunitário;
  foto de encontro ROTEX.

## Quero ir

- **Taxa de inscrição** e **taxa distrital de participação** do D4571
  (as faixas exibidas são explicitamente de outros distritos, ciclo 2026-27).
- Lista oficial de países parceiros e vagas do ciclo (grade atual rotulada
  como ilustrativa).
- Datas de cada uma das 10 etapas do processo seletivo.
- **Edital do ciclo vigente** em PDF. ✔ Já recuperados do site anterior e
  publicados em `docs/`: Edital 007 (LTEP 2025/26), Edital 008 (Jovem
  Destaque), errata de 17/08/2025, Regulamento P.I.I.J. assinado (set/2025)
  e as 5 fichas/termos em DOCX — todos marcados como "Ciclo 2025/26 ·
  histórico"; falta confirmar a vigência do Regulamento.
- Situação do programa de bolsas no ciclo vigente (o Edital 008 de 2025/26
  já está publicado como referência: 1 vaga, escola pública, renda ≤ 3 SM).
- Valores do ciclo vigente (o site já publica, como referência histórica, os
  valores do Edital 007 2025/26: inscrição R$ 1.000; taxa distrital
  R$ 16.500 em até 6 parcelas).
- Prazo de resposta ao formulário de interesse ("em até N dias úteis").
- Texto oficial do termo de compromisso e da autorização de uso de imagem
  (checkboxes da etapa 5 do wizard).
- Diretório de clubes por cidade (o seletor de clube patrocinador hoje lista
  cidades, não clubes).

## Quero hospedar

- Prazo de resposta da coordenação de famílias anfitriãs.
- Guia da família anfitriã do D4571 (material a produzir).

## Inbounds

- Checklist detalhado de documentos do inbound (visto/CRNM).
- Nome e contato 24 h da coordenação de inbounds.
- Guia de boas-vindas ("survival kit") em PDF.

## Clubes e rotarianos

- Acordo do clube do ciclo (arquivo e data).
- Agenda de treinamentos de oficiais e conselheiros.
- Kit de materiais de divulgação.

## Proteção à Juventude

- Nome e contato direto do Representante Distrital de Proteção aos Jovens.
- Política Distrital de Proteção à Juventude em PDF.
- Conferir a redação oficial em português da Declaração de Conduta (o site usa
  tradução de referência, sinalizada como tal).

## Documentos

- Todos os PDFs: ficha de inscrição, termo de compromisso, autorização de
  imagem, edital, manuais próprios do distrito.
- Acervo histórico de editais anteriores (recuperar do domínio fora do ar).

## Privacidade / LGPD

- **Entidade legal controladora dos dados + CNPJ** — pendência crítica: a
  associação anterior (CNPJ 34.606.242/0001-45) consta baixada desde
  06/2025; confirmar a estrutura sucessora antes de coletar dados de menores.
- E-mail do Encarregado de Dados (DPO).
- Prazos de retenção de dados.
- Revisão jurídica do texto completo da política.

## Dados em conflito nas fontes (tratados como placeholder)

1. Número de famílias anfitriãs mínimas por intercambista (2 × 3).
2. Faixa etária do NGSE (18–25 × 18–30).
3. Número total de clubes do distrito.

## Decisões de produto que cabem à Comissão

- Confirmar o prazo-alvo de resposta dos formulários (SLA dos voluntários).
- Validar a regra etária aplicada nos formulários (hoje: LTEP/STEP 15–18,
  Camps 13–25, NGSE 18–30, com aviso explicativo).
- Definir se a inscrição formal (wizard) ficará no site ou em sistema próprio
  (exige backend seguro — ver "fora do escopo" na entrega).
