# Furação profunda 

Este ciclo foi criado para furos onde se utilizam mais de uma broca.

Este arquivo é um sub-programa. Para utilizar, renomeie o nome do arquivo, de acordo com seus padrões. Abra o arquivo e copie os parâmetros #1 - #8 no programa principal e faça os ajustes nescessários.

Exemplo: Em um furo de 400mm de profundidade, precisamos utilizar duas brocas. Na primeira utlizamos uma broca curta para se fazer um guia para a broca mais longa, furando 100mm de profundidade. Na segunda broca, se utilizar-mos o G83, teríamos que usar o Z0 próximo aos 100mm já feito, dificultando a limpeza e saída de cavacos de dentro do furo. Com este ciclo, podemos ajustar o Z0 rente a face, para facilitar a limpeza do furo, e a máquina faz a aproximação rápida próximo aos 100mm.

<div align="center"> </div>

<img src="https://github.com/Junior-Radaic/Programas-Parametrizados-Centro-de-Usinagem/blob/main/Fanuc/Pica-Pau-com-Aproximacao/G83.PNG" width="250" />



# Observação
Recomendo utilizar o #1 entre 5 a 10mm abaixo do Z0 para a ponta da broca permanecer guiada.