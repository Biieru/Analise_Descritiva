# 📊 Análise de Dados de Funcionários - Big Data

## 📋 Descrição do Projeto

Este projeto apresenta uma análise completa de dados de funcionários utilizando técnicas de Data Science e visualização de dados. A análise foi desenvolvida em Python com foco em estatística descritiva, correlações e insights sobre a força de trabalho da empresa.

## 🎯 Objetivos da Análise

O projeto busca responder a 6 perguntas principais sobre os dados dos funcionários:

1. **Distribuição da Idade** - Análise da distribuição etária da força de trabalho
2. **Salário por Estado Civil** - Comparação salarial entre funcionários solteiros e casados
3. **Correlação Idade x Salário** - Relação entre idade e remuneração
4. **Salário por Nível de Instrução** - Impacto da educação na remuneração
5. **Frequência de Estado Civil** - Perfil demográfico dos funcionários
6. **Distribuição de Filhos por Estado Civil** - Análise da composição familiar

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **Matplotlib** - Criação de gráficos
- **Seaborn** - Visualizações estatísticas avançadas
- **Jupyter Notebook** - Ambiente de desenvolvimento

## 📁 Estrutura do Projeto

DB Funcionarios/

├── 📄 Codes.ipynb # Notebook principal com toda a análise feita

├── 📄 Base de Dados Funcionários.csv # Dataset fonte com cerca de 36 funcionários

├── 📋 requeriments.txt # Dependências do projeto para poder rodar os códigos (libs)

└── 📁 venv_funcionarios/ # Ambiente virtual Python (crie o seu venv)


## Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda

### Instalação
```bash
# Clone o repositório
git clone https://github.com/Biieru/Analise_Descritiva

# Navegue para a pasta
cd DB-Funcionarios

# Instale as dependências
pip install -r requeriments.txt

# Ative o ambiente virtual (recomendado)
venv_funcionarios\Scripts\activate  # Windows
source venv_funcionarios/bin/activate  # Linux/Mac
```

### Execução
```bash
# Abra o Jupyter Notebook
jupyter notebook Codes.ipynb

# Ou execute no VS Code com extensão Python
```

## Dataset

O arquivo `Base de Dados Funcionários.csv` contém informações sobre:
- **36 funcionários** da empresa
- **Variáveis**: ID, Estado Civil, Instrução, Filhos, Salário, Idade, Meses de Empresa, Região
- **Período**: Dados atualizados com informações demográficas e salariais

## 📈 Principais Descobertas

###  Educação e Salário
- Funcionários com ensino superior apresentam salários significativamente maiores
- Existe uma correlação positiva clara entre nível de instrução e remuneração

###  Perfil Demográfico
- **Estado Civil**: 55.6% casados, 44.4% solteiros
- **Idade**: Distribuição entre 20-48 anos, com média equilibrada
- **Família**: Todos os solteiros não possuem filhos

###  Fatores Salariais
- **Idade**: Correlação positiva moderada com salário
- **Estado Civil**: Diferenças salariais entre grupos
- **Experiência**: Meses de empresa influenciam remuneração

##  Metodologia

1. **Exploração dos Dados** - Análise inicial e limpeza
2. **Visualização** - Gráficos estatísticos com matplotlib/seaborn
3. **Análise Estatística** - Correlações, médias e distribuições
4. **Interpretação** - Insights baseados nos dados
5. **Documentação** - Respostas detalhadas para cada pergunta

## 📚 Bibliotecas Principais

- **Pandas**: Manipulação e análise de dados
- **Matplotlib**: Criação de gráficos básicos
- **Seaborn**: Visualizações estatísticas avançadas
- **SciPy**: Testes estatísticos (ANOVA)

## 🎨 Tipos de Gráficos Utilizados

- **Histogramas** - Distribuição de variáveis contínuas
- **Boxplots** - Comparação entre grupos
- **Scatterplots** - Relações entre variáveis
- **Gráficos de Pizza** - Proporções e frequências
- **Gráficos de Barras** - Contagens e comparações

## 📝 Conclusões

A análise revela uma empresa com:
- Força de trabalho diversificada em termos de idade e instrução
- Política salarial que valoriza educação e experiência
- Perfil demográfico equilibrado entre solteiros e casados
- Correlações significativas entre variáveis demográficas e salariais

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:
1. Faça um fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Seu Nome**
- GitHub: [Biieru](https://github.com/Biieru)
- LinkedIn: [Gabriel C Araujo](https://linkedin.com/in/GabrielCAraujo)
- Em qualquer outra rede: @Bordercansado

⭐ **Se este projeto foi útil, considere dar uma estrela no GitHub!**
