## crea un programa que solicite 10 numeros y si son negativos que los promedie, y si son negativos que los sume.
### algoritmo
* inicio algoritmo
* declaro variables (i,prom, sum,num,res2,cont)
* asigno i=0
* para i<=10 hacer
*         imprimir "ingresa un numero"
*         asignar a num
*         si num<=0 entonces
*            suma= suma+num
*         sino 
*         cont=cont+1
*         res2=res2+num
*         prom=res2/cont
*         fin si
*  fin para
*  mostrasr ("la suma de tus negativos es" suma,","," ", "el promedio de tus positivos es", " ", prom, 
*           


### segundo ejercicio
un programa que sume el costo de los productos hasta que el usuario precione "0" y si ingresa numeros negativos que salga un mensaje de cantidad invalida 

*inicio algoritmo
* declarar variables (num, sum,num2)
* imprimir " ingresa un numero"
* asignar a num
* mientras num sea diferente de 0 
*       hacer
*       sum=sum+num2
*       imprimir "ingresa otro numero o preciona 0 para continuar"
*       leer num
*       si num<=-1 entonces
*         imprimir "numero invalido"
*       sino
*       num2=num
* escribir "la suma de tus productos es" suma
