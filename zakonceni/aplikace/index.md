---
layout: page
title:  "Požadavky na závěrečnou webovou aplikaci"
---

# Webová aplikace v JavaScriptu

Pro úspěšné splnění požadavku je potřeba vytvořit webovou aplikaci
napsanou čistě v JavaScriptu:

* Aplikace bude pokud možno vhodným způsobem využívat AJAX.

* Aplikace poběží na serveru přístupném ze sítě Internet a zároveň
  odevzdáváte zdrojové soubory celé aplikace. Pro samotné umístění aplikace lze využít školení server eso.vse.cz
  nebo jakýkoliv jiný.

* Aplikaci je nutné *obhájit před cvičícím* na termínu dle přihlášení
  v systému InSIS. Při obhajobě musíte mít možnost provádět v aplikaci změny.

* Zadání aplikace vám dopředu musí schválit cvičící -- konkrétní
  způsob schválení zadání vám sdělí cvičící (email/osobní/ISIS).

* Stačí, když aplikace bude fungovat v nejnovějších prohlížečích.

* Při psaní aplikace si můžete práci usnadnit pomocí existujících
  JavaScriptových knihoven/frameworků. Doporučujeme použití jQuery, které jsme probírali na cvičeních.
  
* V případech, kdy to bude vhodné, bude aplikace ctít obvyklé webové
  zvyklosti -- například funkční historie prohlížeče či uchovávání
  stavu v adrese URL.

## Příklady zadání aplikací

Pro vaši práci si musíte sami vymyslet zadání, které vám schválí
cvičící. Níže se pro inspiraci můžete podívat, jaké druhy aplikací lze
psát.

* Napište aplikaci pro plánování výletů. Aplikace zobrazí mapu, do ní
  půjde přidávat vlastní body a k nim zapisovat poznámky. Poznámky se
  uloží do uložiště prohlížeče (např. local storage) nebo na nějaké cloudové úložiště jako
  Google Drive.

* Napište aplikaci, která umožní snadné odesílání příspěvků do
  několika sociálních sítí najednou.

* Napište aplikaci pro zobrazování příspěvků ze sociálních
  sítí. Nabízí se mnoho variant -- například nějaké zajímavé zobrazení
  příspěvků od přátel, zobrazování příspěvků s určitým #hastagem s filtrováním přímo v aplikaci atp. Vhodná je např. možnost uložit si v prohlížeči oblíbené hashtagy, podle kterých poté příspěvky filtrujete. Kromě běžných sociálních sítí může být alte

* Napište aplikaci, která bude sloužit jako rozhraní pro práci s
  nějakou databází a bude nabízet základní operace jako vkládání,
  prohlížení, mazání a úpravu dat. Z databází se samozřejmě nebude
  komunikovat napřímo, ale pomocí existujícího REST API.

* Napište aplikace, která vám umožní v off-line režimu psát emaily a
  po připojení k Internetu je automaticky odešle (javascript sám maily posílat neumí, najděte si nějaké vhodné API).
  
* Napište aplikaci, která umožní uživateli nahrát do prohlížeče trasu
  uloženou ve formátu GPX a následni ji vykreslete na mapovém
  podkladu. Umožněte obvyklé operace jako posun a zoomování mapy,
  spočítání délky trasy, vykreslení výškového profilu, atd.  (Pozor, nestačí jen zobrazení GPX zavoláním jedné funkce nad API mapy.cz!)

* Napište aplikaci pro management úkolů s doplňováním poznámek k úkolům, jejich filtrováním atp. Fajn by byla integrace např. s google kalendářem.  

* Napište aplikaci na učení se otázek na odpovědi v testu - sady otázek jsou uložené na serveru, pro jejich stažení je po vybrání konkrétní sady použit AJAX. Aplikace si např. v local storage pamatuje, které otázky zodpověděl uživatel chybně a umožní mu se k nim vrátit.

* Napište hru běžící v prohlížeči. Jednoduššími příklady mohou být např. kvízová aplikace, která si sadu otázek stáhne ze serveru a buď na server, nebo do paměti prohlížeče si ukládá výsledky a statistiky.

* Napište hru běžící za využití nějakého javascriptového herního frameworku (např. něco á la flappy bird), ideálně s pamatováním si nejlepšího skóre.

* Napište generátor grafických oznámení atp. (uživatel nahraje fotku či zadá údaje a vaše aplikace vygeneruje např. přání k Vánocům) s možností jejich následného sdílení přes API vybrané sociální sítě.

## Příklady veřejně dostupných API, která lze využít ve vašich aplikacích

* [Google Drive REST API](https://developers.google.com/drive/web/about-sdk)
* [Amazon S3 REST API](http://docs.aws.amazon.com/AmazonS3/latest/API/APIRest.html)
* [Flickr API](https://www.flickr.com/services/api/)
* [Twitter REST API](https://dev.twitter.com/rest/public)
* [Office 365 API](https://msdn.microsoft.com/en-us/office/office365/howto/rest-api-overview#sectionlanguagesides)
* [Přehled dalších API](https://www.programmableweb.com/apis/directory)
* [A ještě jeden přehled API](https://any-api.com/)


Upozorňujeme, že na možnosti daného API byste se měli podívat ještě před odevzdáním zadání své javascriptové aplikace!
