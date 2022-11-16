##### zadanie_funkcja_calculate #####

live: https://hekterek.github.io/zadanie_funkcja_calculate/

Zadanie zrobilem bez wiekszych problemow. 

Moglbym skrocic ta czesc :

@else if $type == "o" {
$result: $var1 - $var2;
@return $result * 1px;

na

@else if $type == "o" {
@return $var1 - $var2 * 1px;


lecz nie podoba mi sie to ze w tym przypadku 
pierw dochodzi do mnozenia a nastepnie jest 
odejmowana liczba z jednostka od tej bez jednostki. 

Nie wiem ktore zastosowanie jest lepsze ?

Dziekuje 
