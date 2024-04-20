---
Start: 2024-04-08 22:23
DeadLine: 2024-05-12
Status:
  - Active
Priority: 
tags: 
Arquive: false
End: 
Author: João E. Moreira
---

# 📔 Description


# 📝 Next Steps
- [x] read and define a priority list of projects ✅ 2024-04-08
- [x] mandar mail ao prof 📅 2024-04-09 ✅ 2024-04-11

# 📋 Notes
- TP8 - Picar objetos: 5
- TP11 - Chaos: 4
- TP2 - Fractais com a rede vascular: 4
- TP5 - fogo florestal: 4
- TP12 - sistemas ecologicos
- TP7 - sistemas de parasitas:4
- TP10 - parece simples, só matemática: 3
- TP3 - trafic jam: 3
- TP4 - comunismo: 3
- TP6 - covid (propagaçao de doenças): 2
- TP1 - influencia da rede social na opiniao politica: 1
- TP9 - estou farto de genes: 0 (nao li)
## Auto propostos
- Simulating Fluids
- tree body problem
- 3x + 1 conjecture ([## Collatz conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture))
### email
Boa noite,

Eu sou João Moreira, número de aluno 2020230563, e envio este email com o meu colega de grupo Emanuel Roque, número de aluno 2020227336.

A ordem de preferência para os projetos é a seguinte:
- TP8, Picking Objects
- TP11, General Chaos Game
- TP5, Forest Fire
- TP12, Ecological System
- TP2, Fractal Analysis of Blood Vessel Networks
- TP7, Host-Parasite System

Motivados pela valorização dos projetos autopropostos, gostaríamos de propor 3 temas de projeto:
- Tree Body Problem
- Water Fluids
- 3x + 1 Conjecture (Collatz Conjecture)

Pedimos desculpas por não termos fornecido quais queres descrições ou objetivos para estes temas, pois ainda não refletimos muito sobre eles. No entanto, ficaríamos agradecidos se fosse possível discuti-los com os professores na quinta-feira, visto que gostaríamos de receber algumas opiniões por parte dos professores.
Caso contrário damos total preferência aos projetos listados pelos professores.

Saudações académicas,
João.
### Formulação do nosso problema
Queremos estudar a generalização de um ecossistema entre raposas e coelhos.

Na nossa simulação, termos um mundo 2D, estático e síncrono, de dimensões (N, N), com f raposas e r coelhos como população inicial.

Através de regras simples, como por exemplo:
- O alcance das percepções dos agentes
- A destreza ao ambiente, por exemplo, a velocidade com que se movem
- As condições da população inicial
- Taxas de cruzamento entre indivíduos
- ...
influenciam a população final.

## Outras regras relevantes
Os coelhos quando se sentem ameaçados vão para a toca.
## Framework para simulação
meza predator prey

# Run Project
```bash
python3 -m venv env
. ./env/bin/activate
cd mesa-examples/examples/wolf_sheep
pip install -r requirements.txt
mesa runserver
```
