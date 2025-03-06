# geracao-energia
# Análise da Geração de Energia Renovável no Brasil

Este projeto visa comparar a evolução histórica da geração de energia renovável no Brasil, com foco nas fontes **hidrelétrica, eólica e solar**, utilizando dados oficiais de capacidade instalada, quantidade de usinas e operação.

---

## Tabela de Conteúdo
- [Objetivos](#objetivos)
- [Dados Utilizados](#dados-utilizados)
- [Principais Resultados](#principais-resultados)
- [Uso](#uso)
- [Próximas Etapas](#próximas-etapas)

---

## Objetivos
1. Comparar o crescimento das fontes hidrelétrica, eólica e solar no Brasil (2001–2024).
2. Analisar fatores econômicos, ambientais e geográficos que influenciam cada fonte.
3. Fornecer insights para políticas públicas e investimentos em energia renovável.

---

## Dados Utilizados
- **Arquivo Principal**: `empreendimento-operacao-historico.csv`  
  - **Fonte**: Dados públicos da ANEEL/EPE (adaptados para fins didáticos).  
  - **Campos Relevantes**:  
    - `SigTipoGeracao`: Tipo de geração (ex: `UHE`, `EOL`, `UFV`).  
    - `MdaPotenciaInstaladaKW`: Potência instalada em kW.  
    - `QtdUsinasPeriodo`: Número de usinas em operação.  
    - `AnoReferencia`/`MesReferencia`: Período de referência.  

---

## Principais Resultados
### Crescimento da Potência Instalada (2001–2024)
