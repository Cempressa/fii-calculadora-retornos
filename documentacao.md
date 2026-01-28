# 📘 DOCUMENTAÇÃO — Simulador de Investimentos em FIIs

## 🏷️ Versão da Release
**Versão 1.0 — Simulador de Investimentos em FIIs com Excel**

Primeira versão funcional do simulador de investimentos em Fundos Imobiliários (FIIs), desenvolvida como parte do desafio da DIO.  
Inclui:

- Seleção automática de perfil de investidor  
- Cálculo de patrimônio acumulado e dividendos  
- Distribuição percentual por tipo de FII  
- Gráfico dinâmico de alocação  
- Fórmulas financeiras aplicadas  
- Documentação técnica completa  

---

## 📌 1. Objetivo da Planilha

A planilha foi criada para simular investimentos em FIIs, permitindo ao usuário visualizar:

- Patrimônio acumulado ao longo do tempo  
- Dividendos mensais estimados  
- Distribuição sugerida por tipo de FII conforme o perfil do investidor  
- Cenários de crescimento com diferentes taxas de dividendos  

---

## ⚙️ 2. Premissas Utilizadas

- Aporte mensal sugerido: **30% do salário informado**  
- Taxa de rendimento mensal composta (ex.: **1,0789%**)  
- Dividendos calculados com base em percentual definido pelo usuário  
- Perfis disponíveis:
  - Conservador  
  - Moderado  
  - Agressivo  
- Cada perfil possui percentuais de alocação entre:
  - Papel  
  - Tijolo  
  - Híbridos  
  - FOFs  
  - Desenvolvimento  
  - Hotelarias  

---

## 🧮 3. Fórmulas Utilizadas

### **3.1. Patrimônio Acumulado**



\[
FV = PMT \cdot \frac{(1+r)^n - 1}{r}
\]



Onde:  
- **PMT** = aporte mensal  
- **r** = taxa de rendimento mensal  
- **n** = número total de meses  

---

### **3.2. Dividendos Mensais**



\[
Dividendos = Patrimônio \cdot Taxa\_de\_Dividendos
\]



---

### **3.3. Projeção de Cenários**



\[
FV = PMT \cdot \frac{(1+r)^{(anos \cdot 12)} - 1}{r}
\]



---

### **3.4. Distribuição por Tipo de FII**



\[
Valor\_Categoria = Aporte\_Mensal \cdot Percentual\_Categoria
\]



---

## 🧭 4. Como Usar a Planilha

1. Informe seu **salário**  
2. A planilha sugerirá automaticamente **30%** como aporte mensal  
3. Defina:
   - Aporte mensal  
   - Tempo de investimento  
   - Taxa de rendimento mensal  
4. Escolha o **perfil de investidor** no menu suspenso  
5. A planilha exibirá automaticamente:
   - Distribuição por tipo de FII  
   - Patrimônio acumulado  
   - Dividendos mensais  
   - Projeções de longo prazo  
   - Gráfico dinâmico de alocação  

---

## 📊 5. Interpretação dos Resultados

- **Patrimônio acumulado** → valor total ao final do período  
- **Dividendos mensais** → renda passiva estimada  
- **Distribuição por FII** → equilíbrio da carteira conforme o perfil  
- **Cenários** → comparação entre diferentes horizontes de investimento  

---

## 🔧 6. Melhorias Futuras

- Gráficos de evolução do patrimônio ao longo do tempo  
- Aba adicional com histórico de simulações  
- Proteção de células de cálculo  
- Interface mais intuitiva com cores temáticas  

---

## 📦 7. Arquivos do Projeto

