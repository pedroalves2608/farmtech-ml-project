# Fase 5 – Machine Learning na Cabeça – FarmTech Solutions

Projeto da **Entrega 1** da Fase 5: solução de Machine Learning para previsão de rendimento de safra e análise de tendências de produtividade em uma fazenda de médio porte (~200 ha) da FarmTech Solutions.

## Objetivo

- **Análise exploratória** do dataset de condições de solo e temperatura vs. tipo de cultura.
- **Clusterização** para tendências de produtividade e identificação de cenários discrepantes (outliers).
- **Cinco modelos de regressão** (algoritmos distintos) para prever o rendimento da safra, com avaliação por métricas pertinentes.

O passo a passo completo da solução, análises e conclusões está no **notebook Jupyter** abaixo.

## Como executar

1. Clone este repositório.
2. (Opcional) Instale as dependências: `pip install -r requirements.txt`
3. Coloque o arquivo `crop_yield.csv` (disponível no portal da disciplina) na pasta `data/`. Se já houver um arquivo de exemplo, você pode substituí-lo pelo dataset oficial.
4. Abra o notebook em:
   - **Jupyter Notebook/Lab**, ou
   - **VS Code** (extensão Jupyter), ou
   - **Google Colab** (upload do `.ipynb` e do CSV).
5. Execute as células em ordem (Kernel → Restart & Run All). Antes da entrega, execute todas as células para que os outputs fiquem salvos.

**Link para o notebook:** [notebooks/pbl_fase4.ipynb](notebooks/pbl_fase4.ipynb)

Antes da entrega, renomeie o arquivo do notebook para: `SeuNomeCompleto_rmXXXXX_pbl_fase4.ipynb` (ex.: `JoaoSantos_rm76332_pbl_fase4.ipynb`), conforme orientação do enunciado.

## Vídeo demonstrativo

**[Inserir aqui o link do vídeo no YouTube (não listado), com até 5 minutos, demonstrando o funcionamento do entregável.]**

## Estrutura do repositório

```
├── README.md
├── requirements.txt
├── data/
│   └── crop_yield.csv
└── notebooks/
    └── pbl_fase4.ipynb   → renomear para NomeCompleto_rmXXXXX_pbl_fase4.ipynb
```

Mantenha o repositório **público** para acesso da equipe FIAP. Não realize commits após a data da entrega.
