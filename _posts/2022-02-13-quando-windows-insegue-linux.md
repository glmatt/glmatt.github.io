---
layout: post
title: "Quando Windows insegue Linux"
categories: vacanze
tags: [computer, windows, linux, microsoft, nerd]
---
![Programma di installazione app MS](/assets/images/ms-app-package.png "Programma di installazione app MS")

Dopo anni di **Windows** (e tante imprecazioni) passai con sollievo e soddisfazione (e qualche grattacapo) a Linux (nello specifico **Linux Mint**) come sistema operativo principale sul mio portatile aziendale.
Non nascondo i problemi, soprattutto in termini di **compatibilità** (checché ne dicano **LibreOffice** non è interoperabile con **MS Office** né Impress è minimamente all'altezza di PowerPoint, e non venite a parlarmi di **Wine** o **CrossOver** per piacere!), ma lavorare su Linux era ed è un piacere. Tuttora sulla mia scrivania a casa c'è un vecchissimo minipc i3 su cui gira degnamente una fantastica distro Ubuntu-based chiamata Zorin OS 16 Lite (se siete un minimo curiosi fatevi un giro qui: [qui](https://zorin.com/os/ "Vai al sito ufficiale di Zorin OS")) che uso per i download e altre cosette.

Sta di fatto che il [bug #1](https://bugs.launchpad.net/ubuntu/+bug/1) di Mark Shuttleworth è ormai maggiorenne e non è ancora stato risolto e probabilmente mai lo sarà: Windows continuerà a girare sui pc della maggior parte delle persone nonostante l'evidente superiorità (e minore diffusione) di **macOS** (mio parere, pensatela come vi pare), la flebile concorrenza di **ChromeOS** e qualche bella iniziativa in ambito Linux appunto.

Ma in questi ultimi anni abbiamo assistito a tanti avvicinamenti di Microsoft verso il mondo dell'open source, a partire da **Windows Subsystem for Linux** per passare all'acquisizione da parte dell'azienda di Seattle di **GitHub** (di cui ormai sono innamorato e dipendente, come potete vedere dal dominio del blog che state leggendo).

Una delle figate di **Linux** è sempre stata la possibilità di aggiornare l'elenco dei pacchetti installati sulla macchina con un semplice

```
apt-get update
```

Bene, ora è possibile fare qualcosa del genere anche su Windows con un bel

```
winget upgrade
```

dopo aver installato il tool.

Trovate tutto qui:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Did you know that you can mass upgrade a lot of Windows 10/11 3rd party software with a free tool from Microsoft? It&#39;s like Linux&#39;s &quot;apt&quot; or &quot;yum&quot; ... Patching some of your vulnerable software is now free and easy, as I&#39;ll show you here 1/5 <a href="https://t.co/qHdLhefx5c">pic.twitter.com/qHdLhefx5c</a></p>&mdash; Lars Karlslund (@lkarlslund) <a href="https://twitter.com/lkarlslund/status/1479809034836402183?ref_src=twsrc%5Etfw">January 8, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Grazie al mitico Francesco Ronchi per la segnalazione.
Se vi va di seguire le sue incursioni mai banali e sempre interessanti lo trovate anche [qui](https://t.me/francescoron "Francesco Ronchi - things.")