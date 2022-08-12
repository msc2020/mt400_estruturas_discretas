# Descrição

Códigos desenvolvidos como parte do material para as aulas, como professor voluntário, 
da disciplina Estruturas Discretas - MT/MS 400 (2o semestre de 2019) - IMECC/UNICAMP.

______

### Aula 1 (14-ago-2019):

1. Como instalar o Mathematica original (licença da Unicamp)

2. Sobre interface do Mathematica, kernel, Help, etc.

3. Dicas de programação: Comandos For[ ] , If[ ], RandomReal[ ], Shift +Enter

4. Sobre o pacote do prof. Michael: mdgp.nb

5. Exercícios (para tentar fazer com auxílio do Help do Mathematica):
   1) gerar e tentar resolver um sistema linear Ax = b;
   2) gerar e tentar resolver um sistema quadrático x'Qx = b.



### Aula 2 (21-ago-2019):

1. Revisão geral

2. Discussão dos exercícios: Aula 1 - exercício 1)

3. Dicas de programação: revisão; comando Module[ ]

4. Sobre o pacote mdgp.nb: item 1) Instance Creation and Plot Routines


### Aula 3 (28-ago-2019)

1. Revisão geral

2. Pacote mdgp.nb: alguns exemplos de como utilizar funções do pacote (mdgp_testes.nb)

3. Exercícios:
   1) Faça uma função (Module[ ]) no Mathematica que receba os coeficientes a, b e c da eq. quadrática ax^2+bx+c = 0 e retorne sua solução.
   2) Usando o Mathematica, tente gerar e resolver um sistema do tipo:
       
       ||x - a|| = r_1,
       
       ||x - b|| = r_2,
       
       ||x - c|| = r_3,
       
   (a, b, c pertencem ao R^2 e r_i ao R^1_+).
   3) Use o pacote mdgp.nb para gerar uma instância, resolver e plotar a solução para um DGP com 10 vértices.


### Aula 4 (04-set-2019)
1. Sites:
 - PDB: www.rcsb.org (exemplo de visuzaliação de um backbone)
 - revistapesquisa.fapesp.br -> ciência -> 'Como o câncer de mama resiste à quimioterapia' (exemplo da importância da dimensão da solução em uma aplicação atual)

2. Revisão geral

3. Pacote mdgp.nb: finalizado exemplos baseados no mdgp.nb testados no mdgp_testes.nb

4. Exercícios:
   1) Considere um grafo (V ={1, 2, 3}, E ={{1, 2}, {1, 3}, {2, 3}}) com arestas 
     de pesos d_{12} = d_{13} = d_{23} = 1. Seja a origem a posição do vértice v = 1. 
     Escreva as equações do sistema (*) abaixo para K \in {1, 2, 3}, e resolva estes 
     sistemas, algebricamente ou numericamente (p. ex., usando o Mathematica). Quantas 
     soluções existem para K = 1? Para K = 2? E para K = 3?

     (*) \forall {u,v} \in E: Sum_{k<=K}(x_{uk} - x_{vk})^2 = d_{uv}^2.

    2) No pacote mdgp.nb encontre as seções DGBuildUpSolver e DGBPSolver. Teste seus
       exemplos para diferentes dados de entrada.
       
### Aula 5 (11-set-2019)

1. Revisão geral

2. Revisão sobre o algoritmo BP (3 versões do algoritmo (equivalentes) presente nas referências, em anexo)

3. Sobre o algoritmo BP no mdgp.nb: testes baseados em funções do pacote, parte 1 (mdgp_testesBP.nb)


### Aula 6 (18-set-2019)

1. Revisão geral

2. Sobre o algoritmo BP no mdgp.nb: testes baseados em funções do pacote, parte2 (finalizado os exemplos de mdgp_testesBP[2].nb)

3. Exercício:
  (1) No Exemplo 8 se diminuirmos o valor de corte r_c = 4 para r_c = 3 (i.e., alterarmos P=DGRandomMDGP[n, 0.0, 4] 
para P=DGRandomMDGP[n, 0.0, 3]) é esperado que o número de soluções deva aumentar ou diminuir? E se aumentarmos o 
valor de corte para r_c = 6, o número de soluções aumenta ou diminui? Tente usar o Mathematica para verificar a resposta 
correta.


### Aula 7 (25-set-2019)

1. Revisão geral

2. Testes com o algoritmo BP baseado no pacote mdgp.nb (parte 3) e no artigo 'A Branch-and-Prune algorithm for the Molecular Distance
Geometry Problem',L. Liberti, C. Lavor, N. Maculan (2008) (em anexo mdgp_testes_artigoBP.nb)

3. Exercícios: ao longo do arquivo mdgp_testes_artigoBP.nb


### Aula 8 (02-out-2019)

1. Revisão geral

2. Testes com o algoritmo BP, continuação: mdgp_testes_artigoBP[2].nb (em anexo)


### Aula 9 (16-out-2019)

1. Revisão geral

2. Discussão da figura com os círculos e arcos associados ao caso intervalar (em anexo)



### Aula 10 (23-out-2019)

1. Revisão geral

2. Testes de elementos da álgebra geométrica com o pacote clifford.m (em anexo testes_alg_geom.nb)


### Aula 11 (02-nov-2019)

1. Revisão geral

2. Testes com o pacote clifford.m (em anexo testes_alg_geom[2].nb)
