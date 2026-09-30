# 📊 Análise de Cancelamento de Clientes com Python

Projeto prático desenvolvido durante a **Jornada Python** (Aula 02), com o objetivo de analisar uma base de dados de clientes de uma empresa fictícia para identificar padrões, entender os principais motivos de cancelamento (Churn) e propor reduções estratégicas nessa taxa.

---

## 🚀 Tecnologias e Bibliotecas Utilizadas
O projeto foi inteiramente construído em Python utilizando o ambiente do Jupyter Notebook / Google Colab e as seguintes bibliotecas:
* **Pandas**: Para importação, manipulação, limpeza e tratamento dos dados.
* **Plotly Express**: Para a criação de gráficos interativos e análise visual avançada.
* **Nbformat**: Suporte auxiliar para renderização de gráficos estruturados.

---

## 📈 Etapas do Projeto

1. **Importação e Limpeza Inicial:** Leitura da base de dados `.csv` e remoção de colunas irrelevantes (como o ID do cliente).
2. **Tratamento de Dados:** Identificação e remoção de linhas vazias (`dropna`) para padronização da base.
3. **Análise Exploratória da Taxa de Cancelamento:** Constatação inicial de que mais de **56%** dos clientes estavam cancelando o serviço.
4. **Filtros e Descobertas Estratégicas:**
   * **Contratos Mensais:** Identificado que praticamente 100% dos clientes com contratos mensais cancelavam o serviço.
   * **Chamadas ao Call Center:** Constatado que clientes que ligavam mais de 5 vezes para o suporte cancelavam as assinaturas.
   * **Dias de Atraso:** Identificado que clientes com mais de 20 dias de atraso no pagamento encerravam o contrato.
5. **Resultado Final:** Após os tratamentos e filtros baseados nas dores do cliente, a taxa de cancelamento foi reduzida drasticamente para níveis aceitáveis e realistas para a operação da empresa.

---

## 📂 Estrutura dos Arquivos
* `analise_cancelamentos.ipynb`: Notebook contendo todo o passo a passo do código executável.
* `cancelamentos.csv`: Base de dados utilizada para a análise *(Nota: certifique-se de adicionar o arquivo `.csv` no diretório do seu projeto para rodar o código)*.

---

## 🛠️ Como Executar o Projeto

1. Faça o download ou clone este repositório.
2. Abra o arquivo `.ipynb` no **Google Colab** ou no **VS Code** (com suporte ao Jupyter).
3. Certifique-se de fazer o upload do arquivo `cancelamentos.csv` para o ambiente de execução.
4. Execute as células sequencialmente.

---
*Projeto replicado para fins de estudo e portfólio em Ciência de Dados.*
