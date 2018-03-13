+++
title = "Dagboek"
description = "about this site"
date = "2014-09-27"
slug = "dagboek"
+++

## Redactionele planning met Trello en Zapier


Zolang ik met redactionele teams heb gewerkt, is een inhoudspijplijn een probleem geweest. Het kennen van de staat van een verhaal, de context van degenen die eromheen zijn en wie wat heeft gedaan, wanneer, is van vitaal belang voor het beheer van een doorvoersnelheid. Over het algemeen komt dit tot uiting in een drukke, lawaaierige, fysieke omgeving. Maar hoe meer afstand een team wordt, des te uitdagender het is om te communiceren over de staat van verhalen.
{{% side-sm-large   %}} 
{{% sidebar date="February 9th, 2018" %}} Opgeslagen in: [ontwerp](ontwerp)  [hoofdartikel](hoofdartikel) [zapier](zapier) [automatisering](automatisering)
{{% /sidebar %}}{{% large-col %}}Toen ik toetrad [EMBL](www.embl.org)  een paar maanden geleden was dit een probleem dat we hadden. De contentstatus werd wekelijks gedaan, maar een voortdurend beschikbaar overzicht door het hele team was dat niet. Noch was er een hulpmiddel of proces om verhalen rond te duwen. Zoals ik al zei, mijn ervaring is dat dit niet uniek is voor EMBL. Bijna elke redactie waar ik mee heb gewerkt worstelt hiermee.

[Dan](https://twitter.com/thenoyes) en ik kwamen bij elkaar en werkten aan een proces dat paste bij het bestaande team en de tools. Het team hier gebruikt Trello uitgebreid voor planning, dus we zijn daar begonnen.

##  Het enige bord om ze allemaal te regeren
Het was belangrijk dat we de bestaande processen met Trello niet verstoorden. Het team gebruikt Trello op verschillende, interessante manieren om samen te werken en hun inhoud te beheren; van ideeën tot uiteindelijke kopie. We moesten zo goed mogelijk integreren. Dit is waar we het over eens zijn:
### 1. Een pre-productie Trello-bord
Zodra een verhaal klaar is om in de workflow te gaan. Dit betekent dat het is afgesproken, gepland, toegewezen aan een prioriteit enz. En vervolgens wordt toegevoegd aan het pre-productie Trello-bord. Dit bord is geordend op verhaaltype: functies, updates, persberichten. Zodra een verhaal compleet is en klaar om te publiceren, wordt het verplaatst naar een kolom 'Verplaatsen naar productie'. <a href="www.Zapier.com">Zapier</a> dan kopieert de kaart, met alles erin, naar het Productschap. Zodra dat is gebeurd, wordt het naar een archieflijst verplaatst.
    
  1.  Find the Pre-production Trello board
  2.  Find a list on that board called 'Move to Production'
  3.  Find cards moved into that list (this is the trigger to run the whole zap)
  4.  Get information about the card and move it to Production. (In fact, here, I didn't move it but copied it. I wanted a safe-guard in the system so that if something went wrong, there would be a backup)
  5.  Once it's moved, confirm by then moving the card into the archive list.
  6.  Once all that's done, check the card has actually moved.
  7.  Then post to Slack and let everyone know.
{{% /large-col %}}{{% /side-sm-large %}}