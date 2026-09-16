# Épico para o Jira

Copie os campos abaixo ao criar o épico manualmente (ou use como referência
se for importar via CSV/API).

---

**Tipo de item:** Epic
**Nome do épico (Epic Name):** Portal PIJ D4571
**Resumo (Summary):** Lançar o portal público do Intercâmbio de Jovens — Rotary Distrito 4571

**Descrição:**

> O Distrito 4571 não tem hoje uma presença digital confiável para o
> Programa de Intercâmbio de Jovens (PIJ): o domínio antigo
> (intercambiod4571.org) está fora do ar e não há canal oficial único para
> candidatos, famílias anfitriãs, clubes e a comissão distrital.
>
> Este épico cobre o desenvolvimento e o lançamento de um portal estático
> (protótipo já construído, publicado em GitHub Pages) com as seções de
> Sobre, Programas, Quero ir, Quero hospedar, Inbounds, Clubes, Proteção à
> Juventude, Documentos e formulários de interesse/inscrição/hospedagem.
>
> **Objetivo:** ter um site publicável, com todo o conteúdo institucional
> validado pela Comissão Distrital, dados reais (não placeholders) e
> conformidade com a LGPD, pronto para substituir a ausência de canal
> digital do programa.
>
> **Fora do escopo deste épico:** backend de inscrição com persistência,
> pagamento online, área logada — tratados em épico futuro caso a Comissão
> decida por essa rota.

**Critérios de aceite do épico:**
- [ ] Nenhum dado de contato/valor/prazo exibido como placeholder `[[...]]`
- [ ] Entidade legal responsável pelo tratamento de dados confirmada e
      publicada na política de privacidade
- [ ] Conteúdo revisado e aprovado pela Comissão Distrital
- [ ] Site publicado no domínio oficial do distrito (ou mantido em GitHub
      Pages, a critério da Comissão)

**Labels sugeridas:** `pij-d4571`, `website`, `rotary`
**Componente sugerido:** Portal PIJ

---

## Stories/Tasks para vincular ao épico

Sugestão de quebra (pode ser criada como Story ou Task, conforme o fluxo do
time):

### 🔴 Crítico
1. Definir entidade legal + CNPJ controlador dos dados e revisar política de privacidade (LGPD)
2. Definir e-mail do Encarregado de Dados (DPO)
3. Confirmar e-mail institucional e endereço da secretaria do programa
4. Definir o ciclo vigente (rótulo e datas de inscrição) e atualizar o site
5. Decidir se a inscrição formal (wizard) permanece estática ou migra para sistema com backend

### 🟡 Importante
6. Confirmar taxa de inscrição e taxa distrital do ciclo vigente
7. Publicar lista oficial de países parceiros e vagas do ciclo
8. Preencher datas das 10 etapas do processo seletivo
9. Coletar nomes dos titulares das 9 funções da comissão distrital
10. Montar diretório de clubes por cidade (para o seletor de clube patrocinador)
11. Substituir depoimentos fictícios por depoimentos reais com termo de autorização
12. Obter fotos documentais reais (hero, família anfitriã, comissão, ROTEX)
13. Definir texto oficial do termo de compromisso e da autorização de uso de imagem
14. Resolver dados em conflito (nº de famílias anfitriãs, faixa etária NGSE, nº de clubes)
15. Self-host das fontes licenciadas (Open Sans; avaliar Frutiger/Sentinel)

### ⚪ Desejável
16. Publicar 3 notícias reais com data
17. Produzir guia da família anfitriã e checklist de documentos do inbound
18. Produzir kit de materiais de divulgação para clubes
19. Ampliar acervo histórico de editais anteriores
20. Revisar responsividade e acessibilidade

---

*Referência completa e detalhada de cada item em `TASKS.md` e
`PENDENCIAS.md` no repositório.*
