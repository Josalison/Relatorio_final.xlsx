# 📊 Análise de Faturamento por Produto

Este projeto realiza a extração, limpeza e tratamento de dados de vendas utilizando Python e a biblioteca Pandas. Após a consolidação dos dados brutos, um relatório limpo é gerado para alimentar um dashboard interativo no Power BI.

---

## 🚀 Tecnologias Utilizadas

* **Python 3** (Lógica principal de programação)
* **Pandas** (Tratamento de dados, ordenação e tabelas dinâmicas)
* **Jupyter Notebook** (Ambiente de desenvolvimento e testes)
* **Power BI** (Visualização de dados e criação de gráficos)

---

## 🛠️ O que o Script Python Faz?

1. **Importação dos Dados**: Abre e lê as tabelas brutas de vendas originais.
2. **Cálculo Matemática**: Cria a coluna de `Faturamento total` multiplicando a quantidade pelo preço unitário de cada item.
3. **Agrupamento Dinâmico (`groupby`)**: Consolida o faturamento total e ordena os produtos do mais vendido para o menos vendido.
4. **Tratamento de Bugs de Data**: Converte os campos de data no Pandas e remove o excesso de zeros (`00:00:00`) usando o acessador `.dt.date`, gerando uma coluna limpa de datas para o relatório.
5. **Exportação**: Limpa a memória de arquivos pesados e gera o arquivo final `Relatorio_final.xlsx`.

---

## 📊 Visualização no Power BI

Com o arquivo tratado gerado pelo Python, os dados foram integrados ao Power BI para a criação de um gráfico de colunas empilhadas, permitindo monitorar com precisão a performance de faturamento de cada produto:
<img width="980" height="593" alt="image" src="https://github.com/user-attachments/assets/f4e06f76-dbbc-4ae0-8ee8-e24a96ad258a" />


* **Notebook** (Líder de faturamento)
* **Monitor 24"**
* **Teclado Mecânico**
* **Mouse Gamer**

---

## 📁 Estrutura do Repositório

* `table_manipulation.ipynb`: Código-fonte Jupyter com toda a lógica em Pandas.
* `requirements.txt`: Bibliotecas necessárias para rodar o projeto.
* `.gitignore`: Configuração para impedir o upload de arquivos locais pesados (`.xlsx` e `.pbix`) para o GitHub.
* `README.md`: Documentação do projeto.
