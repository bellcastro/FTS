# Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser

Silva, Vinícius Barcelos; Spoto, Edmundo Sérgio; Araujo, Cláudio Antonio; Vicenzi, Auri M R. "Incremental Strategy for Applying Mutation Operators Emphasizing 
Faults Diicult to be Detected by Automated Static Analyser" in **Proceedings of SBES’17**, Fortaleza, CE, p. 24-32, 2017. DOI: 10.1145/3131151.3131169. 

## 1. Fichamento de Conteúdo

Teste de mutação é uma técnica muito eficaz, entretanto gera um alto custo computacional devido ao número de mutantes gerados. O objetivo do artigo é dar continuidade 
ao estudo de Araujo et al. e definir uma estratégia incremental de aplicação dos operadores de mutação para C, com base nas informações de análise estática. A estratégia 
STAT foi definida e avaliada em relação aos conjuntos essenciais E5 e E27 de acordo com valores de escore mutação, custo em termos do número de mutantes gerados e equivalentes. 
Os testes estatísticos realizados demonstraram que segundo os aspectos investigados, não há diferença entre a STAT e os conjuntos essenciais E5 e E27. 
Indicando assim, que esses subconjuntos de operadores de mutação são bons candidatos para redução de custo e manutenção da eficácia do critério.

## 2. Fichamento Bibliográfico 


* *Teste de Mutação* Técnica que tem como objetivo medir o quão válido é um conjunto de casos de teste. (Página 24)

* *Análise Estática Automatizada* É um método de depuração que examina automaticamente o código-fonte antes de um programa ser executado. (Página 25) 

* *Escore de Mutação* Relaciona o número de mutantes gerados com o número de mutantes mortos. (Página 32)

  

## 3. Fichamento de Citações 


* *“Um dos problemas do Teste de Mutação é o alto custo computacional devido ao grande número de mutantes gerados, que demandam tempo para a execução, e posterior análise de mutantes vivos para identificação de mutantes equivalentes. ”*

* *"Por outro lado, operadores de mutação com menores taxas CDLR(ok ) modelam os defeitos mais difíceis de serem detectados pelo analisador estático"*

* *"A Ferramenta Splint foi escolhida como analisador estático e a* *Ferramenta Proteum/IM como a ferramenta de mutação. No caso da Splint foram utilizadas todas as possíveis regras de análise estática.*
  *No caso da Proteum/IM todos os 78 operadores de unidade* *implementados."*

* *"Nesse sentido, considera-se uma vantagem o uso da STAT pois esta utiliza, inicialmente, os operadores que modelam defeitos mais difíceis de serem detectados por meio de análise estática."*

  
