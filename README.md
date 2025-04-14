
# 🐍📊 Análise de Dados com PokéAPI

Este projeto em Python consome dados da PokéAPI para realizar análises estatísticas e gerar visualizações sobre os Pokémon, utilizando bibliotecas como `pandas`, `numpy` e `matplotlib`.

## 🔍 Sobre o Projeto

O objetivo deste projeto é:

1. **Consumir dados da PokéAPI**: Obter informações detalhadas sobre os Pokémon.
2. **Estruturar os dados**: Utilizar `pandas` para organizar os dados em dataframes.
3. **Transformar os dados**: Classificar os Pokémon em categorias como fortes, médios e fracos.
4. **Visualizar os dados**: Gerar gráficos que mostram a distribuição dos Pokémon por tipo.
5. **Analisar estatísticas**: Calcular médias de ataque, defesa e HP, além de identificar os 5 Pokémon com maior experiência.
6. **Gerar relatórios**: Exportar as análises estatísticas para arquivos CSV.

## 🛠️ Tecnologias Utilizadas

- Python 3
- Bibliotecas:
  - `requests`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `json`
  - `IPython`
- Docker (para ambiente isolado de execução)

## 📁 Estrutura do Projeto

- `Main.py`: Script principal que executa todas as etapas do projeto.
- `5MaioresExperienciabase.csv`: Arquivo CSV com os 5 Pokémon de maior experiência.
- `MediasPokemonPorTipo.csv`: Arquivo CSV com as médias de ataque, defesa e HP por tipo de Pokémon.
- `Grafico distribuição pokemon por tipo.png`: Gráfico gerado mostrando a distribuição dos Pokémon por tipo.
- `execucao.log`: Log da execução do script.

## 🚀 Como Executar

### Pré-requisitos

- Docker instalado na máquina.

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/LarisMorais/PokeAPI.git
   cd PokeAPI
   ```

2. Construa a imagem Docker:

   ```bash
   docker build -t pokeapi-analise .
   ```

3. Execute o container:

   ```bash
   docker run --rm -v "$(pwd):/app" pokeapi-analise
   ```

   Isso executará o script `Main.py` dentro do container Docker, e os arquivos de saída serão gerados no diretório atual.

## 📬 Contato

Se desejar entrar em contato, você pode me encontrar em:

- [LinkedIn](https://www.linkedin.com/in/larissamorais26/)
- [GitHub](https://github.com/LarisMorais)
- Email: larismorais26@gmail.com
