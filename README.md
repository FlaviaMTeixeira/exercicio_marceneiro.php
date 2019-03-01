# exercicio_marceneiro.php

<?php

//Um marceneiro, para fazer um trabalho, precisa cortar vários pedaços de madeira de 45cm cada um. Ele pode comprar tábuas de 3, 4

print "Informe o tamanho da tabua que você quer comprar em centímetros: ";

$tamanho_tabua = (int) fgets(STDIN);
$tamanho_pedaco_tabua = 45;


$quantidade_pedaco = (int) ($tamanho_tabua / $tamanho_pedaco_tabua) ;

$sobra_tabua = $tamanho_tabua % $tamanho_pedaco_tabua  ;

print "A quantidade de pedaços será $quantidade_pedaco, sobra $sobra_tabua cm";
