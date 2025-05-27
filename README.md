🩺 Análise de Dados — PNAD COVID (Tech Challenge)
Este projeto foi desenvolvido como parte do Tech Challenge da pós-graduação em Data Analytics, com o objetivo de analisar o comportamento da população brasileira durante a pandemia da COVID-19, utilizando dados da PNAD COVID disponibilizados pelo IBGE.

🎯 Objetivo
Você foi contratado por um grande hospital para ajudar na compreensão dos efeitos da pandemia na sociedade, de forma a subsidiar estratégias futuras. A análise parte de três eixos principais:

Características clínicas dos sintomas

Perfil demográfico da população

Impactos econômicos e comportamentais

🛠️ Tecnologias utilizadas
Python (Pandas e PySpark)

Power BI para visualização interativa dos insights

Jupyter Notebook para documentação e execução do processo

🧾 Etapas do projeto
Leitura e Unificação dos Dados
Três arquivos CSV com os dados brutos foram carregados e combinados em uma base única.

Tratamento e Limpeza
Aplicação dos dicionários oficiais do IBGE para tornar os dados legíveis e interpretáveis.

Análise Exploratória (EDA)
Avaliação de sintomas, doenças pré-existentes, testes realizados, hospitalizações, entre outros.

Visualização e Insights no Power BI
Criação de dashboards interativos com os principais achados.

📌 Principais perguntas respondidas
Quais sintomas mais comuns foram relatados?

Qual o perfil das pessoas que buscaram atendimento médico?

Como o desemprego e o auxílio emergencial impactaram a população?

Existe correlação entre comorbidades e hospitalizações?

📊 Resultados e Dashboard
O dashboard desenvolvido no Power BI apresenta os insights de forma visual e acessível. Ele inclui filtros por estado, idade, sexo, sintomas e muito mais.

Caso queira visualizar o dashboard ou replicar o projeto, você pode abrir o arquivo POWER BI - PNAD COVID.pbix com o Power BI Desktop.

📁 Estrutura do repositório
bash
Copiar
Editar
├── Pos Tech Pnad Covid.ipynb   # Notebook com a análise completa (Python + PySpark)
├── POWER BI - PNAD COVID.pbix  # Dashboard interativo com os resultados
├── data/                       # (Opcional) Diretório para os arquivos CSV utilizados
└── README.md                   # Documentação do projeto
