# 🎯 Projeto Lotofácil – Análise Estatística e Geração de Jogos

Este projeto tem como objetivo realizar uma análise estatística completa da Lotofácil com base em todos os concursos disponíveis, e, a partir dessa análise, gerar jogos otimizados com maior probabilidade de acerto.

## 📁 Estrutura

- `data/`: Base de dados original (arquivo .xlsx da Lotofácil)
- `notebooks/`: Jupyter notebooks com as análises e scripts
- `outputs/`: Arquivos gerados, como gráficos e os 30 jogos finais
- `README.md`: Este arquivo
- `requirements.txt`: Bibliotecas utilizadas

## 🧠 Etapas do Projeto

1. **Análise Exploratória**: Frequência de dezenas, distribuição ímpar/par, soma, heatmaps, etc.
2. **Fechamento com 18 dezenas**: Geração de 30 jogos com pelo menos 13 pontos garantidos se 15 estiverem entre as 18.
3. **Verificação dos resultados**: Script que confere se os jogos gerados acertaram nos concursos seguintes.
4. **Análise parametrizada**: Foco nos últimos `n` concursos, como os 100 mais recentes.

## 📊 Exemplos de Análises

- Frequência absoluta e relativa das dezenas
- Heatmaps por linha e coluna do volante
- Distribuição par/impar
- Soma total das dezenas
- Gráfico comparativo entre frequência histórica e dezenas do fechamento

## 🛠️ Tecnologias

- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

## 🚀 Como usar

1. Clone o repositório:
git clone https://github.com/ccaio89/analise-lotofacil.git

2. Instale os pacotes
pip install -r requirements.txt

3. Execute os notebooks na pasta `notebooks/`.

## 📌 Autor

Caio – Engenheiro de Dados | Estatístico  
