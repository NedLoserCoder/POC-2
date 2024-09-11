# POC-2-Array
## Sistemas de Informação, 02J L12
### Andreas Caycedo Martinez, 10435302
### Caio Takehiro Magnoli Igari, 10437809

Neste arquivo aplicamos alguns conceitos de array, que poderão ser vistos no console da página web. Começamos vendo o código HTML:

- Código HTML
  
  ![image](https://github.com/user-attachments/assets/5af09e5d-5678-40d6-85a9-03c3d29dd288)

  Aqui vemos uma estrutura corriqueira para um código HTML, porém com uma estilização específica nas tags body e h1, com o intuito de dar um visual chamativo para o que será posto em tela. Na tag script, vemos o link para o código Javascript, que é onde a mágica acontece

- Código Javascript

-- Criando array

  ![image](https://github.com/user-attachments/assets/14b790ae-3359-4639-8287-55a0a334007d)

  Esse primeiro trecho mostra o array "registro" sendo criado, com alunos como objeto e características como idade, mensalidade, bolsista, etc. O comando "console.log", por sua vez, faz com que esse registro apareça no console da página HTML

-- Spread

  ![image](https://github.com/user-attachments/assets/aa3467c1-bf8f-4144-976f-6dd4ddb22e0c)

  Usamos o operador spread para, no caso, criar uma cópia do array "registro" e colá-la no console de uma vez. Essa cópia poderá ser modificada sem modificar o original. Então, criamos o array "registro2", usando o spread operator para juntá-lo ao array original, formando o array "console". Por último, adicionamos a string "ALUNOS DO MACKENZIE" ao array.

-- Map

  ![image](https://github.com/user-attachments/assets/94c9a108-ce66-45cb-9ec6-f58a5a206374)

  Esse novo array usa a função map, que analisa o array "registro" para verificar certos elementos, e com base neles, criar um novo array. No caso, ele verifica se o aluno é ou não bolsista.

-- Reduce

  ![image](https://github.com/user-attachments/assets/533d7ef3-56b9-4753-9fd6-79792a1a3e85)

  A função reduce, no caso, soma o valor de todas as mensalidades dos alunos, e exibe o resultado no console.

-- Filter

  ![image](https://github.com/user-attachments/assets/e46c2e9e-f1b2-4460-896e-ab71e0df6393)

  A opção filter, como o próprio nome sugere, filtra os alunos com base em certas características, como no exemplo, em que filtra e exibe alunos com 20 anos ou mais.

-- Sort

  ![image](https://github.com/user-attachments/assets/7b310162-e30b-4fc9-a96c-4c824651a14a)

  A função sort irá analisar as quantidades de certas propriedades dos objetos. No caso, vai ordenar os alunos de acordo com as quantidades de semestres (em ordem crescente) e depois, no último array, irá ordenar em ordem alfabética pelo nome dos cursos.

- Resultados

  Vejamos como fica em tela:

  ![image](https://github.com/user-attachments/assets/9d307102-eb49-42ed-a56e-4068e04fb9e8)

  Essa é a tela principal no navegador. Vemos, em cores chamativas, a ordem "Olhe no console". O que fazemos para inspecionar o console é clicar com o botão direito e selecionar "Inspecionar elemento", ou então Ctrl + Shift + C.

  ![image](https://github.com/user-attachments/assets/4dd360bf-cd35-4e06-959c-68f7c476a45f)

  Aqui vemos o Array original com sua cópia, mostrando os objetos "alunos" e suas respectivas propriedades.

  ![image](https://github.com/user-attachments/assets/166d116a-be3a-4cde-b3c3-e4b771885b09)

  No primeiro array da imagem, vemos dois novos alunos adicionados à lista. No segundo array, vemos a linha ALUNOS DO MACKENZIE no topo.

  ![image](https://github.com/user-attachments/assets/4546552d-e3f7-43ad-b42b-1f85b37e25e3)

  Primeiro array: Mostra qual aluno é bolsista e qual não é. Segundo: simplesmente mostra a soma de todas as mensalidades. No caso, 11800. Terceiro: Mostra os alunos com mais de 20 anos de idade

  ![image](https://github.com/user-attachments/assets/7d10310d-2e1d-4461-8fe4-34a7711bc842)

  Por fim, esses dois últimos arrays organizam a lista conforme a quantidade de semestres (em ordem crescente) e então em ordem alfabética pelo nome dos cursos.

E foi basicamente isso que desenvolvemos usando métodos de array







