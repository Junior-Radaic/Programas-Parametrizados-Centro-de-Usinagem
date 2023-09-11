# **Usinagem de Chanfro em Ponta de Eixo**

Programa criado para usinar chanfros em furos com ferramentas paralelas

Fazer os ajustes nos parâmetros R1 - R5 conforme descrito no programa.

No parâmetro R3 alterar apenas o ângulo de inclinação desejado no ().


# **Exemplo**
Precisamos fazer um chanfro de 5mmX45 graus em um furo com 50mm de diâmetro.
Os parâmetros ficariam assim:

R1 = 27.5 ; RAIO MAIOR

R5 = 0 ; INICIO EM Z

R2 = 0.1 ; INCREMENTO EM Z

R3 = TAN(45) * R2 ; INCREMENTO EM X NO RAIO

R4 = -5 ; Z FINAL


# **Observação**
No parâmetro R2, quanto maior o incremento, pior acabamento.

Programa já executado com sucesso, porém, recomendo que teste o programa em segurança antes de usinar.