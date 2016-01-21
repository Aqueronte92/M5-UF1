##1.5 Característiques dels llenguatges més difosos  
Els llenguatges de programació més difosos són aquells que més es fan servir
en cadascun dels diferents àmbits de la informàtica. En l’àmbit educatiu, per
exemple, es considera un llenguatge de programació molt difós aquell que es fa
servir a moltes universitats o centres educatius per a la docència de la iniciació a
la programació.

###1.5.1 Característiques de la programació estructurada
La programació estructurada va ser desenvolupada pel neerlandès Edsger W.
Dijkstra i es basa en el denominat teorema de l’estructura. Per això utilitza
únicament tres estructures: seqüència, selecció i iteració, essent innecessari
l’ús de la instrucció o instruccions de transferència incondicional (GOTO, EXIT FUNCTION, EXIT SUB o múltiples RETURN).  
####Claredat
Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat: comentaris, noms de variables comprensibles i procediments
entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense
interrupcions en la seqüència normal de lectura.  
####Teorema de l’estructura
Demostra que tot programa es pot escriure utilitzant únicament les tres estructures
bàsiques de control:
* Seqüència: instruccions executades successivament, una darrere l’altra. A
la figura 1.8 es pot observar un exemple de l’estructura bàsica de seqüència,
on primer s’executarà la sentència A i, posteriorment, la B.  
####Disseny descendent
El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall.  
####Programació modular
Quan es parla de programació modular, ens referim a la divisió d’un programa
en parts més manejables i independents. Una regla pràctica per aconseguir aquest
propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un
pam de codificació.
En la majoria de llenguatges, els mòduls es tradueixen a:
* Procediments: són subprogrames que duen a terme una tasca determinada
i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i
millorar la seva claredat.
* Funcions: són subprogrames que duen a terme una determinada tasca i
retornen un únic resultat o valor. S’utilitzen per crear operacions noves que
no ofereix el llenguatge.
####Tipus abstractes de dades (TAD)
En programació, el tipus de dades d’una variable és el conjunt de valors que la
variable pot assumir. Per exemple, una variable de tipus booleà pot adoptar només
dos valors possibles: __vertader__ o __fals__ hi ha un conjunt limitat però ben
definit d’operacions que tenen sentit sobre els valors d’un tipus de dades; així,
operacions típiques sobre el tipus booleà són __AND__ o __OR__.

###1.5.2 Característiques de la programació orientada a objectes
Un dels conceptes importants introduïts per la programació estructurada és l’abstracció
de funcionalitats a través de funcions i procediments. Aquesta abstracció
permet a un programador utilitzar una funció o procediment coneixent només què
fa, però desconeixent el detall de com ho fa.  
Aquest fet, però, té diversos inconvenients:
* Les funcions i procediments comparteixen dades del programa, cosa que
provoca que canvis en un d’ells afectin a la resta.
* Al moment de dissenyar una aplicació és molt difícil preveure detalladament
quines funcions i procediments necessitarem.
* La reutilització del codi és difícil i acaba consistint a copiar i enganxar
determinats trossos de codi, i retocar-los. Això és especialment habitual
quan el codi no és modular.  
L’__orientació a objectes__ (en endavant, OO) és un paradigma de construcció
de programes basat en una abstracció del món real.  
Un __objecte__ és una combinació de dades (anomenades atributs) i mètodes
(funcions i procediments) que ens permeten interactuar amb ell. En OO,
doncs, els programes són conjunts d’objectes que interactuen entre ells a
través de missatges (crides a mètodes).  
####Abstracció
És el procés en el qual se separen les propietats més importants d’un objecte
de les que no ho són.  
En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la
classe. Es pot definir una classe com una descripció genèrica d’un grup d’objectes
que comparteixen característiques comunes, les quals són especificades en els seus
atributs i comportaments.  
####Encapsulació
Permet als objectes triar quina informació és publicada i quina informació és
amagada a la resta dels objectes. Les característiques que es poden atorgar són:
* Públic: qualsevol classe pot accedir a qualsevol atribut o mètode declarat
com a públic i utilitzar-lo.
* Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o mètode
declarat com a protegit a la classe mare i utilitzar-lo.
* Privat: cap classe no pot accedir a un atribut o mètode declarat com a privat
i utilitzar-lo.






Modularitat
Permet poder modificar les característiques de cada una de les classes que defineixen
un objecte, de forma independent de la resta de classes en l’aplicació. En altres
paraules, si una aplicació es pot dividir en mòduls separats, normalment classes,
i aquests mòduls es poden compilar i modificar sense afectar els altres, aleshores
aquesta aplicació ha estat implementada en un llenguatge de programació que
suporta la modularitat.
Jerarquia
Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un
sistema complex són l’herència i l’agregació.
L’herència també es pot veure com una forma de compartir codi, de manera que
quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò
que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el
comportament.
Per exemple, es pot identificar una classe pare anomenada ����������� i dues
classes filles, és a dir dos subtipus de treballadors, ������������� i ���������.
F����� �.��. Exemple d’herència
A la figura 1.12 es pot observar la representació en forma de diagrama de l’exemple
explicat anteriorment: les classes ������������� i ��������� que hereten de la
classe �����������.
L’agregació és un objecte que està format de la combinació d’altres objectes o
components. Així, un ordinador es compon d’una CPU, una pantalla, un teclat i
un ratolí, i aquests components no tenen sentit sense l’ordinador. A la figura 1.13
Entorns de desenvolupament 31 Desenvolupament de programari
es pot observar un exemple d’agregació en què la classe ��������� està composta
per les altres quatre classes.
F����� �.��. Exemple d’agregació
El polimorfisme
És una característica que permet donar diferents formes a un mètode, ja sigui en
la definició com en la implementació.
La sobrecàrrega (overload) de mètodes consisteix a implementar diverses vegades
un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el
compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres
de la crida.
Un exemple de mètode sobrecarregat és aquell que calcula el salari d’un treballador
en una empresa. En funció de la posició que ocupa el treballador tindrà més
o menys conceptes a la seva nòmina (més o menys incentius, per exemple).
El mateix mètode, que podríem anomenar CàlculSalari quedarà implementat
de forma diferent en funció de si es calcula el salari d’un operari (amb menys
conceptes en la seva nòmina, la qual cosa provoca que el mètode rebi menys
variables) o si es calcula el salari d’un directiu.
La sobreescriptura (override) de mètodes consisteix a reimplementar un mètode
heretat d’una superclasse exactament amb la mateixa definició (incloent nom de
mètode, paràmetres i valor de retorn).
Un exemple de sobrecàrrega de mètodes podria ser el del mètode ������. A partir
d’una classe ������ que conté el mètode ������, existeix una classe derivada per
a alguns tipus de figures (per exemple, ��������� o �������).
La implementació del mètode ������ serà diferent a cada una de les classes
derivades; aquestes poden implementar-se de forma diferent (en funció de com
es calculi en cada cas l’àrea de la figura) o definir-se de forma diferent.
