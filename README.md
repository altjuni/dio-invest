# DIO INVEST - Simulador & Gerenciador de Investimentos

O **DIO INVEST** é uma ferramenta interativa desenvolvida em planilha (Excel/Google Sheets) projetada para auxiliar no planejamento financeiro pessoal, simulação de juros compostos e alocação estratégica em **Fundos Imobiliários (FIIs)** com base no perfil do investidor.

##  Funcionalidades Principais

*  Configurações de Renda & Metas:

  * Definição de salário base e rendimento estimado da carteira.

  * Sugestão automática do valor mensal a ser investido (ex: 30% da renda).

*  **Simulador de Investimento Mensal:**

  * Cálculo de projeção de patrimônio acumulado a longo prazo.

  * Estimativa de dividendos mensais futuros com base na taxa de rendimento configurada.

*  **Análise de Cenários Horizontais:**

  * Comparativo automático de evolução do patrimônio e dividendos em **2, 5, 10, 20 e 30 anos**.

*  **Alocação de Ativos (FIIs):**

  * Sugestão de distribuição percentual e financeira de investimentos divididos por tipos de Fundos Imobiliários:

    * **Papel**

    * **Tijolo**

    * **Híbridos**

    * **FoFs** (Fundos de Fundos)

    * **Desenvolvimento**

    * **Hotelaria**

  * Visualização gráfica em pizza para acompanhar a diversificação da carteira.

##  Estrutura da Planilha

### 1. Configurações Financeiras

| Métrica | Exemplo | 
 | ----- | ----- | 
| **Salário** | R\$ 2.000,00 | 
| **Rendimento da Carteira** | 0,60% ao mês | 
| **Sugestão de Investimento (30%)** | R\$ 600,00 | 

### 2. Projeção por Cenários de Tempo

| Período | Patrimônio Estimado | Dividendo Mensal Estimado | 
 | ----- | ----- | ----- | 
| **2 Anos** | R\$ 5.445,53 | R\$ 32,67 | 
| **5 Anos** | R\$ 16.755,38 | R\$ 100,53 | 
| **10 Anos** | R\$ 48.656,84 | R\$ 291,94 | 
| **20 Anos** | R\$ 225.039,68 | R\$ 1.350,24 | 
| **30 Anos** | R\$ 864.433,93 | R\$ 5.186,60 | 

##  Como Usar

1. Faça o download ou clone este repositório:

   ```
   git clone https://github.com/altjuni/dio-invest.git
   
   ```

2. Abra o arquivo `.xlsx` no **Microsoft Excel** ou importe no **Google Sheets**.

3. Altere os valores na seção **CONFIGURAÇÕES** (Salário e Taxa de Rendimento) e no campo **Quanto investir por mês?**.

4. Acompanhe os resultados gerados automaticamente nos quadros de **Cenários** e no **Gráfico de Alocação por FIIs**.

##  Tecnologias Utilizadas

* **Microsoft Excel**

* **Fórmulas de Juros Compostos**

* **Gráficos Dinâmicos e Formatador Visual**

##  Contribuições

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhoria nas fórmulas, inclusão de novas classes de ativos (Ações, Renda Fixa) ou novos visuais:

1. Faça um *Fork* do projeto.

2. Crie uma *Branch* para sua Feature (`git checkout -b feature/NovaFeature`).

3. Abra um *Pull Request*.
