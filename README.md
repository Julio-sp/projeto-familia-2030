# 🗺️ Projeto Família 2030

Este é o repositório centralizado de controle, planejamento e gamificação do plano de vida, estudos e emigração da família (2026–2030). O sistema é baseado em um modelo de travas mensais condicionais para garantir a consistência e evitar a desistência.

---

## 🏛️ Divisão do Aporte Inicial (Base Conservadora da Casa do RJ)
*   **Valor Líquido:** €15.000,00 (Margem calculada absorvendo taxas e possíveis descontos).
*   **Alocação:**
    *   💻 40% - Infraestrutura Digital e Softwares (€6.000)
    *   🧠 30% - Capacitação e Potencial Mental / Cursos (€4.500)
    *   🛡️ 20% - Reserva de Contingência (€3.000)
    *   ✈️ 10% - Validação e Emigração (€1.500)

---

## 📂 Estrutura do Diretório do Código (React + Vite + Tailwind)

A aplicação será dividida nos seguintes módulos internos de dados e páginas:

```text
projeto-familia-2030/
├── src/
│   ├── data/            # Bases de dados congeladas e lições
│   │   ├── meses.js
│   │   ├── idiomas.js
│   │   ├── carreiraMae.js
│   │   ├── carreiraPai.js
│   │   ├── filha.js
│   │   ├── financas.js
│   │   └── imoveis.js
│   ├── components/      # Componentes de interface do Dashboard
│   └── pages/           # Visualizações de cada plano específico
