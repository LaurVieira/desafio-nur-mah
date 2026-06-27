# 🏛️ Inteligência de Mercado - Nur Mah Museum
**Desenvolvido por:** Laura Vieira

##  Sobre o Projeto
Este projeto apresenta uma análise exploratória e preditiva sobre a saúde financeira e a distribuição geográfica de instituições culturais nos Estados Unidos. O objetivo é extrair inteligência dos dados públicos do IMLS para apoiar a estratégia de captação de recursos e parcerias do **Nur Mah Museum**.

##  Principais Insights e Recomendações
Através da análise de dados, foram identificadas três frentes estratégicas:
1. **Metas Realistas:** A captação de recursos deve usar a receita mediana dos Museus de Arte como linha de base (baseline).
2. **Parcerias Estratégicas:** Museus de Ciência e Zoos operam com receitas muito superiores. Sugere-se criar exposições híbridas para atrair fundos desses setores.
3. **Expansão Geográfica:** Focar campanhas de marketing em estados altamente populosos (como CA e NY), mas buscando regiões com menor saturação de concorrência direta.

##  Modelagem Preditiva
Foi desenvolvido um modelo de Machine Learning utilizando o algoritmo **Random Forest Regressor** para estimar a receita de uma instituição com base no seu tipo e estado. 
O modelo serve como um ponto de partida (baseline) e atesta que o sucesso financeiro de um museu depende de variáveis externas ausentes no dataset (como investimento em marketing, turismo local e prestígio).

##  Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, OneHotEncoder)
* **Ambiente:** Jupyter Notebook (VS Code)

##  Estrutura dos Ficheiros
* `analise_nur_mah.ipynb` -> O notebook principal contendo toda a análise, gráficos e modelo de Machine Learning.
* `data/museums.csv` -> A base de dados original utilizada no projeto.
* `README.md` -> Documentação do projeto.

##  Como Executar o Projeto
1. Certifique-se de ter o Python instalado.
2. Abra o ficheiro `analise_nur_mah.ipynb` no VS Code ou Jupyter.
3. A primeira célula do notebook garantirá a instalação das bibliotecas necessárias.
4. Clique em **Run All** (Rodar Tudo) para visualizar as análises e os gráficos gerados.
