<?xml version="1.0" encoding="utf-8"?>
<html xmlns="http://www.w3.org/1999/xhtml" lang="it" xml:lang="it">
<head>
 
<!-- 2018-08-28 mar 14:38 -->
<meta  http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta  name="generator" content="Org-mode" />
<meta  name="author" content="Avv. Franco Pasut, Novara" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center; }
  .todo   { font-family: monospace; color: red; }
  .done   { color: green; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  pre.src-sh:before    { content: 'sh'; }
  pre.src-bash:before  { content: 'sh'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-R:before     { content: 'R'; }
  pre.src-perl:before  { content: 'Perl'; }
  pre.src-java:before  { content: 'Java'; }
  pre.src-sql:before   { content: 'SQL'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.right  { text-align: center;  }
  th.left   { text-align: center;   }
  th.center { text-align: center; }
  td.right  { text-align: right;  }
  td.left   { text-align: left;   }
  td.center { text-align: center; }
  dt { font-weight: bold; }
  .footpara:nth-child(2) { display: inline; }
  .footpara { display: block; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2013 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
<script type="text/javascript" src="https://orgmode.org/mathjax/MathJax.js"></script>
<script type="text/javascript">
<!--/*--><![CDATA[/*><!--*/
    MathJax.Hub.Config({
        // Only one of the two following lines, depending on user settings
        // First allows browser-native MathML display, second forces HTML/CSS
        //  config: ["MMLorHTML.js"], jax: ["input/TeX"],
            jax: ["input/TeX", "output/HTML-CSS"],
        extensions: ["tex2jax.js","TeX/AMSmath.js","TeX/AMSsymbols.js",
                     "TeX/noUndefined.js"],
        tex2jax: {
            inlineMath: [ ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"], ["\\begin{displaymath}","\\end{displaymath}"] ],
            skipTags: ["script","noscript","style","textarea","pre","code"],
            ignoreClass: "tex2jax_ignore",
            processEscapes: false,
            processEnvironments: true,
            preview: "TeX"
        },
        showProcessingMessages: true,
        displayAlign: "center",
        displayIndent: "2em",

        "HTML-CSS": {
             scale: 100,
             availableFonts: ["STIX","TeX"],
             preferredFont: "TeX",
             webFont: "TeX",
             imageFont: "TeX",
             showMathMenu: true,
        },
        MMLorHTML: {
             prefer: {
                 MSIE:    "MML",
                 Firefox: "MML",
                 Opera:   "HTML",
                 other:   "HTML"
             }
        }
    });
/*]]>*///-->
</script>
</head>
<body>
<div id="content">

<div id="table-of-contents">
<h2>Indice</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Premessa  normativa e tecnica</a>
<ul>
<li><a href="#sec-1-1">1.1. Breve premessa normativa</a></li>
<li><a href="#sec-1-2">1.2. Premessa tecnica</a></li>
</ul>
</li>
<li><a href="#sec-2">2. Indirizzi relativi ed assoluti</a></li>
<li><a href="#sec-3">3. MS Word: la costruzione del collegamento</a></li>
<li><a href="#sec-4">4. MS Word: la trasformazione in PDF</a>
<ul>
<li><a href="#sec-4-1">4.1. Il metodo Esporta</a></li>
<li><a href="#sec-4-2">4.2. Il metodo Salva con nome</a></li>
<li><a href="#sec-4-3">4.3. Piccolo trucco nel caso in cui i collegamenti relativi non funzionino</a></li>
</ul>
</li>
<li><a href="#sec-5">5. LibreOffice Writer: configurazione preliminare</a></li>
<li><a href="#sec-6">6. LibreOffice Writer: la creazione del collegamento</a></li>
<li><a href="#sec-7">7. LibreOffice Writer, la trasformazione in PDF</a></li>
<li><a href="#sec-8">8. Ed ora: LaTeX!</a></li>
<li><a href="#sec-9">9. LaTeX: creazione del collegamento</a></li>
<li><a href="#sec-10">10. LaTeX: analisi del codice sorgente</a></li>
<li><a href="#sec-11">11. LaTeX: il risultato prima e  dopo la compilazione</a></li>
<li><a href="#sec-12">12. Tabella di sintesi</a></li>
<li><a href="#sec-13">13. Esempi da scaricare</a></li>
</ul>
</div>
</div>

<div id="fig:-word_writer_latex" class="figure">
<p><a href="https://2.bp.blogspot.com/-20rhbDaJ7FI/W38TeWXNdyI/AAAAAAAAUG4/42d4PhQCswAh5DVI3JH82XlChSOGvtqFwCLcBGAs/s1600/word_writer_latex.png%0A" width="80%"><img src="https://2.bp.blogspot.com/-20rhbDaJ7FI/W38TeWXNdyI/AAAAAAAAUG4/42d4PhQCswAh5DVI3JH82XlChSOGvtqFwCLcBGAs/s1600/word_writer_latex.png" alt="word_writer_latex.png" width="80%" /></a>
</p>
<p><span class="figure-number">Figura 1:</span> Word, Writer,  LaTeX in sovrapposizione sfumata</p>
</div>

<div id="outline-container-sec-1" class="outline-2">
<h2 id="sec-1"><span class="section-number-2">1</span> Premessa  normativa e tecnica</h2>
<div class="outline-text-2" id="text-1">
</div><div id="outline-container-sec-1-1" class="outline-3">
<h3 id="sec-1-1"><span class="section-number-3">1.1</span> Breve premessa normativa</h3>
<div class="outline-text-3" id="text-1-1">
<p>
Questo articolo  è  rivolto principalmente ad Avvocati ed altri operatori del diritto che debbano, in  particolare nel sistema PCT,  predisporre atti con documenti <i>collegati</i>.
In considerazione del <i>target</i>, ritengo opportuno soltanto  un  cenno alla norma  norma di riferimento costituita dall'art. 4, comma 1 bis, del DECRETO del Ministro della giustizia 10 marzo 2014, n. 55 introdotto dall'art. 1 del DECRETO 8 marzo 2018, n. 37 del Ministero della Giustizia, pubblicato sulla GU n. 96 del 26-4-2018.
</p>

<p>
Nel testo della norma i <i>documenti</i> sono menzionati nella parte relativa alla  <i>ricerca testuale</i> (il frammento è il seguente: "<i>quando
esse consentono la ricerca testuale all'interno dell'atto e dei <b>documenti</b> allegati</i>") ma non in quella relativa alla <i>navigazione</i> (il frammento è il seguente: "<i>nonchè la
navigazione all'interno dell'atto</i>").
</p>

<p>
Questo significa che la <i>navigazione tramite collegamenti  tra atto e documenti</i> non è strettamente richiesta per l'incremento percentuale dei parametri.
</p>

<p>
Tuttavia la creazione di  collegamenti è un ottimo sistema per rendere più agevole la lettura e, quindi, lo studio degli atti giudiziari da parte dei Magistrati, dei difensori delle parti avverse nonchè, a futura memoria, di chi ha redatto gli atti stessi.
</p>

<p>
La creazione di collegamenti può, pertanto, trovare un fondamento nella prima parte della stessa norma sopra menzionata in cui viene invocata la redazione degli atti "<i>con tecniche informatiche idonee ad agevolarne la consultazione o la fruizione</i>".
</p>
</div>
</div>

<div id="outline-container-sec-1-2" class="outline-3">
<h3 id="sec-1-2"><span class="section-number-3">1.2</span> Premessa tecnica</h3>
<div class="outline-text-3" id="text-1-2">
<p>
In questo articolo sono descritte le <b>funzionalità integrate</b>, ovvero senza l'utilizzo di  applicazioni esterne  di tre sistemi di <i>editing</i>,  già menzionati nel precedente articolo dedicato agli <a href="https://francopasut.blogspot.com/2018/05/atti-ipertestuali-e-processo-civile.html">ATTI IPERTESTUALI E PCT</a>, ovvero <i>MS Word</i>, <i>LibreOffice Writer</i> e <i>LaTeX</i>.
</p>

<p>
I tre software analizzati  sono utilizzabili in ambiente <i>Windows</i>, <i>macOS</i> e <i>GNU/Linux</i>  ad eccezione di Word per il quale non esiste ancora una versione nativa per <i>GNU/Linux</i>.
</p>


<p>
Occorre, tuttavia, precisare che il collegamento tra atti e documenti esterni funziona, come emerso dai nostri  test, solo se tutto il materiale su trova in una stessa <b>cartella locale</b>. 
</p>

<p>
In  altri termini, allo stato attuale della tecnologia del PCT ci risulta, salvo implementazioni <i>medio tempore</i> intervenute, che sul <i>Polisweb</i> i collegamenti ipertestuali verso documenti esterni non siano ancora utilizzabili e che, pertanto,  per beneficiare degli stessi  sia necessario  <b>prima</b> scaricare tutto il materiale (ovvero atti e documenti collegati) in una stessa cartella locale e, <b>poi</b>, lanciare <b>in locale</b> i collegamenti.
</p>
</div>
</div>
</div>

<div id="outline-container-sec-2" class="outline-2">
<h2 id="sec-2"><span class="section-number-2">2</span> Indirizzi relativi ed assoluti</h2>
<div class="outline-text-2" id="text-2">
<p>
Questa premessa serve ad  inquadrare l'argomento  dei percorsi di ricerca dei documenti collegati tra loro, ben conosciuta soprattutto da chi si occupa di gestire siti <i>web</i>,  anche per la  risoluzione di alcuni possibili problemi di malfunzionamento dei collegamenti.
</p>



<p>
In sintesi: un collegamento è <b>assoluto</b> quando avviene esclusivamente se il file da collegare si trova in un  percorso specifico. Esempio: in un collegamento all'interno del percorso assoluto  <code>C:\Users\Fpasut\Documents\Report.pdf</code> il collegamento avverrà sempre e soltanto se il file <i>Report.pdf</i> si trova <b>esattamente</b> nella cartella finale del percorso stesso.
</p>

<p>
Un collegamento è <b>relativo</b> quando è sufficiente che i documenti si trovino in una stessa cartella o in cartelle subordinate tra loro <b>a prescindere dai percorsi superiori rispetto a  tali cartelle</b>.
</p>

<p>
Per riprendere l'esempio sopra riportato, in un collegamento relativo il file <i>Report.pdf</i> potrà essere collegato a qualsiasi altro documento presente nella stessa cartella <code>(...).\Documents\</code> come in qualsiasi altra cartella a prescindere da quale sia il percorso superiore.
</p>


<p>
L'argomento è chiarito molto bene nel paragrafo <a href="https://help.libreoffice.org/Common/Relative_and_Absolute_Links/it">Collegamenti relativi e assoluti</a> tratto dalle istruzioni on-line di <i>LibreOffice</i> dal quale riporto alcuni frammenti:
</p>

<em>

 <p>
 Un percorso assoluto come "C:\homepage\immagini\foto.gif" non funzionerebbe più sul server del provider. Sul server o sul computer di un visitatore del sito potrebbe non esistere il drive C: i sistemi operativi quali Unix o MacOS non riconoscono le lettere dei drive e anche se fosse presente la cartella homepage\immagini, la figura non sarebbe disponibile. È preferibile utilizzare l'indirizzamento relativo per i link a file
 </p>

 <p>
 Se posizionate il mouse su un collegamento appare un suggerimento che mostra il percorso assoluto, in quanto LibreOffice funziona internamente sempre con percorsi assoluti. Il percorso completo e l'indirizzo sono visibili solamente osservando il risultato dell'esportazione HTML, ad esempio caricando il file HTML creato come "Testo" o aprendolo con un editor di testo.
 </p>
</em>






<p>
La soluzione è illustrata nello stesso documento con le seguenti indicazioni:
</p>
<em>
 <p>
 Scegliete Strumenti - Opzioni - Carica/Salva - Generale e specificate nel campo Salvare URL relativamente a se LibreOffice crea collegamenti ipertestuali relativi o assoluti. Il collegamento relativo si crea solo quando il documento su cui si sta lavorando e la destinazione del collegamento si trovano nella stessa unità di memorizzazione.
 </p>
</em>



<p>
La premessa è importante per  chiarire le impostazioni dei documenti esterni collegati all'atto principale.
</p>

<p>
Nel nostro caso occorre, ovviamente, impostare tutti i programmi con <b>collegamenti relativi</b> per consentire a chiuque abbia la possibilità di scaricare il materiale in una qualsiasi cartella presente sul proprio computer di avere il beneficio dei collegamenti attivi. 
In caso contrario soltanto l'utente che ha generato i collegamenti potrebbe utilizzare i collegamenti.
</p>


<p>
Tenendo conto delle premesse iniziamo l'analisi dei singoli <i>software</i>.
</p>
</div>
</div>

<div id="outline-container-sec-3" class="outline-2">
<h2 id="sec-3"><span class="section-number-2">3</span> MS Word: la costruzione del collegamento</h2>
<div class="outline-text-2" id="text-3">
<p>
In un documento aperto con MS Word, selezioniamo l'elemento da collegare (ad esempio una parola) e utilizziamo la voce <i>INSERISCI - Collegamento Ipertestuale</i> oppure, molto più velocemente, utilizziamo la combinazione di tasti <code>ALT+CTRL+K</code>; sotto Windows o <code>CMD+K</code> sotto macOS, nella finestra che appare selezioniamo il documento da collegare e premiamo OK.
</p>


<p>
Nell'immagine seguente riporto una schermata della creazione del collegamento nella versione per Windows:
</p>

<div id="fig:costruzione_collegamento_word_windows" class="figure">
<p><img src="https://3.bp.blogspot.com/-ASlPYhRYgBQ/W38JLeFpHzI/AAAAAAAAUF8/-lAIaEY-BJYz_8x9ocFqtFL6UW9oMSuCQCLcBGAs/s1600/scelta_collegamento_word.png" alt="scelta_collegamento_word.png" width="80%" />
</p>
<p><span class="figure-number">Figura 2:</span> La costruzione del collegamento in Windows</p>
</div>


<p>
Nell'immagine seguente riporto una schermata della creazione del collegamento nella versione per macOS:
</p>


<div id="fig:costruzione_collegamento_word_mac" class="figure">
<p><img src="https://2.bp.blogspot.com/-SxrkKUkNiro/W4ELX9sVaTI/AAAAAAAAUHc/ZvItqlYE7SEBjVfstwr62jsfXF3hehm4QCLcBGAs/s1600/Schermata+2018-08-25+alle+09.05.40.png" alt="Schermata+2018-08-25+alle+09.05.40.png" width="80%" />
</p>
<p><span class="figure-number">Figura 3:</span> La costruzione del collegamento in macOS</p>
</div>


<p>
La costruzione del collegamento deve avvenire con il file di partenza e quello di arrivo <b>nella stessa cartella</b>, altrimenti il sistema creerebbe un riferimento <b>assoluto</b> alla diversa cartella in cui si trova il documento collegato.
</p>




<p>
La parola risulterà sottolineata in blu, secondo lo standard generale dei <i>link web</i>.
Word ha due possibilità di salvataggio diretto in PDF: il comando <i>Crea documenti PDF/XPS</i> sotto <i>File/Esporta</i> ed il comando <i>Salva con nome</i>.
</p>


<p>
In entrambi i casi si arriva alla creazione del link diretto tra il documento di origine e quello collegato.
</p>
</div>
</div>

<div id="outline-container-sec-4" class="outline-2">
<h2 id="sec-4"><span class="section-number-2">4</span> MS Word: la trasformazione in PDF</h2>
<div class="outline-text-2" id="text-4">
<p>
A questo punto occorre preliminarmente precisare che soltanto Word per Windows ha è dotato in modo nativo della funzionalità di salvataggio diretto in PDF <b>con conservazione dei link ipertestuali</b>. 
</p>

<p>
Nella versione macOS di Word il  salvataggio in PDF avviene, a meno che non si utilizzino aggiunte al programma, sì regolarmente ma i collegamenti presenti nel documento non vengono esportati.
</p>


<p>
In alternativa ad eventuali elementi aggiuntivi di terze parti si può aprire il documento creato con Word in <i>LibreOffice Writer</i> ed utilizzare la propria funzione di <i>esportazione in PDF</i>, come da procedimento illustrato più sotto.
</p>


<p>
Le indicazioni seguenti, pertanto, sono relative alla versione di Word in ambiente Windows in cui, come sopra evidenziato, non occorre utilizzare alcun applicativo intermedio.
</p>

<p>
Word per Windows  ha due possibilità di salvataggio diretto in PDF: il comando <i>Crea documenti PDF/XPS</i> sotto <i>File/Esporta</i> ed il comando <i>Salva con nome</i>.
</p>
</div>
<div id="outline-container-sec-4-1" class="outline-3">
<h3 id="sec-4-1"><span class="section-number-3">4.1</span> Il metodo Esporta</h3>
<div class="outline-text-3" id="text-4-1">
<p>
Per procedere con  primo metodo di creazione del PDF si utilizzano i comandi da menù <i>File, Esporta, Crea documento PDF/XPS</i> e si preme il tasto <i>Pubblica</i> (notare il termine Pubblica al posto di Salva).
</p>


<div id="fig:word_pubblica_pdf" class="figure">
<p><img src="https://1.bp.blogspot.com/-Yycb0GzHmjQ/W38LtMERiZI/AAAAAAAAUGM/f3RkWB3HmWMFtwoDIDT0GWn56WnsqV7-gCLcBGAs/s1600/pubblica_word.png" alt="pubblica_word.png" width="80%" />
</p>
<p><span class="figure-number">Figura 4:</span> Word, Pubblica in PDF</p>
</div>


<p>
Avremo un file in formato PDF con un collegamento incorporato.
</p>

<p>
Proviamo ad aprire il collegamento nella cartella dove abbiamo effettuato l'operazione: tutto funzionerà correttamente (eventualmente dopo il superamento del tradizionale <i>Avviso di protezione</i> che in questo caso non pone alcun dubbio  trattandosi di collegamento che abbiamo creato noi).
</p>


<div id="fig:allarme_protezione_windows" class="figure">
<p><img src="https://1.bp.blogspot.com/-yDDxw29o2K8/W38OZwYY-pI/AAAAAAAAUGg/ofNd-vbhHekezmNgIphPr4PJi0K5OV4UACLcBGAs/s1600/finestra_allarme.png" alt="finestra_allarme.png" width="50%" />
</p>
<p><span class="figure-number">Figura 5:</span> Finestra di allarme  in Windows</p>
</div>



<div id="fig:allarme_protezione_mac" class="figure">
<p><img src="https://1.bp.blogspot.com/-DmwE93dD8DE/W4EOE-IDWMI/AAAAAAAAUHo/hdc97UUKs3YjZUUNWgd0w9knFpd8xx5dQCLcBGAs/s1600/Schermata+2018-08-25+alle+10.04.57.png" alt="Schermata+2018-08-25+alle+10.04.57.png" width="50%" />
</p>
<p><span class="figure-number">Figura 6:</span> Finestra di allarme in macOS</p>
</div>


<p>
Proviamo a spostare (attenzione: NON copiare ma spostare perchè altrimenti rimarrebbe il file obiettivo nel punto precedente e non cambierebbe alcunchè) i due file collegati in una cartella diversa  e ad attivare lo stesso collegamento: se tutto è andato liscio il collegamento funzionarà anche in questo caso.
</p>
</div>
</div>

<div id="outline-container-sec-4-2" class="outline-3">
<h3 id="sec-4-2"><span class="section-number-3">4.2</span> Il metodo Salva con nome</h3>
<div class="outline-text-3" id="text-4-2">
<p>
La stessa operazione può essere effettuata con il secondo metodo, ovvero con <i>Salva con nome</i> seguito, ovviamente, nel campo <i>Salva come</i> dal tipo documento <i>PDF</i> e <i>Salva</i> (non più <i>Pubblica</i> ma <i>Salva</i>). 
</p>

<p>
Anche in questo caso  il collegamento, salvo imprevisti, funzionerà sia nella cartella di origine che in una qualsiasi cartella dove siano presenti entrambi i documenti.
</p>


<div id="fig:word_salva_con_nome" class="figure">
<p><img src="https://2.bp.blogspot.com/-rbOPFEgtfS8/W38LzxIhpiI/AAAAAAAAUGQ/QNA6LTL38ZYUM3CBFcxOatXJEFqF_tmZwCLcBGAs/s1600/salva_word.png" alt="salva_word.png" width="80%" />
</p>
<p><span class="figure-number">Figura 7:</span> Word, Salva con Nome</p>
</div>


<p>
Trattasi di una concreta applicazione del principio del <i>collegamento ipertestuale relativo</i> spiegato nel relativo paragrafo di questo articolo.
</p>
</div>
</div>

<div id="outline-container-sec-4-3" class="outline-3">
<h3 id="sec-4-3"><span class="section-number-3">4.3</span> Piccolo trucco nel caso in cui i collegamenti relativi non funzionino</h3>
<div class="outline-text-3" id="text-4-3">
<p>
Può capitare che un collegamento, creato  con il primo o il secondo procedimento sopra descritto, non funzioni in una cartella <i>diversa</i> da quella in cui è stato creato.
</p>

<p>
Per superare questo inconveniente è possibile provare ad utilizzare un piccolo trucco: lanciate il collegamento <b>subito dopo la creazione</b>, quindi nella stessa cartella in cui è stato creato. In questo modo si sblocca il <i>link</i> ed il documento potrà, poi,  essere aperto ovunque si trovi a patto, ovviamente, che nella stessa cartella si trovi anche il documento contenente il collegamento di partenza.
</p>
</div>
</div>
</div>

<div id="outline-container-sec-5" class="outline-2">
<h2 id="sec-5"><span class="section-number-2">5</span> LibreOffice Writer: configurazione preliminare</h2>
<div class="outline-text-2" id="text-5">
<p>
Una delle caratteristiche più interessanti di tutte le componenti di LibreOffice è la totale omogeneità dell'interfaccia in ogni sistema operativo.
</p>

<p>
Questo significa che le operazioni descritte per un sistema operativo sono totalmente applicabili anche alle versioni di altri sistemi operativi con notevole semplificazione per chi opera in vari ambienti di lavoro.
</p>


<p>
In <i>LibreOffice Writer</i> la procedura è, in ogni caso, molto simile a quella sopra descritta per <i>Word</i>  ma con una differenza fondamentale: di <i>default</i> i collegamenti in questo software hanno un <b>indirizzo assoluto</b> (a questo proposito richiamo il <i>paragrafo dedicato a questo argomento</i>).
</p>

<p>
Per trasformare gli indirizzi da <b>assoluti</b> a <b>relativi</b> è necessario intervenire sulla configurazione del sistema.
</p>

<p>
La prima operazione, ma da effettuare <i>una tantum</i> è, quindi, quella di modificare la <i>Configurazione Generale</i> della voce <i>Carica/Salva</i> attivando le voci <i>Salva URL relativamente al file system</i> e <i>Salva URL relativamente a internet</i>, come indicato nelle istruzioni del programma stesso.
</p>



<div id="fig:-writer_impostazioni_generali" class="figure">
<p><img src="https://2.bp.blogspot.com/-QdCuEjozPW0/Wy-nEb4fnfI/AAAAAAAASU8/vfK2uOVuHncKX3U0OMl0tC2fGc7zk2mtQCLcBGAs/s1600/Impostazioneediting.jpg" alt="Impostazioneediting.jpg" width="80%" />
</p>
<p><span class="figure-number">Figura 8:</span> LibreOffice Writer, le configurazioni generali</p>
</div>
</div>
</div>

<div id="outline-container-sec-6" class="outline-2">
<h2 id="sec-6"><span class="section-number-2">6</span> LibreOffice Writer: la creazione del collegamento</h2>
<div class="outline-text-2" id="text-6">
<p>
Per la creazione del collegamento si procede come segue: in un documento in formato LibreOffice (tipicamente con estensione <i>.odt</i>), si seleziona un elemento (ad esempio una parola) da collegare ad un altro; si utilizza la voce di menù <i>Inserisci; Collegamento</i> oppure la combinazione di tasti <code>Ctrl-k</code>; nella finestra che appare si seleziona l'opzione <i>Documento</i> (le altre opzioni sono <i>Internet</i>, <i>Posta</i> e <i>Nuovo Documento</i>); nel campo in alto si inserisce il percorso del documento da collegare (per facilitare il compito è possibile utilizzare l'icona della cartella che apre la finestra di selezione in modalità grafica); si seleziona il documento e si preme <i>OK</i> oppure <i>Applica</i>.
</p>

<p>
Di seguito riporto un'immagine del procedimento sopra descritto.
</p>


<div id="fig:-writer_creazione_collegamento" class="figure">
<p><img src="https://2.bp.blogspot.com/-NE0OkhyKzw0/W320KIdsKlI/AAAAAAAAUFA/hY-XN5OlGRY59WejqoECctPwreRW3MOegCLcBGAs/s1600/finestra_selezione_writer_evidenziata.png" alt="finestra_selezione_writer_evidenziata.png" width="80%" />
</p>
<p><span class="figure-number">Figura 9:</span> LibreOffice, la creazione del collegamento</p>
</div>

<p>
Abbiamo, quindi, ottenuto il documento in formato Writer con il collegamento incorporato. 
</p>

<p>
Ora occorre trasformare il documento in PDF. Rammentiano che questa operazione può essere svolta anche sui documenti creati in Word (ovvero con estensione <code>.docx</code>) per superare il limite già sopra descritto di quel software.
</p>
</div>
</div>

<div id="outline-container-sec-7" class="outline-2">
<h2 id="sec-7"><span class="section-number-2">7</span> LibreOffice Writer, la trasformazione in PDF</h2>
<div class="outline-text-2" id="text-7">
<p>
Per la <i>trasformazione</i> in PDF utilizziamo la voce   menù <i>“Esporta come PDF…”</i> e, prima di procedere, attiviamo  le opzioni <i>“Converti i riferimenti di un documenti nei parametri del formato PDF”</i> e <i>“Esporta URL relativi al file system”</i>.
</p>






<div id="fig:impostazione_esportazione_writer" class="figure">
<p><img src="https://1.bp.blogspot.com/--9s2_OUfveA/W323XfLF0tI/AAAAAAAAUFM/4bzV_auhvOsbBVwjaGZUleUHoVn7bNpdACLcBGAs/s1600/config_esportaz_writer.png" alt="config_esportaz_writer.png" width="80%" />
</p>
<p><span class="figure-number">Figura 10:</span> Configurazione di esportazione in Writer</p>
</div>

<p>
Le  due opzioni, una volta selezionate, vengono memorizzate nel sistema anche per le successive operazioni, sino a modifiche manuale. Pertanto nelle esportazioni successive sarà sufficiente utilizzare l'opzione più veloce <i>Esporta direttamente in PDF</i>.
</p>

<p>
A questo punto clicchiamo sul pulsante <i>Esporta</i> e, nella finestra successiva, <i>Salva</i>.  Finito!
</p>

<p>
Anche in questo caso è meglio provare il collegamento sia in locale, ovvero nella cartella dove lo abbiamo appena creato  che trasportando tutto  in altra cartella.
</p>
</div>
</div>

<div id="outline-container-sec-8" class="outline-2">
<h2 id="sec-8"><span class="section-number-2">8</span> Ed ora: LaTeX!</h2>
<div class="outline-text-2" id="text-8">
<p>
A questo punto passiamo al terzo sistema di <i>editing</i>:  <i>LaTeX</i>.
</p>

<p>
<i>LaTeX</i> non è, tecnicamente, un <i>software di editing</i> ma è un <i>linguaggio di marcatura dedicato all'editing</i>, ovvero un linguaggio strutturato creato al solo fine di ottenere la <i>migliore impaginazione possibile</i> di qualsiasi documento.
</p>


<p>
I vantaggi di un linguaggio strutturato come <i>LaTeX</i> rispetto a qualsiasi software di videoscrittura <i>tradizionale</i>, sono, in sintesi, quelli della possibilità di personalizzazione  senza limiti unito alla massima  velocità di redazione dei contenuti.
</p>

<p>
L'unico <i>prezzo</i> di pagare è costituito da un  breve periodo d <i>training</i> per poter padroneggiare la sintassi di base.
</p>

<p>
Per il resto il sistema è del tutto gratuito e totalmente disponibile in qualsiasi ambiente operativo (tra cui: <i>Windows</i>, <i>macOS</i> e <i>GNU/Linux</i>).
</p>

<p>
Oltre alla descrizione passo-passo della creazione di un <i>link</i> ipertestuale in <i>LaTeX</i> tra un atto ed un documento, ho allegato  al presente articolo  un archivio ZIP contenente, tra gli altri, sia il sorgente che il PDF generato.
</p>
</div>
</div>

<div id="outline-container-sec-9" class="outline-2">
<h2 id="sec-9"><span class="section-number-2">9</span> LaTeX: creazione del collegamento</h2>
<div class="outline-text-2" id="text-9">
<p>
Avendo a che fare con un vero e proprio  <i>linguaggio</i> il collegamento tra due documenti in LaTeX deve essere creato, ovviamente, con <i>linee di codice</i>.
</p>


<p>
Nella parte preliminare  (ovvero nella parte che arriva fino al comando <code>\begin{document}</code>) del documento principale, occorre, prima di inserie il codice nell'atto, richiamare la  libreria <code>{hyperref}</code>.
</p>

<p>
In pratica è sufficiente  inserire, all'inizio del documento,  il comando: <code>\usepackage{hyperref}</code>.
</p>

<p>
Basta questa piccola aggiunta per aprire le potenzialità dei collegamenti ipertestuali di LaTeX!
</p>

<p>
A questo punto possiamo inserire lo specifico  comando di collegamento nei punti desiderati, come illustrato nella sezione seguente.
</p>
</div>
</div>

<div id="outline-container-sec-10" class="outline-2">
<h2 id="sec-10"><span class="section-number-2">10</span> LaTeX: analisi del codice sorgente</h2>
<div class="outline-text-2" id="text-10">
<p>
Per illustrare il procedimento di creazione dei collegamenti ipertestuali in <i>LaTeX</i>  ho predispoto un frammento di sorgente relativo ad un <b>ELENCO DOCUMENTI</b> tipicamente da collocare in calce ad un atto giudiziario nella sezione <i>Documenti prodotti</i> (o simile):
</p>

<div class="org-src-container">

<pre class="src src-latex">\begin{compactenum}
\item \href[pdfnewwindow]{run:./DOC 01.pdf}{Primo documento}
\item \href[pdfnewwindow]{run:./DOC 02.pdf}{Secondo documento}
\item \href[pdfnewwindow]{run:./DOC 03.pdf}{Terzo documento}
\item \href[pdfnewwindow]{run:./DOC 04.pdf}{Quarto documento}
\item \href[pdfnewwindow]{run:./DOC 05.pdf}{Quinto documento}
\end{compactenum}
</pre>
</div>

<p>
In questo frammento sono racchiuse vari comandi che analizzo separatemente:
</p>

<ul class="org-ul">
<li>la coppia <code>\begin</code> e <code>\end</code> associata a <code>{compactitem}</code> apre e chiude l'ambiente di numerazione compatta che viene attivata inserendo nella prefazione il comando <code>\usepackage{paralist}</code>.
</li>
<li>la numerazione automatica viene, poi, generata  tramite il prefisso <code>\item</code> prima di ogni riga.
</li>
<li>il comando <code>\href</code> attiva le funzionalità ipertestuali rese disponibili dalla libreria <code>{hyperref}</code> sopra menzionata.
</li>
<li>l'opzione <code>[pdfnewwindow]</code> consente l'apertura di una <b>nuova finestra</b> contenente il PDF collegato. Senza tale opzione il PDF andrebbe a sostituire il documento di origine.
</li>
<li>il comando <code>{run:</code> lancia il documento collegato che viene materialmente descritto nella sequenza <code>./DOC 01.pdf}</code> e altre analoghe.
</li>
<li>Il particolare frammento  <code>./</code> ha un significato molto preciso: attiva il <b>riferimento relativo</b> (richiamo le osservazioni in premessa sull'argomento) alla <i>cartella corrente</i>, a prescindere da quale essa sia e da dove si si trovi, per la ricerca del documento collegato. 
</li>
<li>la parte finale del codice, ad esempio <code>{Primo documento}</code> contiene il <b>nome che sarà visualizzato</b> nell'elaborato finale.
</li>
</ul>

<p>
Nel frammento ho utilizzato  le funzionalità di <i>numerazione compatta</i> che, per gli atti  giudiziari, sono preferibili quelle  di lista integrate nativamente in  LaTeX in quanto non lasciano spazi bianchi in eccedenza.
</p>
</div>
</div>

<div id="outline-container-sec-11" class="outline-2">
<h2 id="sec-11"><span class="section-number-2">11</span> LaTeX: il risultato prima e  dopo la compilazione</h2>
<div class="outline-text-2" id="text-11">
<p>
Il risultato, prima e dopo la compilazione del codice (rammento che il sorgente LaTeX, come illustrato in precedenti articoli, deve essere compilato per giungere alla propria forma finale in PDF), è il seguente (i nomi sono liberamente tratti dal romando di Herman Hesse "<i>Il Giuoco delle Perle di Vetro</i>":
</p>




<div id="fig:latex_sorgente_finale" class="figure">
<p><img src="https://3.bp.blogspot.com/-GZN_RXhMEG4/W4ROZQjcPzI/AAAAAAAAUJA/1MD_H7pEoQ0SuE8bmgoZb27LFlBm6hSfACLcBGAs/s1600/latex_risultato_finale.png" alt="latex_risultato_finale.png" width="80%" />
</p>
<p><span class="figure-number">Figura 11:</span> LaTeX, sorgente e risultato finale</p>
</div>



<p>
Da notare, nell'immagine seguente:
</p>
<ul class="org-ul">
<li>le DUE SCHEDE in alto nello <b>stesso lettore</b> di PDF
</li>
<li>Il sommario ipertestuale a sinistra (l'atto di origine è, infatti, stato redatto con le tecniche descritte nel mio precedente articolo menzionato in premessa)
</li>
<li>L'elenco documenti con le sovraimpressioni ipertestuali (sono, come già illustrato nel precedente articolo) dei semplici ma efficaci richiami, visibili a monitor ma <b>non stampabili</b>, che indicano la presenza di collegamenti ipertestuali (anche questi si possono, comunque, nascondere).
</li>
</ul>


<div id="fig:risultato_latex" class="figure">
<p><img src="https://2.bp.blogspot.com/-afBkNobYx6c/W326pbBk87I/AAAAAAAAUFY/CMwKA6BGqEQXwzFEA-M5IlgwRpjmQokMgCLcBGAs/s1600/risultato_latex.png" alt="risultato_latex.png" width="80%" />
</p>
<p><span class="figure-number">Figura 12:</span> Il risultato finale in LaTeX</p>
</div>


<p>
Dall'immagine sopra riportato si può notare che, contrariamente a quanto accade con i due software precedenti, l'apertura dei documenti collegati con il codice sopra descritto avviene nello stesso lettore di PDF <i>stand alone</i> e non nella versione incorporata nel <i>browser</i>.
</p>

<p>
Questo facilita la lettura comparata dei documenti collegati tra loro sopratutto negli applicativi, come Adobe Acrobat Reader <b>DC</b> (ovvero <b>Document Cloud</b>) che aprono i vari  PDF in schede istanziate in unico applicativo  piuttosto che in finestre separate.
</p>
</div>
</div>

<div id="outline-container-sec-12" class="outline-2">
<h2 id="sec-12"><span class="section-number-2">12</span> Tabella di sintesi</h2>
<div class="outline-text-2" id="text-12">
<p>
Per rappresentare in modo sintetico  quanto sopra riportato  ho creato  una <b>tabella comparativa</b> con l'indicazione delle  compatibilità di sistema  e con alcune note specifiche.
</p>



<table id="tab:tabella_comparativa" border="2" cellspacing="0" cellpadding="6" rules="all" frame="border" table style="margin: auto;">
<caption class="t-above"><span class="table-number">Tabella 1:</span> Tabella comparativa dei software analizzati</caption>

<colgroup>
<col  class="left" />

<col  class="left" />

<col  class="left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="left">Software</th>
<th scope="col" class="left">Sistema Oper.</th>
<th scope="col" class="left">Note</th>
</tr>
</thead>
<tbody>
<tr>
<td class="left">MS Word</td>
<td class="left">Windows, macOS</td>
<td class="left">In macOS non mantiene i link nel PDF</td>
</tr>

<tr>
<td class="left">LibreOffice</td>
<td class="left">Windows, macOS, GNU/Linux</td>
<td class="left">Interfaccia uniforme in ogni ambiente</td>
</tr>

<tr>
<td class="left">LaTeX</td>
<td class="left">Windows, macOS, GNU/Linux</td>
<td class="left">Occorre conoscere il linguaggio</td>
</tr>
</tbody>
</table>
</div>
</div>

<div id="outline-container-sec-13" class="outline-2">
<h2 id="sec-13"><span class="section-number-2">13</span> Esempi da scaricare</h2>
<div class="outline-text-2" id="text-13">
<p>
Qui sotto trovate il collegamento ad un archivio ZIP in cui ho inserito il sorgente ed il risultato finale in LaTeX e i documenti collegati utilizzati per il test.
</p>

<p>
Il documento è un <i>modello di atto ipertestuale</i> redatto con le tecniche già descritte nel mio precedente articolo menzionato in premessa ed implementato, in questo articolo, con i collegamenti ipertestuali esterni.
</p>

<p>
Nell'immagine seguente ho evidenziato un  <i>fac-simile</i> della fase di apertura dello ZIP <i>online</i> con l'indicazione del punto in cui si trova l'icona per il <i>download</i>. Lo ZIP è <i>hostato</i> su <i>Google Drive</i> ed è liberamente accessibile e scaricabile.
</p>


<div id="fig:latex_sorgente_finale" class="figure">
<p><img src="https://2.bp.blogspot.com/-Xx9cQDSiyy4/W38bjd4wr4I/AAAAAAAAUHE/Tk9_n2KuT00K5zEx6Ku1ZcfFCgjhrU_vgCLcBGAs/s1600/Spazio+di+lavoro+1_001.png" alt="Spazio+di+lavoro+1_001.png" width="80%" />
</p>
<p><span class="figure-number">Figura 13:</span> Indicazioni per scaricare lo ZIP</p>
</div>



<p>
<b>Ecco il collegamento allo <a href="https://drive.google.com/file/d/1b6ndz5WdtKYq0OfI5JxiM_f1hmqe8bX1/view?usp=sharing">ZIP con materiale in LaTeX</a>.</b>
</p>

<p>
Vi ringrazio per l'attenzione.
</p>

<p>
Avv. Franco Pasut
</p>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="author">Autore: Avv. Franco Pasut, Novara</p>
<p class="date">Created: 2018-08-28 mar 14:38</p>
<p class="creator"><a href="http://www.gnu.org/software/emacs/">Emacs</a> 25.1.1 (<a href="http://orgmode.org">Org</a> mode 8.2.10)</p>
</div>
</body>
</html>
