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

## Entrega 2 - AWS (em andamento)

Comparacao de custos AWS solicitada no enunciado:

- Regioes: Sao Paulo (BR) x Virginia do Norte (EUA)
- Modo: On-Demand (100%)
- Configuracao: 2 CPU, 1 GiB RAM, 5 Gbps rede, 50 GB armazenamento

Status atual:

- 🔴 `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` - preencher tabela com valores calculados
- 🔴 `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` - justificar escolha final considerando restricao legal de dados
- 🔴 `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` - inserir imagens/graficos da calculadora AWS
- 🔴 `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` - inserir link do video da Entrega 2 (YouTube nao listado)

Modelo de preenchimento rapido:

| Item                              | Sao Paulo (BR)                                                   | Virginia do Norte (EUA)                                          | Status       |
| --------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- | ------------ |
| Custo mensal estimado             | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | 🔴 Em aberto |
| Solucao mais barata               | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | 🔴 Em aberto |
| Escolha final por restricao legal | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | `<span style="color: #d93025;"><strong>`PENDENTE `</strong>` | 🔴 Em aberto |

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
- 🔴 [ ] Preencher comparacao completa de custos AWS (Entrega 2)
- 🔴 [ ] Inserir justificativa tecnica da escolha final (latencia + restricao legal)
- 🔴 [ ] Inserir imagens/graficos da calculadora AWS no README
- 🔴 [ ] Inserir link do video da Entrega 2 no README
- 🔴 [ ] Revisar padrao final de nome do notebook conforme orientacao oficial do professor
- 🔴 [ ] Conferir se nao houve commit apos o prazo oficial de entrega

## Licenca

MODELO GIT FIAP por Fiap esta licenciado sob Attribution 4.0 International:

- http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1
