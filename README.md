# material_de_apoio_DinoAI
## Olá aluno! Este repositório contém o material de apoio para as aulas da Semana AI!

### Vamos entende-lo melhor?

<br>

### Vamos começar pela função randomRange(min, max)! 

#### Esta função gera um número aleatório entre os valores min e max, pois no JavaScript, não temos nenhum material que faça isso automaticamente! Você pode utilizar está função para diversos outros projetos!


```  
function randomRange(min, max) {
  return Math.random() * (max - min) + min;
} 
``` 

<br>

### já a função lerp(a, b, t) (Interpolação Linear) calcula um valor intermediário entre a e b com base no fator t. A interpolação linear é útil para adivinhar valores entre dois números conhecidos.

``` 
function lerp(a, b, t) {
  return a + (b - a) * t;
}
``` 

<br>

### Na classe Neuron (Neurônio) utilizamos diversos construtores e funções para recriar um neurônio em computador!

#### Como o método constructor(inputs) que inicializa o neurônio com um viés (bias) aleatório no intervalo [-1, 1] e uma lista de pesos aleatórios também no intervalo [-1, 1].
#### O método g(signalList) que calcula a saída do neurônio (ativação) com base nos sinais de entrada e uma função de ativação (tangente hiperbólica).
#### E o método mutate(rate) que realiza mutação nos pesos e no viés do neurônio.

### Já a nossa classe RNA (Rede Neural Artificial) utiliza esses neurônios, mas cria uma rede deles para que trabalhem em conjunto!

<br>

## Está é uma forma simples porém super eficiente de utilizarmos inteligência artificial em tarefas cotidianas, podemos aplicar mais dela em diversos outros ambientes!
## Podemos utiliza-la das seguintes formas:

- Automações
- Criação de conteúdo
- IoT (Internet das Coisas)
- Matemática
- Medicina
- Predição e muito mais!

## Esperamos que este material seja de grande valia para sua jornada!