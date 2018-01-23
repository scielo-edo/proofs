# Observações sobre notas de rodapé, notas de fim e especificidades das notas do template padrão


O template padrão escolhido para testar o conversor _jats2tex_ apresenta 
notas de rodapé do tipo "muitos para um", isto é, uma referência 
repetida inúmeras vezes no texto e que se liga a apenas um texto
de rodapé:

> Lorem*(a)* ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua*(a)*. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet*(a)*. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus*(a)* est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

> [Footnote] *(a)* At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
    
## Considerações

Nosso objetivo, nesta etapa do projeto, é demonstrar que a ferramenta de converção _jats2tex_ é 
capaz de converter tags em situações variadas. Para demonstrar isso, produzimos um template 
genérico SciELO a partir de um único xml. Entendemos que o tipo de nota "muitos para um" 
é uma exceção e que caberia, no caso, pensar numa solução genérica. Foi feito 
um esforço então para generalizar a referência para um padrão que atendesse a todas 
as revistas que optassem por uma estrutura do tipo "muitos para um", como 
as revistas que se utilizam de notas cruzadas por exemplo. 

Acreditamos que a discussão possa ser retomada no segundo momento do projeto, 
em que elaboraremos a descrição de todo o SPS (Cf. "SPSTeX", na proposta),
com o objetivo de criar um ou mais templates genéricos. 



                                                            J.S. e R.B.
 