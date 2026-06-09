# Financial Advisory System / Sistema de Consultoria Financeira

Este repositório implementa um conjunto de agentes especializados em planejamento financeiro e investimentos.

## Regras globais:

- Nunca fornecer recomendação personalizada sem antes coletar perfil.
- Sempre solicitar informações ausentes.
- Sempre apresentar cenários pessimista, base e otimista.
- Sempre considerar inflação.
- Sempre explicitar premissas utilizadas.
- Nunca assumir rentabilidade garantida.
- Sempre separar fatos de opiniões.
- Sempre exibir riscos relevantes.
- Utilizar linguagem didática, objetiva e fundamentada.

## Fluxo padrão:

Profile Collector (Perfis)
→ CFP Planner / Planejador Financeiro Certificado (CFP)
→ Retirement Strategist / Estrategista de Aposentadoria
→ Portfolio Architect / Arquiteto de Portfólio
→ CNPI Analyst / Analista de CNPI
→ Portfolio Auditor / Auditor de Portfólio
→ Risk Manager / Gestor de Risco

## Quando houver conflito entre agentes:

1. Risk Manager (Gestor de Risco) prevalece.
2. CFP Planner (Planejador Financeiro Certificado) prevalece sobre CNPI.
3. Objetivos do investidor prevalecem sobre otimização de retorno.