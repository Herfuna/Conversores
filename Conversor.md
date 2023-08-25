# Universidad Mariano Gálves de Guatemala
## Centro regional Boca del Monte
## _Curso de Algoritmos_

[![N|Solid](https://www.universidadesonline.com.gt/logos/thumb/logo-universidad-mariano-galvez-de-guatemala.png)](https://umg.edu.gt/miumg/)
## Conversiones de unidades de longitud
## _Pseudocodigo:_

> Algoritmo conversion_de_unidades
    definir cm,m,yd,v,pulg,p Como Real
    Definir op Como Entero
    Escribir "Seleccione a que unidad desea comvertir los centimetros,"
    Escribir "   1: Metros"
    Escribir "   2: Yardas"
    Escribir "   3: Varas "
    Escribir "   4: Pulgadas "
    Escribir "   5: Pies "
    leer op
    leer cm
    Si op == 1 Entonces
        m = cm/100
        escribir cm " en metros son: ", m;
    SiNo
        si op == 2 Entonces
            yd = cm/91.44
            Escribir cm " centimetros en yardas son: ", yd;
        sino
            si op== 3 Entonces
                v = cm/83.58
                Escribir cm " centimetros en vara son: ", v;
            SiNo
                si op == 4 Entonces
                    pulg = cm/2.54
                    Escribir cm " centimetros en pulgadas son: ", pulg;
                SiNo
                    si op == 5 Entonces
                        p = cm/30.48
                        Escribir cm " centimetros en pies son: ", p;
                    SiNo
                        si op >= 6 Entonces
                            Escribir "uupss esta opcion no existe, por favor eliga una del 1-5"
                        FinSi
                    FinSi
                FinSi
            FinSi
        FinSi
    Fin Si
FinAlgoritmo




## C++

> //programa que convierte cm en metros, yardas, varas, pulgadas y pies.
#include <iostream>
using namespace std;
int main()
{
float cm,m,yd,v,pulg,p;
int op;
cout << "Seleccione a que unidad desea comvertir los centimetros,"<<endl<<" 1. Metros "
" 2. Yardas "
" 3. Varas "
" 4. Pulgadas "
" 5. Pies ";
    cin>>op;
    cin>>cm;
    if (op == 1 ) {
        m = cm/100;
        cout << cm << " en metros son: "<<  m;
          }
          else if (op == 2) {
            yd = cm/91.44;
            cout << cm <<" en yardas son: "<< yd;
            }
            else if (op == 3){
                v = cm/83.58;
                cout << cm << " centimetros en vara son: "<<v;
            }
            else if (op == 4 ){
                pulg = cm/2.54;
                cout << cm << " centimetros en pulgadas son: "<< pulg;
            }
            else if (op == 5 ){
                p =cm/30.48;
                cout << cm << " centimetros en pies son: "<<p;
            }
            else if (op >= 6){
                cout << "uupss esta opcion no existe, por favor eliga una del 1-5";
            }
    return 0;
}

## Python
> #programa que convierte cm en metros, yardas, varas, pulgadas y pies.
print("1. metros 2. Yardas "
" 3. Varas "
" 4. Pulgadas "
" 5. Pies ")
op = int(input("seleccine la del 1-5 la opcion que quiere. "))
cm = float(input("Igrese el centimetro  que quiere convertir  "))
if op == 1:
    m = cm/100
    print(f" {cm} centimetros en metros son: {m} ")
elif op == 2:
         yd = cm/91.44
         print(f"{cm} centimetros en yardas son: {yd}")
elif op == 3:
    v = cm/83.58
    print(f"{cm }centimetros en varas son : {v}")
elif op == 4:
    pulg = cm/2.54
    print(f"{cm} centimetros en pulgadas son: {pulg}")
elif op == 5:
     p =cm/30.48
     print(f"{cm} centimetros en pies son: {p}")
else:
    print("epaa esta opcion no existe porfavor eliga una del 1-5, gracias")



Juan de Jesús Fuentes Hernández
7690-23-12943




[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
