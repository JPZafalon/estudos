Terça, 26 de maio de 2026
	
  Hoje decidi começar a leitura do livro "Entendendo algoritmos (Aditya Y. Bhargava)".
  
  Iniciando no capítulo 1, passei pelo conteúdo de pesquisa binária e aprendi sobre sua eficácia para diminuir etapas, o que acabou me levando a rever logaritmos:
"Para uma lista de n números, a pesquisa binária precisa de log2(n) etapas para retornar o valor correto, enquanto a pesquisa simples precisa de n etapas."

  Na página seguinte somos apresentados em como colocar pesquisa binária em python, onde tenho pouquíssimo conhecimento. Utilizando Arrays e Buckets como exemplo, o livro utiliza explicações básicas e pequenas, mas o suficiente para despertar minha curiosidade e vontade, fazendo surgir uma ideia, uma vontade: Desenvolver uma "fórmula" que me ajudasse em um futuro próximo.

  Desse jeito comecei a pensar, trazendo meu primeiro "protótipo":
```txt
"B#0 = + 1 $\Leftrightarrow$ Posição do Bucket"
```
  Surgindo minha primeira fórmula informal - e errada.
  
  Então comecei a pesquisar, e aprender, um jeito de organizar e fazer algo melhorado, o que me levou a: 
```txt
[n = 0, 1, 2, 3...]
[B# -> bucket]
V = n + 1
B#n -> V

Definição: B#n <=> valor de bucket -> V = posição no array.
```
  Quando consegui chegar a um resultado agradável, mesmo que ainda "cru", utilizei ele como meio para uma outra dúvida que me surgiu e me fez pensar: "E se eu tivesse um armário com múltiplas prateleiras, apenas com buckets armazenando informações?", o que me levou ao segundo momento em que, mesmo não sendo um cálculo em que eu mesmo criei, me senti muito feliz por conseguir alcançar esses resultados sem procurar algo pronto - apenas me desenvolvendo aos poucos, em algumas horas.

  Então utilizando minha fórmula de bucket (B#), consegui chegar em um sistema de busca universal para localizar a posição de um item dentro de um "armário com várias prateleiras":
```txt
[G = Posição global]
[p = Prateleiras]
[n = Buckets]
[S = tamanho das prateleiras]

G = (p*S) + n + 1
```
  O que me trouxe a vontade de fazer exercícios, aprender e visualizar melhor o conteúdo que tinha acabado de descobrir, pedindo então que IAs gerassem exercícios para que eu pudesse praticar e me aperfeiçoar. Isso também fez com que eu pudesse visualizar a fórmula reversa da equação, para descobrir em que "p" e "n" um "G" apontava.

  Quem sabe eu não traga alguns exemplos... 
