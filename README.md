# Projeto Planejamento de viagem

<p>Projeto entregue durante o curso de desenvolvimento Web ministrado pela <a href="https://www.betrybe.com" targe="_blank" rel="nofollow">Trybe</a>.</p>

<p>Obtive a aprovação no projeto completando 100% dos requisitos obrigatórios e opcionais. Efetivando, assim, a conclusão do Bloco 6 (Datas) referente a Aceleração em Java.</p>

## Descrição
**Projeto tem como objetivo que o usuário possa calcular os fusos horários de suas viagens entre os países.**
  
  - O projeto lida com datas, horas e fusos horários utilizando Java.
  
:pushpin: Inicialmente o sistema recebe a entradas da pessoa usuária, na seguinte ordem:
  1. qual é a cidade de origem da sua viagem;
  2. a cidade de destino;
  3. a data e a hora de partida do seu voo; e
  4. a distância entre as cidades em quilômetros.
  
:pushpin: Após a pessoa usuária inserir essas informações, o sistema apresentará um resumo da viagem, indicando data, hora e o nome da cidade de partida, e também data, hora e o nome da cidade de destino. E, para facilitar ainda mais a vida das pessoas viajantes, o sistema apresentará uma frase informando que o desembarque será tal hora na cidade destino, o que equivale a tal hora da cidade de origem.

## Rodando o projeto localmente
  1. Clone o repositório
   
     `git@github.com:Lucas-PCN/planejamento-de-viagem.git`
    
  2. Entre no diretório do repositório que você acabou de clonar:
  
     `cd planejamento-de-viagem`

  3. Instale as dependências:
    
     `mvn install`

## Demonstração
### Exemplo de entrada e saída:

```
---------------------------- Bem-vindo ao sistema de planejamento de viagem ----------------------------
	1) Planejar uma nova viagem
	2) Encerrar Sistema

Entre com a opção desejada: 1
Entre com o nome da cidade origem: Recife
Entre com o nome da cidade destino: Tokyo
Entre com a data e o horário da partida (formato: dd/mm/aaaa hh:mm:ss): 22/01/2022 18:30:00
Entre com a distância em km entre a cidade de origem e a de destino: 16.885
```
 - Aqui estamos considerando que a cidade de origem é Recife, que a cidade de destindo é Tokyo, que o embarque do nosso voo será em 22/01/2022 às 18:30:00, e que a distância entre Recife e Tokyo é 16.885 km. 
 
 **Com essas informações, a saída no nosso console seria:**

```
---------------------------- Resumo da Viagem ----------------------------
Partida: 22/01/2022 18:30:00
Origem: Recife

Chegada: 24/01/2022 06:30:00
Destino: Tokyo

Atenção: o desembarque em Tokyo será: 24/01/2022 06:30:00 no horário de Tokyo e 23/01/2022 18:30:00 no horário de Recife
--------------------------------------------------------------------------
```
---

Projeto desenvolvido por Lucas Castanheira, para fins didáticos. 2023
