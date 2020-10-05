# Obligatorisk oppgave 2 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 

# Krav til innlevering

Se oblig-tekst for alle krav. Oppgaver som ikke oppfyller følgende vil ikke få godkjent:

* Git er brukt til å dokumentere arbeid (minst 2 commits per oppgave, beskrivende commit-meldinger)	
* Ingen debug-utskrifter
* Alle testene som kreves fungerer (også spesialtilfeller)
* Readme-filen her er fyllt ut som beskrevet

# Arbeidsfordeling

Oppgaven er levert av følgende studenter:
* Navn Navnesen, S981737, s981737@oslomet.no
* ...

Vi har brukt git til å dokumentere arbeidet vårt. Vi har 16 commits totalt, og hver logg-melding beskriver det vi har gjort av endringer.

I oppgaven har vi hatt følgende arbeidsfordeling:
* Per har hatt hovedansvar for oppgave 1, 3, og 5. 
* Else har hatt hovedansvar for oppgave 2, 4, og 6. 
* Fatima har hatt hovedansvar for oppgave 7 og 8. 
* Vi har i fellesskap løst oppgave 10. 

# Beskrivelse av oppgaveløsning (maks 5 linjer per oppgave)

* Oppgave 1: The biggest challenges in task 1 were to get value with zero not to be counted in a. 
After much reseach it was solved by a single code; 
if (value == null)
continue;
It was also a challenge to find out if NullPointerException could be performed with a common throw exception, or if more code was needed. As an example 3.3.2. in the compendium. 
This was solved by using:
if (a == null) {
throw new NullPointerException ("The table is null");


* Oppgave 2:  The code for String toString() was found from Oppgaver til Avsnitt 3.3.2.2. It is for EnkeltLenketListe but
the logic for Doubbeltlenketliste in ascending order is the same. So we used it for String toString().
About String omvendtString() this is print out liste from back to front. EnkeltLenketListe has a link from head to tale and String toString() had Node<T> p = hode; p = p.neste;.
So we thought if we changed Node<T> p = hale; p = p.forrige; in omvendtString, it should work. Then we tried and it worked.
Both method should return "[]" when liste has no value. So we put if statement on the top of the code.

* Oppgave 3: Firstly, we need to have some help variable for Node what we wanted to find. Then we had to think several patterns.
1). When Node is the head.
2). When Node is the tail.
3). When Node is smaller than the half of number ( antall / 2 ) in the list, then search from head to the the half of number(antall / 2). 
If antall /2 became decimal, it made a problem later.
So we put (int) antall/2 for judgement number.
4). When Node is bigger than the half of number ( antall / 2 ), the Node would be searched from tail to the half of number.

hent(int indeks) was easy to code, we had already have finnNode() method, so find the node for int indeks then return value of that indeks.

* Oppgave 4: 


* Oppgave 5: For this oppgave, idea came from Kompedium Programkode 3.3.2 f), but this code was for EnkeltLenketListe, 
so we had to connect variable from tail to head. There were several patterns when a Node added.
1). When the list was blank from before adding
2). When a Node added to head of the list.
3). When a node added to tail of the list.
4). When a node added in the middle of the list.
After adding a Node, numbers of the list should add 1 and changing also increased.
 

* Oppgave 6:


* Oppgave 7:


* Oppgave 8:


* Oppgave 9:


* Oppgave 10:



 