# Projeto de IA: Classificação de Doenças Foliares em Plantas de Milho

## Proposta
Este projeto utiliza um conjunto de dados para a **classificação de doenças foliares em plantas de milho**, abrangendo quatro classes: Ferrugem Comum, Mancha Cinzenta, Praga e Saudável. O objetivo é aplicar redes neurais convolucionais (CNNs) e técnicas avançadas de aprendizado de máquina para detectar e classificar as doenças foliares.

---

## Descrição do Conjunto de Dados

| Classe                      | Imagens |
|-----------------------------|---------|
| **0: Ferrugem Comum**        | 1.306   |
| **1: Mancha Cinzenta na Folha** | 574     |
| **2: Praga**                 | 1.146   |
| **3: Saudável**              | 1.162   |

Este conjunto de dados foi criado utilizando os conjuntos **PlantVillage** e **PlantDoc**, após a remoção de imagens consideradas irrelevantes. 

- Fonte dos Dados: [Kaggle - Corn or Maize Leaf Disease Dataset](https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset)

Se utilizar este conjunto de dados em sua pesquisa acadêmica, credite os autores originais:
- **Singh D, et al.**, PlantDoc: A Dataset for Visual Plant Disease Detection, ACM IKDD CoDS and COMAD, 2020.
- **Arun Pandian J, et al.**, "Data for: Identification of Leaf Diseases in Plants using a 9-layer Deep CNN", Mendeley Data, 2019.

---

## Imagens das Doenças Foliares

- **Figura 1**: Ferrugem Comum
- **Figura 2**: Mancha Cinzenta
- **Figura 3**: Praga
- **Figura 4**: Folha Saudável

---

## Etapas do Projeto

### **Etapa 1 - Utilizar um Exemplo com CNN**
- Aplicação de um exemplo pronto do Keras para classificação.
- Redução da resolução das imagens para otimizar o treinamento.
- Implementação de uma CNN profunda do zero.
- Avaliação de resultados e tempo de treinamento.

### **Etapa 2 - Utilizar uma Rede CNN Pré-treinada**
- Escolha de um modelo pré-treinado (e.g., VGG16, ResNet).
- Implementação de transferência de aprendizado.
- Avaliação de resultados e tempo de aprendizado.

### **Etapa 3 - Utilizar uma Rede ViT (Vision Transformer)**
- Escolha de um modelo ViT para a tarefa.
- Ajuste fino do aprendizado.
- Avaliação de resultados e tempo de aprendizado.

### **Etapa 4 - Utilizar Plataforma Embarcada**
- Utilização da plataforma **Edge Impulse** ([link](https://studio.edgeimpulse.com/)) para testar o modelo em um dispositivo embarcado.
- Dispositivo: **Celular**.
- Geração de um notebook Python para teste do modelo.

---

## Tecnologias Utilizadas
- **Python** para modelagem e treinamento.
- **Keras**, **TensorFlow**, **PyTorch** para implementação das redes neurais.
- **Edge Impulse** para teste em plataforma embarcada.
- **Jupyter Notebooks** para desenvolvimento.

---

## Como Executar o Projeto
1. Clone o repositório.
2. Instale as dependências via `pip install -r requirements.txt`.
3. Baixe o conjunto de dados e coloque-o no diretório do projeto.
4. Execute os notebooks fornecidos para cada etapa descrita acima.

---

## Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

---

## Contribuições
Contribuições são bem-vindas! Se você deseja melhorar ou expandir o projeto, sinta-se à vontade para fazer um fork e enviar suas sugestões.

