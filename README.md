# Aplicativo Web com Relatório de Vendas

Este projeto consiste em um aplicativo web com relatório de vendas realizado em curso de Streamlit da Alura. O aplicativo permite a exploração de dados históricos e acompanhamento de indicadores de desempenho.

### Pré-requisitos

Certifique-se de ter o Python 3.11 instalado em seu sistema.

Instale o suporte ao ambiente virtual:

```bash
sudo apt update && sudo apt install python3.11-venv
```

### Instalação

Siga os passos abaixo para configurar o ambiente e instalar as dependências:

```bash
#clonar o repositório
git clone https://github.com/jorgeplatero/alura-dashboard-vendas.git
cd relatorio-vendas-web-app

#criar o ambiente virtual
python -m venv venv

#ativar o ambiente virtual
source venv/bin/activate

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
| **Frontend/App** | **Streamlit** | `1.32.2` | Framework para desenvolvimento de aplicativo web |
| **Análise de Dados** | **Pandas** | `2.2.1` | Biblioteca para manipulação de dados |
| **Visualização** | **Plotly** |`5.20.0` | Biblioteca para criação de gráficos dinâmicos e interativos |
| **Linguagem** | **Python** | `>=3.11` | Linguagem para desenvolvimento de scripts |
| **Gerenciamento** | **Venv** | `-` | Gerenciador de ambientes virtuais para isolamento de dependências |

### Fonte de Dados

O aplicativo está configurado para consumir as bases de dados de vendas utilizadas no treinamento e disponíveis neste repositório.

### Deploy

O aplicativo web está disponível via Streamlit Cloud.

Link para o aplicativo web: https://aluradashboardvendas.streamlit.app/
