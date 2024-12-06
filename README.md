# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="https://raw.githubusercontent.com/lfusca/templateFiap/main/assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

## Construindo uma máquina agrícola

## 👨‍🎓 Integrantes do grupo

- RM559645 - [Edimilson Ribeiro](https://www.linkedin.com/in/edimilson-ribeiro/)
- RM560173 - [Gabriel Ribeiro](https://www.linkedin.com/in/ribeirogab/)
- RM559800 - [Jonas Felipe dos Santos Lima](https://www.linkedin.com/in/jonas-felipe-dos-santos-lima-b2346811b/)
- RM560461 - [Jose Antonio Correa Junior](https://www.linkedin.com/in/jacorrea/)
- RM559926 - [Marcos Trazzini](https://www.linkedin.com/in/mstrazzini/)

## 👩‍🏫 Professores

### Tutor(a)

- [Lucas Gomes Moreira](https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/)

### Coordenador(a)

- [André Godoi](https://www.linkedin.com/in/profandregodoi/)

---

## 📜 Descrição

Este projeto aplica aprendizado de máquina para automatizar a classificação de grãos de trigo em cooperativas agrícolas de pequeno porte, onde o processo é tradicionalmente manual. Utilizando o conjunto de dados "Seeds Dataset" do UCI Machine Learning Repository, o objetivo foi desenvolver e comparar modelos de classificação para identificar as variedades de grãos: Kama, Rosa e Canadian.

### Funcionalidades principais

- Análise e pré-processamento de dados: Exploração e limpeza do conjunto de dados.
- Implementação de algoritmos de classificação: Comparação entre os modelos K-Nearest Neighbors (KNN), Random Forest e Support Vector Machine (SVM).
- Otimização de hiperparâmetros: Uso de Grid Search para melhorar o desempenho.
- Interpretação dos resultados: Insights relevantes sobre o desempenho dos modelos e desafios de classificação.

## 📁 Estrutura de pastas

* notebook: Contém o notebook com a implementação principal:

* data: Conjunto de dados utilizado no projeto:

## 🔧 Como executar

### Configuração inicial

1. Clone este repositório:

   ```bash
   git clone git@github.com:FIAP-IA2024/grain-classification.git
   cd grain-classification
   ```

2. Crie e ative um ambiente virtual Python:

   - **Linux/macOS:**

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

   - **Windows:**

     ```cmd
     python -m venv venv
     venv\Scripts\activate
     ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute o notebook localmente:

   ```bash
   jupyter notebook notebook/Fase4_Cap3.ipynb
   ```

### Execução no Google Colab

Caso prefira executar o projeto diretamente no Google Colab, acesse o link abaixo:

[**Rodar no Colab**](https://colab.research.google.com/drive/1Xdi5hKmg9ofE0R-0yTU2vdVPlpFPp3dG?usp=sharing)

---

## 📊 Resultados

* O modelo SVM obteve a melhor acurácia (92%), demonstrando consistência e robustez na classificação das três variedades de grãos.

* A análise destacou que a Classe Rosa foi a mais facilmente identificada por todos os modelos, enquanto Kama e Canadian apresentaram desafios devido às características similares.

* A otimização dos modelos não trouxe ganhos significativos, reforçando que os hiperparâmetros iniciais já estavam bem ajustados.

### Visualizações geradas

* Matriz de Correlação

* Boxplots

## 💻 Tecnologias utilizadas

* Linguagem: Python
* Bibliotecas principais:
    * pandas e numpy: Manipulação de dados.
    * matplotlib e seaborn: Visualização de dados.
    * scikit-learn: Implementação de algoritmos de Machine Learning.

---

## 📋 Licença

Este projeto segue o modelo de licença da FIAP e está licenciado sob **Attribution 4.0 International**. Para mais informações, consulte o [MODELO GIT FIAP](https://github.com/agodoi/template).
