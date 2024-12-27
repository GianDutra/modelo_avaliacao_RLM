# Modelo de Previsão de Desempenho Acadêmico

---

<img src="./.github/modelo_avaliacao.png" alt="modelo_avaliacao" title="Modelo de Previsão de Desempenho Acadêmico">

---

## Tecnologias Utilizadas

### Linguagem de Programação

- [Python](https://www.python.org/) (v3.11.0)

### Gerenciadores de Ambiente Virtual

- [Pyenv](https://github.com/pyenv/pyenv)
- [Pipenv](https://pipenv.pypa.io/en/latest/)

### Principais Bibliotecas (Packages)

- [scikit-learn](https://scikit-learn.org/stable/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [joblib](https://joblib.readthedocs.io/en/latest/)
- [gradio](https://gradio.app/)

---

## Visão Geral do Projeto

Este projeto tem como objetivo criar um modelo de predição para estimar o desempenho acadêmico de um estudante com base em diferentes variáveis, como horas de estudo, pontuação anterior, atividades extracurriculares, horas de sono e simulados resolvidos. O modelo foi desenvolvido utilizando regressão linear múltipla, e a interface foi criada com Gradio para facilitar a interação e realização de predições.

### Principais Etapas do Projeto:
- **Exploração de Dados**: Análise exploratória utilizando gráficos, como dispersão e histogramas, para entender as correlações entre as variáveis.
- **Construção e Treinamento do Modelo**: Treinamento de um modelo de regressão linear múltipla utilizando o scikit-learn.
- **Testes Estatísticos**: Realização de testes de normalidade e homocedasticidade dos resíduos, como Anderson-Darling e Goldfeld-Quandt, para garantir a qualidade do modelo.
- **Interface com Gradio**: Criação de uma interface interativa com o Gradio, permitindo que os usuários insiram valores e obtenham previsões de desempenho acadêmico.

---

## Como Executar o Projeto

**Pré-requisitos**:
- Certifique-se de que o **Python** esteja instalado em sua máquina. Caso contrário, baixe em [python.org](https://www.python.org/downloads/).

**Instalando o Projeto**:

1. Clone o repositório:
    ```bash
    git clone https://github.com/SEU_USUARIO/modelo_avaliacao.git
    cd modelo_avaliacao
    ```

2. Configure o ambiente virtual com `pipenv`:
    ```bash
    pipenv install
    pipenv shell
    ```

3. Execute o aplicativo Gradio:
    ```bash
    python app.py
    ```

4. Acesse a interface interativa em:
    ```
    http://127.0.0.1:7860/
    ```

---

## Funcionalidades Implementadas

### Modelo de Machine Learning
- Criação de um modelo de regressão linear múltipla para prever o desempenho acadêmico.
- Avaliação do modelo com métricas como RMSE, análise de resíduos e testes estatísticos (Anderson-Darling e Goldfeld-Quandt).

### Testes Estatísticos
- **Testes de Normalidade**: Anderson-Darling para verificar se os resíduos seguem uma distribuição normal.
- **Testes de Homocedasticidade**: Goldfeld-Quandt para verificar se a variância dos resíduos é constante.

### Interface com Gradio
- Interface interativa para permitir que os usuários insiram dados e obtenham previsões de forma rápida e fácil.
- Personalização com sliders para ajustar variáveis contínuas e radio buttons para variáveis categóricas.

---

## 👨‍💼 Autor

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://github.com/giandutra.png" width="100px;" alt="Foto do Autor no GitHub"/><br>
        <sub>
          <b>SEU NOME</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
