# ciencias-de-dados-com-python
Dashboard interativo utilizando python e streamlit


# 📊 Dashboard de Salários na Área de Dados  

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

Um **dashboard interativo** desenvolvido em **Python** com **Streamlit**, **Pandas** e **Plotly**, criado para explorar dados salariais no setor de dados, permitindo filtrar e visualizar informações de forma simples, intuitiva e visualmente atraente.

---

## 🚀 Acesse meu Projeto Online

[📊 Acesse o App no Streamlit](https://ciencias-de-dados-com-python.streamlit.app/)

---

## 🚀 Funcionalidades

✅ Filtros interativos (Ano, Senioridade, Contrato e Tamanho da Empresa)  
✅ KPIs (Média Salarial, Máximo, Total de Registros e Cargo mais frequente)  
✅ Gráficos interativos com Plotly:  
- 📌 **Top 10 cargos por salário médio**  
- 📊 **Distribuição salarial**  
- 🥧 **Proporção de trabalho remoto/presencial**  
- 🌍 **Mapa de salários médios por país para Cientistas de Dados**  
✅ Exibição da base de dados filtrada  

---

## 🖼 Prévia do Dashboard

> *(adicione um print ou GIF do seu app rodando)*  

---

## 📂 Estrutura do Projeto

```
📁 dashboard-salarios
│
├── app.py                  # Código principal do dashboard
├── dados_imersao_final.csv # Dataset (ou link para o GitHub)
├── requirements.txt        # Dependências do projeto
└── README.md               # Documentação do projeto

```

---

## 🔧 Tecnologias Utilizadas

- **Python 3.10+**
- **Streamlit** → Criação da interface interativa
- **Pandas** → Manipulação e filtragem de dados
- **Plotly Express** → Visualizações interativas
- **CSV online (GitHub)** → Fonte de dados hospedada

---

## 📦 Instalação e Execução

Clone o repositório:
```bash

git clone https://github.com/fabinhoz/ciencias-de-dados-com-python.git

cd ciencias-de-dados-com-python
```

Crie um ambiente virtual e instale as dependências:
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

pip install -r requirements.txt
```

Execute o app:
```bash
streamlit run app.py
```

O dashboard abrirá automaticamente no navegador em:
```
http://localhost:8501
```

---

## 📊 Fonte dos Dados

O dataset foi obtido a partir da [Imersão Dados](https://www.alura.com.br/), contendo informações salariais do setor de dados em diferentes países, cargos, senioridades e formatos de contrato.

---

## 🤝 Contribuição

Contribuições são bem-vindas!  
Para contribuir:
1. Faça um **fork** do projeto  
2. Crie uma **branch** (`git checkout -b feature/nova-funcionalidade`)  
3. Faça o commit (`git commit -m 'Adicionei nova funcionalidade'`)  
4. Faça o **push** (`git push origin feature/nova-funcionalidade`)  
5. Abra um **Pull Request**  

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — sinta-se livre para usá-lo e modificá-lo.

---

💡 *Feito por fabinhoz com Python, Café ☕ e muita curiosidade por dados.*

