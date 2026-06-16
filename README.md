# Predição de Diabetes utilizando Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E?logo=scikit-learn&logoColor=white)

## 📌 Visão Geral do Projeto

Este projeto tem como objetivo desenvolver um agente inteligente capaz de prever o diagnóstico de diabetes com base em dados clínicos de pacientes. A motivação principal é explorar como a Inteligência Artificial pode ser aplicada na área da saúde para auxiliar na detecção precoce de doenças, melhorando a qualidade de vida e o direcionamento médico.

O projeto abrange desde a ingestão e tratamento dos dados, passando pela Análise Exploratória de Dados (EDA) com mapas de calor e gráficos de dispersão, até o treinamento e avaliação de um modelo de **Regressão Logística**.

---

## ⚙️ Arquitetura e Pipeline de Dados

O fluxo de desenvolvimento do modelo preditivo segue a esteira de dados ilustrada abaixo:

![](https://mermaid.ink/img/pako:eNpVktFu2jAUhl_FcqUJJGAJIaBEUyUgwC6GVK1cLeHCxCdg1bEj22G0lIepdjH1Yld7hLzYnAza4hsf2___2eeXjziVFHCIt4oUO7SKEpUIZMc4bk2IBkQBRYRK_WWjbikjGzCge6net9eo271Fk_hOVa_dQskUtCY5CCNrKaCVIrSsfle_ZM2YAzGlAr2-8CeNfXoci-qFM3vR7FBwqYip_ipGasQsGp8u6mmtfp5KpYCTBvqMonhJjGJPNf7jCboHspFKrK_NEdNWvSnZ2T6LF6p6yVgqddMk0wUoXftzYuxTDGebawSaxxHbM31u6S0W2ykTn1egDbovODNvrnnjWrRaKwVM_A8HUYmWNnLexPQdtjaUhvhNbqs_2rCUtNsXwKIBfI3He8LZubsr_8cERFY2oE9oWb3a7ZS8p32ZtXnkgMYoY5yHN1mQdWwo8gHCG8_zznX3J6NmF_aLQ-3CHfs1GMWhUSV0cA4qJ_USH2tigs0OckhwaEtK1EOCE3GynoKIH1LmF5uS5XaHw4xwbVdlQYmBiBH76d4lICioqSyFwaHnDBsGDo_4gMO-M-p57sB1g8D3hrbq4Eccdt2eN-gHvusHA3c08v2hd-rgp-Zat-c4Vjpwhs7AcQN36J_-ATXS_4w?type=png)

---

## 📊 O Dataset

O conjunto de dados utilizado contém atributos médicos diagnósticos de pacientes. Para facilitar a legibilidade e manutenção do código, os dados originais foram traduzidos e padronizados para o português:

| Atributo | Descrição |
| :--- | :--- |
| **Gravidezes** | Número de vezes que a paciente engravidou |
| **Glicose** | Concentração de glicose plasmática (teste de tolerância de 2 horas) |
| **PressaoSanguinea** | Pressão arterial diastólica (mm Hg) |
| **EspessuraPele** | Espessura da dobra cutânea do tríceps (mm) |
| **Insulina** | Insulina sérica de 2 horas (mu U/ml) |
| **IMC** | Índice de Massa Corporal (peso em kg / (altura em m)²) |
| **HistoricoFamiliarDiabetes** | Função de linhagem de diabetes (probabilidade genética) |
| **Idade** | Idade da paciente (anos) |
| **Resultado** | Variável alvo (0 = Negativo para Diabetes, 1 = Positivo) |

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (LogisticRegression, train_test_split, metrics)

---

## 🚀 Guia de Instalação e Execução

Para reproduzir este projeto na sua máquina local, siga os passos abaixo:

**1. Clone o repositório:**
```bash
git clone
https://github.com/henriqueserafin/diabetes.git
cd diabetes
```

**2. Recomendo que crie um ambiente virtual:**
```bash
python -m venv venv

# Ativando no Windows:
.\venv\Scripts\activate

# Ativando no Linux/Mac:
source venv/bin/activate
```

**3. Instale as dependências necessárias:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Execute o Jupyter Notebook:**
```bash
jupyter notebook
```
*Após iniciar o Jupyter, abra o arquivo `predicaodiabetes.ipynb` e execute as células sequencialmente.*

---

## 📂 Estrutura do Repositório

```text
diabetes/
├── data/
│   └── diabetes.csv
├── predicaodiabetes.ipynb
└── README.md
```

---

