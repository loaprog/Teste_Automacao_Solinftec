## Desafio Automação Solinftec
Nesse desafio o objetivo era automatizar o processo de identificar semelhanças ou diferenças entre duas ou mais imagens. Essa tarefa
é particularmente útil em diversas aplicações, como reconhecimento de padrões, verificação de autenticidade de documentos, detecção 
de plágio, entre outros.

## Caminho tomado para atingir o objetivo
Utilizei três métodos, em cada um aplicando técnicas de visão computacional:

1. No primeiro método, utilizei os índices do Sensoriamento Remoto para visualizar a biomassa da vegetação nas imagens RGB, utilizei o Índice de Folha Verde (GLI). Em seguida, calculei a quantidade de pixels que representavam o solo exposto e a biomassa da planta. Caso outra imagem apresentasse a mesma quantidade de pixels, seria declarada como semelhante; caso contrário, seria considerada diferente.

 - Rodando com imagens diferentes:
   
![image](https://github.com/loaprog/Teste_Automa-o_Solinftec/assets/75463070/0b7e44c1-61d6-4c21-9c20-e3ad4bcdc2c4)

- Rodando com uma das imagens iguais:
  
![image](https://github.com/loaprog/Teste_Automa-o_Solinftec/assets/75463070/291b43c4-5db1-49fa-95c3-faf0539a9d1e)

2. No segundo método, com o TensorFlow realizei a transformação das imagens em dados tensoriais, posteriormente convertendo-os em vetores para melhorar a eficiência computacional e de armazenamento. Procurei outras imagens que tivessem essa mesma correlação de dados para declará-las como semelhantes. Caso não houvesse semelhança com alguma imagem, ela seria considerada diferente.

- Rodando com imagens diferentes:
   
![image](https://github.com/loaprog/Teste_Automacao_Solinftec/assets/75463070/e3392535-ffe7-41c4-8455-084648c50388)

- Rodando com uma das imagens iguais:
  
![image](https://github.com/loaprog/Teste_Automacao_Solinftec/assets/75463070/0777d6c7-ee55-4a28-96ce-45af9b467c62)

3. No terceiro método, utilizei o OpenCV para calcular a diferença entre os pixels em duas imagens e estabeleci que se a diferença entre os pixels de duas imagens fosse menor que 30, elas seriam consideradas semelhantes.
   
- Rodando com imagens diferentes:
   
![image](https://github.com/loaprog/Teste_Automa-o_Solinftec/assets/75463070/a1d1a5f7-e52b-457e-ac5c-739746da6c77)

- Rodando com uma das imagens iguais:
  
![image](https://github.com/loaprog/Teste_Automa-o_Solinftec/assets/75463070/7ab41d6e-ddc1-42c0-843e-dead48a34117)

Tenho uma dedicação inabalável por desafios, agricultura e tecnologias. Seria uma honra fazer parte de uma equipe que compartilha desse mesmo propósito!
