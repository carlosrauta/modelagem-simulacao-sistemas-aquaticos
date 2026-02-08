# Modelagem e Simulação de Sistemas Aquáticos

## Informações Gerais

- **Disciplina:** Modelagem e Simulação de Sistemas Aquáticos  
- **Curso:** Engenharia de Pesca  
- **Carga Horária:** 110 horas  

---

## Ementa

Modelagem matemática discreta e contínua de sistemas dinâmicos aplicada à pesca e à aquicultura. Simulação numérica utilizando Python. Modelos de crescimento biológico e dinâmica de estoques pesqueiros. Balanço de massa e energia em sistemas de produção aquícola, com ênfase em sistemas de recirculação (RAS). Mecânica e hidrodinâmica de petrechos de pesca. Validação de modelos matemáticos por meio de dados de campo e de laboratório.

---

## Objetivos

Ao final do curso, o aluno deverá ser capaz de:

- Abstrair e modelar fenômenos biológicos e físicos do ambiente aquático, como crescimento de peixes e depleção de oxigênio.
- Desenvolver scripts em Python para resolver equações diferenciais e a diferenças que descrevem sistemas pesqueiros e aquícolas.
- Validar modelos matemáticos utilizando dados reais de biometria e monitoramento ambiental.
- Simular cenários de manejo, como o impacto de diferentes níveis de esforço de pesca sobre a biomassa.
- Comunicar resultados técnicos por meio de relatórios científicos e visualizações de dados.

---

## Conteúdo Programático

### 1. Fundamentos e Dinâmica Discreta

- Taxas de variação em sistemas biológicos: natalidade, mortalidade e recrutamento  
- Diagramas de estoques e fluxos: representação de ciclos de nutrientes e biomassa  
- Equações a diferenças: modelos de crescimento populacional discreto  
  - Crescimento geométrico  
  - Crescimento logístico  
- Matrizes de Leslie: modelagem de populações estruturadas por idade  
  - Aplicações de álgebra linear  

### 2. Modelagem Biológica e Pesqueira

- Modelos de dinâmica de populações  
  - Modelo de Schaefer (produção excedente)  
  - Modelo de Fox  
- Equação de crescimento de von Bertalanffy  
  - Modelagem contínua do comprimento e do peso ao longo do tempo  
- Sistemas de predação  
  - Equações de Lotka–Volterra aplicadas a ecossistemas aquáticos  

### 3. Modelagem de Sistemas de Aquicultura
- Balanço de oxigênio dissolvido  
  - Consumo respiratório versus aeração  
- Sistemas de Recirculação Aquícola (RAS)  
  - Modelagem da remoção de amônia e nitrito  
- Transferência de calor  
  - Modelagem térmica em tanques e no transporte de peixes vivos  

### 4. Mecânica e Hidrodinâmica Aplicadas

- Diagramas de corpo livre em petrechos de pesca  
  - Forças atuantes em redes de arrasto (arrasto e sustentação)  
- Equações diferenciais de segunda ordem  
  - Movimento de cabos e comportamento hidrodinâmico de portas de arrasto  
- Cálculo vetorial aplicado  
  - Determinação de tensões em sistemas de fundeio de tanques-rede  

### 5. Simulação Numérica com Python

- Uso de bibliotecas NumPy e Matplotlib  
- Resolução de equações diferenciais ordinárias (ODEs)  
  - `scipy.integrate.solve_ivp`  
- Métodos numéricos  
  - Método de Euler  
  - Métodos de Runge–Kutta  
- Aplicações em modelos de pesca e aquicultura  

---

## Bibliografia Sugerida

### Básica

- SPARRE, P.; VENEMA, S. C. *Introdução à avaliação de mananciais de peixes tropicais*. FAO.  
- BISWAS, K. P. *Design Construction and Uses of Trawal Fishing Gear *.  
- ZILL, D. G. *Equações Diferenciais com Aplicações em Modelagem*. Cengage Learning, 2016
- TIMMONS, M. B.; EBELING, J. M. *Recirculating Aquaculture*.  

### Complementar

- DOWNEY, A. B. *Pense em Python*. Novatec, 2016.   
- HILBORN, R.; WALTERS, C. J. Quantitative Fish Stock Assessment.  
- MEADOWS, D. *Pensando em sistemas: Como o pensamento sistêmico pode ajudar a resolver os grandes problemas globais*.  
