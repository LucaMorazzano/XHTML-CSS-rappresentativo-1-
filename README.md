# XHTML-CSS-rappresentativo-1-

indirizzo repository GitHub: https://github.com/LucaMorazzano/XHTML-CSS-rappresentativo-1-.git

nome componenti gruppo: Luca Morazzano 	matricola 1920476
		        Andra Fionda 	matricola 1847591
La realizzazione dell'esercizio è basata sull'attivita pratica proposta nelle slide delle lezione (CSS-13). 
Il mini sito web realizzato è formato da tre pagine collegate tra loro attraverso l'uso del tag anchor href di html.
Segue una descrizione degli elementi usati e delle scelte di stile effettuate per ogni pagina presente nella directory:

- Home.html : la pagina home.html è basata su un layout a tre colonne a display flessibile che cambia
la disposizione degli elementi al rimpicciolirsi delle dimensioni della finestra di visualizzazione, l'effetto che si manifesta è una disposizione verticale degli elementi lungo una singola colonna;
una sezione header ed una footer. 
Nella sezione header sono presenti un logo, un titolo ed una lista contenente elementi anchor, che rimandano alle altre pagine del sito e che offrono delle animazioni quando il cursore si posiziona su di loro.
Questa animazione è stata realizzata mediante l'utilizzo della subclasse :hover.
Nella sezione principale ovvero quella compresa tra header e footer, il contenuto è disposto in un layout a tre colonne.
Nella colonna di sinistra è presente una tabella contenente le stanze disponibili. Tale tabella è stata stilizzata utilizzando la subclasse :hover
offrendo anche essa una sorta di animazione al passaggio del cursore su alcuni elementi.
Nella colonna centrale è stato inserito un paragrafo al quale è stata assegnata una classe che ne ha permesso una stilizzazione del font e del posizionamento.
Nella colonna di destra è presente un immagine posizionata in modo da avere un allineamento coerente al contenuto della pagina.
Al rimpicciolirsi della dimensione della finestra di visualizzazione il main content offre una disposizione verticale dove:
la colonna di sinistra va in cima a quella centrale che a sua volta precede quella di destra. Questo è stato possibile grazie all'uso
di una media_query che cambia la flex-direction in column quando si verificano le condizioni accennate poc'anzi.
Nella sezione footer troviamo invece un titolo realizzato con tag h2 e opportunamente stilizzato, seguito da una lista di immagini
a disposizione orizzontale che cambia in verticale al rimpicciolirsi della finestra di visualizzazione.

- Contatti.html : la pagina contatti.html è basata sullo stesso layout di home.html e ne eredita la stilizzazione per ogni contenuto presente.
Alcuni elementi sono stati stilizzati con css interni poichè usando lo stesso foglio di stile esterno usato per home.html, si verificavano
dei conflitti nella stilizzazione.

- Info.html : La pagina info.html è stata realizzata utilizzando un secondo foglio di stile chiamato "stile2.css". Il layout è basato
su un unica colonna composta da tre contenitori con bordi arrotondati (effetto realizzato grazie alla proprietà border-radius), che descrivono
i vari servizi presenti nell'hotel.

Sia info.html che contatti.html contengono il menu (adattato alla pagina) che permette la navigazione all'interno del sito.



PERCORSO INSTALLAZIONE LWEB:
Fionda: http://lweb.diag.uniroma1.it/~lweb18/RAPPRESENTATIVO1/contributo1
Morazzano: http://lweb.diag.uniroma1.it/~lweb25/RAPPRESENTATIVO%20CSS%201/contributo1.luca.morazzano/XHTML-CSS-rappresentativo-1--main/
