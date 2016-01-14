###Codi font  

Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text
resultants, on es troben les instruccions, es diu que contenen el __codi font__.
Aquest codi font pot ser d'es d'un nivell molt alt, molt a prop del
llenguatge humà, fins a un nivel més baix, més proper al codi de les màquines,
com ara el codi assemblador.  

El procés anomenat __compilació__ és la traducció del codi font dels fitxers
del programa en fitxers en format binari que contenen les instruccions en
un format que el processador pot entendre. El __codi objecte__ és el codi
font traduït per aquest compilador a codi màquina, pero aquest codi encara
no pot ser executat per l'ordinador.  

El __codi executable__ és la traducció completa a codi màquina, duta a terme per
l'enllaçador, el qual es pot interpretar directament amb l'ordinador  

El concepte de __màquina virtual__ sorgeix amb l'objectiu de facilitar el
desenvolupament de compiladors que generen codi per a diferents processadors.

La compilació consta de dos fases:  

* La primera parteix del codi font a un llenguatge intermedi obtenit un 
programa equivalent amb un menor nivell d'abstracció que l'original i que no
pot ser directament executat

* La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible
per la màquina.  
