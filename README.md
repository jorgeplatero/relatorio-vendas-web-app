# Aplicativo Web com Relatório de Vendas

Este projeto consiste em um aplicativo web com relatório de vendas realizado em curso de Streamlit da Alura. O aplicativo permite a exploração de dados históricos e acompanhamento de indicadores de desempenho.

### Pré-requisitos

Certifique-se de ter o Python 3.11 instalado em seu sistema.

Para sistemas baseados em Linux (Ubuntu/Debian), instale o suporte ao ambiente virtual:

```bash
sudo apt update && sudo apt install python3.11-venv
```

### Instalação

Siga os passos abaixo para configurar o ambiente e instalar as dependências:

```bash
#clonar o repositório
git clone https://github.com/jorgeplatero/alura-dashboard-vendas.git
cd alura-dashboard-vendas

#criar o ambiente virtual
python -m venv venv

#ativar o ambiente virtual
# No Linux/Mac:
source venv/bin/activate
# No Windows:
venv\Scripts\activate

#instalar as dependências
pip install -r requirements.txt
```

### Como Rodar a Aplicação

Com o ambiente virtual ativado, execute o comando abaixo para iniciar o aplicativo localmente:

```bash
streamlit run app.py
```

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **Frontend/App** | **Streamlit** | `1.32.2` | Framework utilizado para o desenvolvimento do aplicativo web |
| **Análise de Dados** | **Pandas** | `2.2.1` | Biblioteca utilizada para manipulação de dados |
| **Visualização** | **Plotly** |`5.20.0` | Biblioteca para criação de gráficos dinâmicos e dashboards |
| **Linguagem** | **Python** | `>=3.11` | Linguagem de programação base para o desenvolvimento dos scripts |
| **Gerenciamento** | **Venv** | `-` | Gerenciador de pacotes e ambientes virtuais utilizado para garantir a reprodutibilidade das dependências do projeto |

### Fonte de Dados

O aplicativo está configurado para consumir as bases de dados de vendas utilizadas no treinamento e disponíveis neste repositório.

### Deploy

O aplicativo web está disponível via Streamlit Cloud.

Link para o aplicativo: https://aluradashboardvendas.streamlit.app/
