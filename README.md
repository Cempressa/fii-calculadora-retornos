# Simulador de Investimentos em Fundos Imobiliários com Excel

Este projeto foi desenvolvido como parte do desafio da DIO para aplicar conceitos de Excel na criação de uma ferramenta prática de simulação de investimentos em Fundos Imobiliários (FIIs).

## 🎯 Objetivo

Criar uma planilha interativa que permita ao usuário simular diferentes cenários de investimento em FIIs, considerando variáveis como:

- Valor inicial investido  
- Aportes mensais  
- Taxa de rendimento mensal  
- Tempo de investimento  
- Cálculo de dividendos mensais  
- Patrimônio acumulado ao longo do tempo  

## 🧠 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados e reforçados os seguintes conhecimentos:

- Fórmulas financeiras no Excel (SE, SOMA, TIR, VP, etc.)  
- Automatização de cálculos com referências dinâmicas  
- Estruturação de planilhas para simulação  
- Documentação técnica com Markdown  
- Uso do GitHub para versionamento e compartilhamento  

## 📁 Estrutura do Repositório

Como este projeto tem caráter demonstrativo e o foco está na documentação técnica, o repositório contém apenas o arquivo principal:


## 📘 Documentação Técnica

### 📌 1. Objetivo da Planilha

A planilha foi criada para simular investimentos em FIIs, permitindo ao usuário visualizar:

- Patrimônio acumulado ao longo do tempo  
- Dividendos mensais estimados  
- Distribuição sugerida por tipo de FII conforme o perfil do investidor  
- Cenários de crescimento com diferentes taxas de dividendos  

### ⚙️ 2. Premissas Utilizadas

- Aporte mensal sugerido: 30% do salário informado  
- Taxa de rendimento mensal composta (ex.: 1,0789%)  
- Dividendos calculados com base em percentual definido pelo usuário  
- Perfis disponíveis: Conservador, Moderado, Agressivo  
- Cada perfil possui percentuais de alocação entre os tipos de FII: Papel, Tijolo, Híbridos, FOFs, Desenvolvimento, Hotelarias  

### 🧮 3. Fórmulas Utilizadas

**3.1. Patrimônio Acumulado**  


\[
FV = PMT \cdot \frac{(1+r)^n - 1}{r}
\]

  
Onde:  
- PMT = aporte mensal  
- r = taxa de rendimento mensal  
- n = número total de meses  

**3.2. Dividendos Mensais**  


\[
Dividendos = Patrimônio \cdot Taxa\_de\_Dividendos
\]



**3.3. Projeção de Cenários**  


\[
FV = PMT \cdot \frac{(1+r)^{(anos \cdot 12)} - 1}{r}
\]



**3.4. Distribuição por Tipo de FII**  


\[
Valor\_Categoria = Aporte\_Mensal \cdot Percentual\_Categoria
\]



### 🧭 4. Como Usar a Planilha

1. Informe seu salário e a planilha sugerirá automaticamente 30% para investimento  
2. Defina o aporte mensal, tempo de investimento e taxa de rendimento  
3. Escolha o perfil de investidor (via menu suspenso)  
4. A planilha exibirá automaticamente:
   - Distribuição por tipo de FII  
   - Patrimônio acumulado  
   - Dividendos mensais  
   - Projeções de longo prazo  
   - Gráfico de alocação por categoria  

### 📊 5. Interpretação dos Resultados

- Patrimônio acumulado mostra o valor total ao final do período  
- Dividendos mensais estimam o fluxo de renda passiva  
- Distribuição por FII ajuda a manter uma carteira equilibrada  
- Cenários permitem comparar diferentes horizontes de investimento  

## 🔧 Melhorias Futuras

Embora a planilha já possua seleção automática de perfil e gráficos de alocação, outras melhorias podem ser implementadas:

- Gráficos de evolução do patrimônio ao longo do tempo  
- Aba adicional com histórico de simulações  

## 🚀 Como Usar

1. Baixe o arquivo `Simulador_investimento.xlsx`  
2. Abra no Excel  
3. Preencha os campos de entrada (salário, aporte, tempo, taxa)  
4. Escolha o perfil desejado  
5. Visualize os resultados e gráficos gerados automaticamente  

## 📌 Requisitos

- Microsoft Excel 2016 ou superior  
- Conhecimento básico em fórmulas e funções  

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e compartilhar.

---
