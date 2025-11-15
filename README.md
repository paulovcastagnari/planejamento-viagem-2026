# 🧳 Planejamento de Viagem — Férias 2026

## 🇮🇹 Destinos na Itália

- Roma
- Cinque Terre
- Florença
- Pisa
- Siena

---

# 📅 Itinerário — Versão 1 (3 destinos principais)
**Período:** *01/05/2026 a 11/05/2026*  
**Duração:** *10 noites*

---

## 🗓️ Linha do tempo da viagem

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title Itinerário de Viagem – Maio 2026
    excludes weekends

    section Roma
    Chegada e estadia em Roma     :2026-05-01, 3d

    section Cinque Terre
    Viagem Roma → Cinque Terre   :milestone, ct_arrive, 2026-05-04, 0d
    Estadia em Cinque Terre      :2026-05-04, 3d

    section Florença (+ Pisa + Siena)
    Viagem para Florença         :milestone, fl_arrive, 2026-05-07, 0d
    Dia 1 – Pisa                 :2026-05-08, 1d
    Dia 2 – Siena                :2026-05-09, 1d
    Dia 3 – Florença             :2026-05-10, 1d
    Tempo livre em Florença      :2026-05-10, 1d

    section Retorno
    Voo Florença → Brasil        :milestone, return_bra, 2026-05-11, 0d
```

---

## ✈️ Detalhamento dos deslocamentos

### 1️⃣ Brasil → Roma
- **Saída (GRU):** 01/05/2026 — 00:30  
- **Chegada (FCO):** 01/05/2026 — 18:45  

### 2️⃣ Roma → Cinque Terre
- **Saída:** 04/05/2026 — Estação Termini  
- **Chegada:** 04/05/2026 — La Spezia  

### 3️⃣ Cinque Terre → Florença
- **Saída:** 07/05/2026  
- **Programação:**  
  - *08/05 – Pisa*  
  - *09/05 – Siena*  
  - *10/05 – Florença*  
  - *11/05 (metade do dia) – Florença*  

### 4️⃣ Florença → Brasil
- **Saída (FLR):** 11/05/2026 — 19:15  
- **Chegada (GRU):** 11/05/2026 — 05:50  

---

## 🗺️ Fluxo geral do roteiro

```mermaid
flowchart LR
    A[🇧🇷 São Paulo<br>01/05] --> B[🇮🇹 Roma<br>01–04/05]
    B --> C[Cinque Terre<br>04–07/05]
    C --> D[Florença<br>07–11/05]
    D --> E[🇧🇷 Retorno ao Brasil<br>11/05]
```

---

# 💰 Budget – Versão inicial

| Trecho | Valor |
|--------|-------|
| ✈️ GRU → Roma (FCO) | **R$ 3.971,17** |
| ✈️ Roma (FCO) → GRU | **R$ 3.091,09** |
| **Total parcial aéreo** | **R$ 7.062,26** |
