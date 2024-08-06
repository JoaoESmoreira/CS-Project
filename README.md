---
Start: 2024-04-08 22:23
DeadLine: 2024-05-19
Status:
  - Active
Priority: 
tags: 
Arquive: false
End: 
Author: João E. Moreira
Author2: Emanuel Roque
---

# 📔 Description
Com este trabalho, procuramos explorar a dualidade de resultados possíveis, nos quais as populações podem coexistir ou ser levadas à extinção mútua, dependendo das interações e condições ambientais. 

Através da simulação proposta, temos por objetivo estabelecer um paralelismo simplificado com o que ocorre na natureza, destacando como pequenas alterações podem desencadear a quebra de ecossistemas e levar à extinção de espécies. Reconhecemos que a natureza possui um equilíbrio frágil, cuja compreensão é crucial para a conservação e preservação da biodiversidade.

Através de regras simples, como por exemplo:
- As condições da população inicial
- Taxas de cruzamento entre indivíduos
- Quantidade de energia ganha pela comida
- ...
influenciam a população final.
## Framework para simulação
meza predator prey
# 💻 Run Project
```bash
python3 -m venv env
. ./env/bin/activate
pip install -r requirements.txt

cd src
python3 run.py    # visualization mode
cd our_model
python3 model.py    # experiments
```

