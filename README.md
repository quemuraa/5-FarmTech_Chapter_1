- Guilherme Pinheiro Carlsson Cury - RM564011

# 🌾 FarmTech Solutions — Fase 5: Machine Learning na Cabeça

Projeto desenvolvido para a **Fase 5** do curso de **Tecnólogo em Inteligência Artificial** — FIAP 2026.

---

## Nome do grupo : AI4Success

## 👥 Integrantes do Grupo

- Murilo Ferreira Borges - RM567738
- Guilherme Pinheiro Carlsson Cury - RM564011
- Guilherme da Nobrega Gontijo - RM562211
- Durval de O. Dorta Jr. - RM567007
- Estevao Ferreira Santos - RM567522

## 👩‍🏫 Professores:

#### Tutor(a)

* Ana Cristina dos Santos

#### Coordenador(a)

* André Godoi Chiovato

## 📜 Descrição

Analisar dados agricolas para prever rendimento de safras com Machine Learning,
incluindo:

- Analise exploratoria de dados (EDA)
- Clusterizacao para tendencias e outliers
- Regressao supervisionada com 5 modelos preditivos

## 📁 Estrutura de pastas

```text
Fase_5_Colegas_Tarefa_1/
|- README.md
|- data/
|  |- crop_yield.csv
|- notebooks/
   |- EstevaoFerreiraSantos_rm567522_pbl_fase5.ipynb
```

## Entrega 1 - Machine Learning

Notebook principal:

- `notebooks/EstevaoFerreiraSantos_rm567522_pbl_fase5.ipynb`

Link direto no repositorio:

- [`./notebooks/EstevaoFerreiraSantos_rm567522_pbl_fase5.ipynb`](./notebooks/EstevaoFerreiraSantos_rm567522_pbl_fase5.ipynb)

Conteudo atual ja implementado no notebook:

- EDA do dataset `crop_yield.csv`
- Clusterizacao (KMeans) para perfis/tendencias
- Deteccao de outliers (DBSCAN)
- 5 modelos de regressao com comparacao por metricas
- Conclusoes, pontos fortes e limitacoes em markdown

Video da Entrega 1:

- (https://youtu.be/Bt7wXpwRs7Q)

## Entrega 2 - AWS

Comparacao de custos AWS solicitada no enunciado:

- Regioes: Sao Paulo (BR) x Virginia do Norte (EUA)
- Modo: On-Demand (100%)
- Configuracao: 2 CPU, 1 GiB RAM, 5 Gbps rede, 50 GB armazenamento

Status atual:

- 🔴 <span style="color: #d93025;"><strong>Feito </strong> - preencher tabela com valores calculados
- 🔴 <span style="color: #d93025;"><strong>Feito </strong> - justificar escolha final considerando restricao legal de dados
- 🔴 <span style="color: #d93025;"><strong>Feito </strong> - inserir imagens/graficos da calculadora AWS
- 🔴 <span style="color: #d93025;"><strong>Feito </strong> - inserir link do video da Entrega 2 (YouTube nao listado)

Modelo de preenchimento rapido:

| Item                              | Sao Paulo (BR)                                                   | Virginia do Norte (EUA)                                          |
| --------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | 
| Custo mensal estimado             | <span style="color: #d93025;"><strong>19.28 USD p/month </strong> | <span style="color: #d93025;"><strong>11.13 USD p/month </strong> | 🔴 Em aberto |
| Solucao mais barata               | <span style="color: #d93025;"><strong>NÃO </strong> | <span style="color: #d93025;"><strong>SIM </strong> | 🔴 Em aberto |
| Escolha final por restricao legal | <span style="color: #d93025;"><strong>SIM </strong> | <span style="color: #d93025;"><strong>NÃO </strong> | 🔴 Em aberto |

## Justificativa

A aplicação utiliza dados provenientes de sensores ambientais, que podem estar relacionados a informações como localização, propriedade e produção agrícola. Dessa forma, o tratamento desses dados exige atenção quanto à conformidade legal.

Ao optar pela região de São Paulo (Brasil), garantimos maior aderência à Lei Geral de Proteção de Dados (LGPD), evitando a necessidade de transferência internacional de dados e reduzindo a complexidade de requisitos legais associados ao armazenamento em outros países.

Além disso, a escolha da região nacional proporciona menor latência na comunicação entre os sensores e a API. Em cenários internacionais, como na região da Virgínia (EUA), a latência pode variar aproximadamente entre 100 ms e 180 ms, enquanto em território nacional tende a ser significativamente menor, melhorando o tempo de resposta da aplicação.

Outro ponto relevante é a disponibilidade e estabilidade da conexão. Ao utilizar uma infraestrutura localizada no Brasil, reduz-se a dependência de rotas internacionais, que podem estar mais sujeitas a instabilidades, aumentando assim a confiabilidade do sistema.Portanto, mesmo com um custo superior, a região de São Paulo se mostra a escolha mais adequada, priorizando conformidade legal, desempenho e confiabilidade da solução.

## Imagens das Instâncias

### São Paulo
<img width="1600" height="437" alt="image" src="https://github.com/user-attachments/assets/c0645c58-73ef-4995-9bc9-59de9b24c755" />
<img width="1600" height="334" alt="image" src="https://github.com/user-attachments/assets/521369d9-b7ce-428e-936a-68d93bcdf625" />
<img width="381" height="99" alt="image" src="https://github.com/user-attachments/assets/03895e9a-6e0a-45f1-835c-1688cf888bb8" />
<img width="1600" height="453" alt="image" src="https://github.com/user-attachments/assets/7bbef1bc-cb1d-4b67-a1e9-8453df012ad9" />

### Norte da Virgínia
<img width="1600" height="519" alt="image" src="https://github.com/user-attachments/assets/a3e4d666-ac95-4e95-a774-9a431f84f48e" />
<img width="1600" height="469" alt="image" src="https://github.com/user-attachments/assets/53c3d559-933b-47b6-8ab5-8a21923d32dc" />
<img width="1600" height="674" alt="image" src="https://github.com/user-attachments/assets/fbb0c6a2-5f21-4670-b088-a6f16c055eee" />
<img width="1084" height="498" alt="image" src="https://github.com/user-attachments/assets/b8aff5f4-bf35-48a8-b9a7-59f82bbaef85" />

Video da Entrega 2:

- (https://www.youtube.com/watch?v=8aw4_MhTSA0)

## 🔧 Como executar o código

Pre-requisitos:

- Python 3.10+
- Jupyter Notebook (ou VS Code + extensao Jupyter)

Passos:

1. Criar e ativar ambiente virtual

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Instalar dependencias

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Abrir notebook

```bash
jupyter notebook notebooks/EstevaoFerreiraSantos_rm567522_pbl_fase5.ipynb
```

## `<span style="color: #d93025;">`ATENCAO - Pendencias obrigatorias antes da entrega final

- 🔴 [ ] Inserir link do video da Entrega 1 no README
- 🔴 [X] Preencher comparacao completa de custos AWS (Entrega 2)
- 🔴 [X] Inserir justificativa tecnica da escolha final (latencia + restricao legal)
- 🔴 [X] Inserir imagens/graficos da calculadora AWS no README
- 🔴 [X] Inserir link do video da Entrega 2 no README
- 🔴 [ ] Revisar padrao final de nome do notebook conforme orientacao oficial do professor
- 🔴 [ ] Conferir se nao houve commit apos o prazo oficial de entrega

## Licenca

MODELO GIT FIAP por Fiap esta licenciado sob Attribution 4.0 International:

- http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1
