Análise Exploratória de Dados (EDA) — Carga de Energia do ONS (2015–2025)
Este projeto realiza uma análise exploratória detalhada sobre o comportamento da carga energética brasileira na última década, utilizando dados oficiais do Operador Nacional do Sistema Elétrico (ONS). A análise busca identificar padrões sazonais, tendências de crescimento e anomalias nos quatro subsistemas do Sistema Interligado Nacional (SIN).

📑 Contexto do Problema
O ONS é responsável pela coordenação e controle da geração e transmissão de energia elétrica no Brasil. A carga energética, expressa em MWmed (Megawatts médios), representa a demanda total consumida ao longo de um dia. Compreender esses dados é fundamental para garantir a segurança operacional e o planejamento do setor elétrico brasileiro.

🚀 Tecnologias Utilizadas
Python 3.14+

Pandas: Manipulação e limpeza de dados.

Matplotlib & Seaborn: Visualização de dados e plotagem de séries temporais.

NumPy: Suporte matemático e computacional.

Jupyter Notebook: Ambiente de desenvolvimento da análise.

## 📁 Estrutura do Projeto

```text
EDA_TASK/
├── CsvDados/        # Arquivos CSV originais do ONS (2015-2025)
├── Graficos/        # Visualizações exportadas (.png)
├── notebook/
│   └── eda.ipynb    # Notebook com a análise completa
├── .gitignore       # Configurações de exclusão do Git
├── requirements.txt # Dependências do projeto
└── README.md        # Documentação do projeto
````

📊 Principais Insights
Dominância Regional: O subsistema Sudeste/Centro-Oeste detém a maior carga média do país, com picos superiores a 55k MWmed em 2025, refletindo sua alta densidade industrial e populacional.

Sazonalidade Térmica: Identificou-se que os maiores picos de carga ocorrem sistematicamente durante o verão, fortemente correlacionados ao uso de sistemas de climatização.

Crescimento Estrutural: Através da aplicação de médias móveis de 30 dias, observou-se que valores anteriormente considerados outliers no subsistema Sul agora representam um novo patamar de demanda estrutural.

Qualidade dos Dados: A análise isolou uma anomalia técnica no subsistema Nordeste em agosto de 2018, demonstrando a importância de diferenciar falhas de medição de eventos reais do sistema.

## 🛠️ Como Executar

Clone o repositório:

```bash
git clone https://github.com/Joaovinicius4/EdaEnergia.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook notebook/eda.ipynb
```

## 📝 Conclusões

A análise demonstra que o sistema elétrico brasileiro está em expansão contínua. A combinação de métodos estatísticos com interpretação temporal foi essencial para validar o crescimento real da demanda frente às anomalias pontuais de medição.

---
**Desenvolvido por João Vinicius**  
*Estudante de Sistemas de Informação - Unimontes*
