# Detec-o-de-Placas-de-Tr-nsito-com-Intelig-ncia-Artificial
O projeto tem como objetivo desenvolver um modelo de visão computacional capaz de detectar e classificar placas de trânsito, como "Pedestrian Crossing", "Traffic Light" e "Speed Limit". A escolha desse tema se deu pela relevância na segurança viária e pelo potencial de aplicação em sistemas de assistência à direção. 

Detecção de Placas de Trânsito com Inteligência Artificial

Identificação

Nome e e-mail do integrante do projeto:Pedro Duques Satler – E-mail: [pedrinhosatler@gmail.com]

Descrição do Projeto

O projeto tem como objetivo desenvolver um modelo de visão computacional capaz de detectar e classificar placas de trânsito, como "Pedestrian Crossing", "Traffic Light" e "Speed Limit". A escolha desse tema se deu pela relevância na segurança viária e pelo potencial de aplicação em sistemas de assistência à direção. O conjunto de dados foi selecionado a partir de imagens rotuladas dessas placas, permitindo a criação de um modelo eficiente para detecção em tempo real.

Conjunto de Dados

O conjunto de dados utilizado contém imagens rotuladas de diferentes placas de trânsito, com variações de iluminação, ângulos e ambientes. As principais características incluem:

Número de amostras utilizadas: 80 imagens

Classes: Pedestrian Crossing, Traffic Light, Speed Limit

Formato dos rótulos: Bounding boxes delimitando as placas nas imagens

Fonte dos dados: Road Sign Detection

Aprendizado de Máquina – Visão Computacional

A técnica utilizada foi a Detecção de Objetos. O projeto no Edge Impulse utiliza um modelo de classificação supervisionada para a detecção de objetos, classificando diferentes classes como background, pedestrian crossing, speed limit e traffic light. A abordagem aplicada se baseia em Redes Neurais Convolucionais (CNNs), amplamente utilizadas em tarefas de visão computacional devido à sua eficiência em identificar e classificar objetos em imagens.

Resultados e Desempenho

Acurácia: 70.59%

Precisão: 0.78

Recall: 0.82

F1 Score: 0.80

Matriz de Confusão:

[[2421, 3, 0, 2], 
 [ 1, 6, 0, 0], 
 [ 0, 0, 9, 0], 
 [ 3, 0, 0, 3]]

Comentários sobre o desempenho

O modelo apresentou um desempenho satisfatório, com uma acurácia de 70.59%, precisão de 0.78 e recall de 0.82. Embora tenha conseguido detectar placas de trânsito de maneira eficiente na maioria dos casos, enfrentou dificuldades em condições de baixa iluminação e imagens com alto nível de ruído. Além disso, algumas falsas detecções indicam a necessidade de um refinamento nos dados de treinamento e ajustes nos hiperparâmetros do modelo para melhorar sua robustez.

Conclusão

O projeto demonstrou que a visão computacional pode ser uma ferramenta eficaz para a detecção de placas de trânsito, contribuindo para a segurança viária e possíveis aplicações em veículos autônomos e sistemas de assistência à condução. Apesar do desempenho satisfatório, identificamos desafios como a necessidade de aprimorar a qualidade dos dados e refinar os hiperparâmetros do modelo. Melhorias futuras podem incluir o uso de um conjunto de dados mais diversificado e técnicas avançadas de pré-processamento para aumentar a robustez da detecção em diferentes condições ambientais.

Experiência na Plataforma Edge Impulse

A experiência com a plataforma Edge Impulse foi enriquecedora, permitindo uma abordagem prática do aprendizado de máquina para visão computacional. Durante o desenvolvimento do projeto, enfrentei desafios como a coleta de dados adequados e o ajuste dos parâmetros do modelo. No entanto, a interface intuitiva da plataforma facilitou a implementação e o treinamento do modelo. Como aprendizado principal, destacamos a importância da qualidade dos dados para o sucesso do modelo e a necessidade de ajustes contínuos para obter melhores resultados.

Como Executar o Projeto

Acesse a plataforma Edge Impulse e importe o dataset utilizado.

Configure os parâmetros do modelo de detecção de objetos.

Realize o treinamento e avalie os resultados.

Teste a detecção utilizando novas imagens.

Contato

Pedro Duques Satler📧 E-mail: pedrinhosatler@gmail.com
