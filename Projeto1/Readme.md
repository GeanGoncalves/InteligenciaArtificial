
# Projeto de Inteligência Artificial com IIoT para Planta de Processo e Separador Trifásico

## Introdução
A **Internet das Coisas Industrial (IIoT)** envolve a interconexão de sensores, instrumentos e dispositivos com sistemas de controle industrial. Esta atividade utiliza um sistema IIoT em uma planta de processo e separador trifásico de água, gás e petróleo, com o objetivo de aplicar técnicas de análise de dados e aprendizado de máquina para otimizar o desempenho da planta.

### Objetivo
O objetivo do projeto é analisar a base de dados gerada por sensores distribuídos na planta, detectar anomalias no processo e aplicar modelos de aprendizado de máquina para melhorar a identificação de falhas e otimizar o rendimento da planta.

---

## Base de Dados da Planta de Processo

A base de dados foi gerada sinteticamente e consiste em leituras de temperatura de 50 dispositivos, coletadas a cada segundo durante 48 horas. Ao longo desse período, 50% das leituras representam perdas de rendimento, identificadas como **classe 1** (falha).

- **Total de Leituras**: 8.640.000
- **Faixa de Temperatura**: 0 a 100°C
- **Dispositivos**: 50 sensores
- **Intervalo de Tempo**: 172.800 amostras (48 horas)
- **Atributo Alvo**: 0 (normal) ou 1 (falha)

[Baixar Base de Dados](https://drive.google.com/file/d/17XOsLTMn3B2F9odJxGysu0J8rW9tJj6S/view?usp=sharing)

---

## Etapas da Atividade

### **Etapa 1 - Análise da Base de Dados**
- Análise das características dos atributos
- Tratamento de dados faltantes
- Estudo de correlação entre variáveis
- Geração de histogramas
- Detecção de anomalias

### **Etapa 2 - Capacidade de Aprendizado sobre a Base**
- Separação da base de dados em treinamento e teste
- Aplicação de 10 metodologias de aprendizado de máquina
- Avaliação dos modelos com métricas recomendadas
- Ordenação dos melhores modelos por desempenho

### **Etapa 3 - Pipeline, Pré-processamento e Redução de Dimensionalidade**
- Criação de um pipeline de aprendizado
- Aplicação de técnicas de pré-processamento
- Redução da dimensionalidade
- Validação cruzada para avaliação aprimorada

### **Etapa 4 - Seleção de Metodologias e Hiperparâmetros**
- Aplicação das metodologias **XGBoost** e **LightGBM**
- Otimização dos hiperparâmetros com validação cruzada
- Identificação dos 2 melhores modelos

---

## Tecnologias Utilizadas
- **Python** para análise de dados e aprendizado de máquina
- **Bibliotecas**: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM
- **Ambiente**: Jupyter Notebook

## Como Executar o Projeto
1. Clone o repositório.
2. Instale as dependências via `pip install -r requirements.txt`.
3. Baixe a base de dados e coloque-a no diretório correspondente.
4. Siga as etapas descritas nos notebooks para cada fase do projeto.

---

## Contribuições
Este projeto foi desenvolvido para demonstrar a aplicação de técnicas de IIoT e aprendizado de máquina na otimização de processos industriais. Sinta-se à vontade para contribuir ou sugerir melhorias.

---

## Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
