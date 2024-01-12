Verze šablony 1.1

Šablona je vždy k dispozici na <https://github.com/egdilna/sablony/blob/main/architektonicka_dokumentace/sablona-analyza-dopadu-PDS.md>
https://github.com/egdilna/sablony/blob/main/strategicka_dokumentace/sablona-analyza-dopadu-PDS.md




# 1. Úvod
Toto je analytický podklad pro XXX řešící souhrnně oblasti důležité pro naplnění legislativy k eGovernmentu a to zvlášť k právu na digitální služby (tedy zejména zákon 12/2020 a související součásti IKČR a NAP).

Tento dokument uceleně představuje celou problematiku a její souvislosti a především v rámci našeho OVM stanovuje, co se musí udělat a jak se to má obecně udělat, abychom mohli veškeré povinnosti plnit. Přitom se striktně neomezuje jen na PDS, protože aby bylo možno PDS správně implementovat, je třeba dořešit spoustu již existujících EG oblastí, které s PDS nabývají velké důležitosti.

* Verze analýzy: xxx
* Datum aktualizace: xxx
* Stav realizace: xxx
* Zodpovědný zaměstnanec: xxx

# 2. Právo na digitální služby

> Toto je společná obecná kapitola pro všechny analýzy, není třeba ji upravovat.
> 

## 2.1 Co je právo na digitální služby a jak to zapadá do celkového EG rámce

[Právo na digitální služby](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20digit%C3%A1ln%C3%AD%20slu%C5%BEby) je jeden ze základních mechanismů digitální veřejné správy. Umožňuje uplatnit právo na plně digitální interakci klienta s veřejnou správou tam, kde to dává smysl.

Podrobné vysvětlení všech konceptů a návazností je uvedeno v příloze. Pro více obecných informací doporučujeme odkazy [stránka Právo na digitální služby](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20digit%C3%A1ln%C3%AD%20slu%C5%BEby), [prezentace Právo na digitální služby v úřadu](https://www.egovedu.cz/prezentace/pds-v-uradu) a [stránka Implementace povinností dle zákona o právu na digitální služby z NAEG](https://archi.gov.cz/znalostni_baze:implementace_zopds?s\[\]=pr%C3%A1vo%2A&s\[\]=na%2A&s\[\]=digit%C3%A1ln%C3%AD%2A&s\[\]=slu%C5%BEby%2A).

Základními koncepty [PDS](https://architektovani.tiddlyhost.com/#PDS) jsou:

- Stát je veřejná správa, veřejná správa poskytuje služby.
- Existuje jedno místo se seznamem všech služeb veřejné správy a s jejich popisy a podrobnostmi, tím místem je Katalog služeb a zejména [nástroj [Veřejná část Katalogu služeb](https://architektovani.tiddlyhost.com/#Ve%C5%99ejn%C3%A1%20%C4%8D%C3%A1st%20Katalogu%20slu%C5%BEeb) veřejné správy](<https://portal.gov.cz/sluzby-verejne-spravy/>](https://portal.gov.cz/sluzby-verejne-spravy/))
- Je legislativně zakotveno, jak má veřejná správa služby poskytovat (to řeší [zákon 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kon%2012%2F2020)) a co k tomu potřebuje (to řeší [zákon 365/2000](https://architektovani.tiddlyhost.com/#z%C3%A1kon%20365%2F2000) a 111/2009 a další) a jak konkrétně se má co dělat (to řeší agendové zákony)
- Veřejná správa poskytuje klientovi služby, klient činí úkony. U všech služeb a úkonů, pokud tomu nebrání opravdu významné důvody, jsou poskytovány také digitálně.
- U služeb a úkonů fyzických osob není digitální poskytování jedinou cestou.
- Komunikace a interakce klienta s veřejnou správou je napříč všemi úřady jednotná.
- Veřejná správa si sama zajistí obstarání jakýchkoliv dat, která jsou již někde evidována a neobtěžuje tím klienta

[PDS](https://architektovani.tiddlyhost.com/#PDS) je mnohdy mylně bráno jen jako implementace některých povinností z jediného zákona ([zákon 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kon%2012%2F2020) o [PDS](https://architektovani.tiddlyhost.com/#PDS)), avšak jedná se o komplexní oblast, tedy bez plnění souvisejících povinností z digitálních zákonů, se nedá [PDS](https://architektovani.tiddlyhost.com/#PDS) správně implementovat.

[Právo na digitální služby](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20digit%C3%A1ln%C3%AD%20slu%C5%BEby) je tak trochu souběhem respektive syntézou výsledku již existujících principů / produktů eGovernmentu.

## 2.2 Legislativní rámec služeb EG

Pro digitalizaci a eGovernment jsou důležité následující zákony:

**Zákon č. 12/2020 Sb., o právu na digitální služby** se někdy označuje také jako [Digitální Ústava](https://architektovani.tiddlyhost.com/#Digit%C3%A1ln%C3%AD%20%C3%9Astava), jedná se o předpis jež zejména definuje několik základních práv klienta a povinnost veřejné správy tato práva umožnit a dále upravuje některé další EG zákony, aby taková práva měla jasný dopad do fungování úřadu. Jde o nejvýznamnější EG předpis z pohledu klienta. : https://www.zakonyprolidi.cz/cs/2020-12

**Zákon č. 111/2009 Sb., o základních registrech** zakládá jednotlivé základní registry a k tomu definuje propojený datový fond jako povinnosti sdílení, využívání a poskytování údajů ze základních registrů a agendových informačních systémů, dále zavádí podrobnosti k referenčnímu rozhraní a stanovuje povinnosti jednotlivým aktérům. : https://www.zakonyprolidi.cz/cs/2009-111

**Zákon č. 365/2000 Sb., o informačních systémech veřejné správy** upravuje oblast všech regulovaných informačních systémů v úřadech, oblast informačních koncepcí a dlouhodobého řízení a také povinnosti jednotlivých úřadů v rámci informačních činností a informačních systémů. : https://www.zakonyprolidi.cz/cs/2000-365

**Zákon č. 181/2014 Sb., o kybernetické bezpečnosti** upravuje oblast kybernetické bezpečnosti jak pro veřejnou správu včetně krytické infrastruktury, ale i pro soukromý sektor. Udává povinnosti povinným subjektům a udává práva a povinnosti NÚKIBu v této oblasti. : https://www.zakonyprolidi.cz/cs/2014-181

**Zákon č. 250/2017 Sb., o elektronické identifikaci** řeší oblast EID tedy elektronické identifikace a to s využitím národního bodu NIA a zejména povinnosti poskytovatelů služeb povinně využívajících EID a povinnosti vydavatelů prostředků pro identifikaci. : https://www.zakonyprolidi.cz/cs/2017-250

**Zákon č. 297/2016 Sb., o službách vytvářejících důvěru pro elektronické transakce** je transpozicí části EIDAS a řeší problematiku důvěryhodných služeb a důvěryhodnosti dokumentů a související povinnosti. : https://www.zakonyprolidi.cz/cs/2016-297

**Zákon č. 300/2008 Sb., o elektronických úkonech a autorizované konverzi dokumentů** je označován také jako zákon o datových schránkách. Definuje datové schránky a povinnosti jejich využívání pro zaručenou elektronickou komunikaci zejména uvnitř veřejné správy a s veřejnou správou, stanovuje práva držitelů a také upravuje oblast autorizované konverze dokumentů z moci úřední i na žádost. : https://www.zakonyprolidi.cz/cs/2008-300

**Zákon č. 499/2004 Sb., o archivnictví a spisové službě** je hlavním předpisem upravujícím zejména výkon spisové služby jako povinnou správu dokumentů u veřejnoprávních původců a úřadů, označuje se také někdy jako zákon o spisové službě. Definuje povinnosti a základy procesů, povinnosti k nim pak stanovuje [vyhláška 259/2012](https://architektovani.tiddlyhost.com/#vyhl%C3%A1%C5%A1ka%20259%2F2012) a NSESSS. Kromě toho zákon upravuje i oblast archivů a jejich činnosti. : https://www.zakonyprolidi.cz/cs/2004-499

**Zákon č. 106/1999 Sb., o svobodném přístupu k informacím** upravuje poskytování informací na žádost a především publikaci otevřených dat a související povinnosti. : https://www.zakonyprolidi.cz/cs/1999-106

Co obsahují jednotlivé zákony, obsahuje kupříkladu [dokument Podrobný popis vybraných EG předpisů](http://metodiky.egdilna.cz/metodiky/legislativa/popis-eg-zakonu)

Co se týče výhradně zákona o právu na digitální služby, existuje [dokument Rozbor celého zákona 12/2020 PDS](http://metodiky.egdilna.cz/metodiky/legislativa/rozbor-pds)

Samotný zákon o [PDS](https://architektovani.tiddlyhost.com/#PDS) pak především udává jednotlivá práva, stanovuje povinnosti OVM tyto práva klienta (uživatele služby) naplňovat a dále zahrnuje další oblasti, jež ze samotným poskytováním služeb přímo nesouvisí.

Takzvaná [Digitální Ústava](https://architektovani.tiddlyhost.com/#Digit%C3%A1ln%C3%AD%20%C3%9Astava) ([zákon 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kon%2012%2F2020)) definuje několik základních práv klienta:

- [Právo činit digitální úkon](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20%C4%8Dinit%20digit%C3%A1ln%C3%AD%20%C3%BAkon)
- [Právo na digitální službu](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20digit%C3%A1ln%C3%AD%20slu%C5%BEbu)
- [Právo na elektronickou identifikaci a autentizaci](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20elektronickou%20identifikaci%20a%20autentizaci)
- [Právo na informace v souvislosti s poskytováním digitálních služeb](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20informace%20v%20souvislosti%20s%20poskytov%C3%A1n%C3%ADm%20digit%C3%A1ln%C3%ADch%20slu%C5%BEeb)
- [Právo na nahrazení úředně ověřeného podpisu nebo uznávaného elektronického podpisu](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20nahrazen%C3%AD%20%C3%BA%C5%99edn%C4%9B%20ov%C4%9B%C5%99en%C3%A9ho%20podpisu%20nebo%20uzn%C3%A1van%C3%A9ho%20elektronick%C3%A9ho%20podpisu)
- [Právo na osvědčení digitálního úkonu](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20osv%C4%9Bd%C4%8Den%C3%AD%20digit%C3%A1ln%C3%ADho%20%C3%BAkonu)
- [Právo na prokázání právní skutečnosti](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20prok%C3%A1z%C3%A1n%C3%AD%20pr%C3%A1vn%C3%AD%20skute%C4%8Dnosti)
- [Právo na technologickou neutralitu](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20technologickou%20neutralitu)
- [Právo na využívání údajů](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20vyu%C5%BE%C3%ADv%C3%A1n%C3%AD%20%C3%BAdaj%C5%AF)
- [Právo na zápis kontaktního údaje](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20z%C3%A1pis%20kontaktn%C3%ADho%20%C3%BAdaje)
- [Právo na zápis právní skutečnosti](https://architektovani.tiddlyhost.com/#Pr%C3%A1vo%20na%20z%C3%A1pis%20pr%C3%A1vn%C3%AD%20skute%C4%8Dnosti)

## 2.3 Plnění povinností týkajících se práva na digitální služby

Splnit si vše kolem práva na digitání služby je komplexní věc. Nejde jen plnit samotné [PDS](https://architektovani.tiddlyhost.com/#PDS), jde o plnění veškerých povinností digitalizace a eGovernmentu. Úřad bude v souladu s [PDS](https://architektovani.tiddlyhost.com/#PDS) a bude schopen jej plnit tedy jen tehdy, kldyž bude plnit veškeré digitální povinnosti. Příkladem je třeba elektronická identifikace, se kterou [PDS](https://architektovani.tiddlyhost.com/#PDS) počítá a kde existuje základní povinnost pro portálová řešení využívat pouze zaručenou elektronickou identitu klienta prostřednictvím NIA a žádné jiné řešení. Toto je typická digitální povinnost (konkrétně podle [zákona 250/2017](https://architektovani.tiddlyhost.com/#z%C3%A1kona%20250%2F2017)) bez níž [PDS](https://architektovani.tiddlyhost.com/#PDS) nebude fungovat a nebo nebude správné. Jen se zaručenou elektronickou identitou přes NIA totiž bude OVM plnit povinnost nevyžadovat elektronický podpis u podání činěných prostřednictvím portálu.

Plnění povinností se musí odrazit na těchto úrovních:

- Strategická úroveň řízení
    - Analýza dopadů (tento dokument) jako soupis stavu a potřeb změn
    - Informační koncepce úřadu, do které se [PDS](https://architektovani.tiddlyhost.com/#PDS) musí promítnout
    - Realizace potřeb záměry v IK a projekty
    - Implementace [PDS](https://architektovani.tiddlyhost.com/#PDS) řízená jako projekt celého úřadu
- Architektonická úroveň
    - Naplnění principů a cílů
    - Stanovení základních požadavků na úrovni architektury
    - Přehled konkrétních potřeb změn a jejich sledování
- Procesní a metodika a úroveň
    - Úpravy procesů v úřadu, aby byly splněny mechanismy [PDS](https://architektovani.tiddlyhost.com/#PDS) a práva klienta
    - Úprava formulářů, dokumentů, aplikací pro klienty, popisů služeb a procesů
    - Úprava metodik a provozních dokumentů, dle kterých se vykonává veřejná správa
    - Stanovení zodpovědností a realizace kontroly dodržování povinností a procesů
    - [PDS](https://architektovani.tiddlyhost.com/#PDS) do řízení kvality úřadu a kvality služeb
    - Metriky služeb a transakčních událostí
- Aplikační a technologická úroveň
    - Úpravy agendových informačních systémů a provozních systémů v úřadu
    - Portálové řešení pro digitální služby a úkony
    - Propojení s Portálem občana, Portálem veřejné správy a dalšími centrálními EG službami
    - Zajištění integrace na další vnitřní systémy v úřadu, jako je spisová služba, ekonomika, evidence subjektů apod.)

Pro sledování plnění povinností existuje metoda Assessment povinností, podklady lze získat i v Mapě EG povinností.

## 2.4 Role a postavení jednotlivých OVM a jejich součinnost

Pro naplnění práv klienta je třeba spolupráce celé veřejné správy. Jelikož naprostá většina údajů potřebných pro výkon agendy již ve veřejné správě existuje, je nezbytné brát vážně principy sdílení údajů a tzv. Propojeného datového fondu. Následující role jsou pro to klíčové a je nutné vždy u každé situace si dobře uvědomit, v jakých rolích se OVM nachází:

- Klientské role (subjektů)
	- Uživatel sdílení údajů : Subjekt, o kterém jsou sdílené údaje podle [PDS](https://architektovani.tiddlyhost.com/#PDS) a [ZZR](https://architektovani.tiddlyhost.com/#ZZR).
	- Subjekt údajů : Konkrétní [Subjekt] v jakémkoliv postavení, o němž se vedou či se ho týkají vedené údaje, ať už jde o údaje vedené v informačních systémech veřejné správy, nebo v dokumentech či evidencích. Pro speciální případy (kupříkladu GDPR) se jedná o zvláštní roli subjektu.
	- Uživatel digitální služby : Klientský subjekt, který je uživatelem digitální služby podle [PDS](https://architektovani.tiddlyhost.com/#PDS).
	- Agendový subjekt : Synonymum pro [Klientský subjekt] v dané jedné agendě (určuje [zákon 111/2009](https://architektovani.tiddlyhost.com/#z%C3%A1kon%20111%2F2009))
- Role orgánu veřejné moci
	- Ohlašovatel agendy Orgán veřejné moci, který je ohlašovatelem agendy v Registru práv a povinností a zodpovídá za údaje o agendě. Role OVM
	- OVM působící v agendě : Orgán veřejné moci, který má v Registru práv a povinností u agendy vyznačenou působnost, nebo který působí v dané agendě. Role OVM
	- Poskytovatel digitální služby : Orgán veřejné moci, který poskytuje digitální službu podle [zákona 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kona%2012%2F2020) o právu na digitální služby a jež je pro poskytování služby povinen podle [zákona 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kona%2012%2F2020) a ohlášení agendy v Registru práv a povinností a Katalogu služeb veřejné správy. Role OVM
	- Zodpovědný za službu veřejné správy : OVM jež je v Katalogu služeb veřejné správy vyznačen jako zodpovídá za službu u služby veřejné správy. Mimo jiné zodpovídá i za to, že informace v KSVS jsou úplné a aktuální a je jejich editorem i do Registru práv a povinností, to se týká veškerých podrobností o službě. Většinou jde o ohlašovatele dané agendy, ale ten může pro jednotlivé služby určit jiné OVM. Vůči němu se pak realizuje reklamace Role OVM
	- Poskytovatel služby a příjemce úkonu : Orgán veřejné moci, který na základě zákonné povinnosti a podle ohlášení poskytovaných služeb v Katalogu služeb veřejné správy a Registru práv a povinností, poskytuje službu veřejné správy. Je jedno, zda se jedná o digitální službu podle [zákona 12/2020](https://architektovani.tiddlyhost.com/#z%C3%A1kona%2012%2F2020), nebo službu ve smyslu [zákona 111/2009](https://architektovani.tiddlyhost.com/#z%C3%A1kona%20111%2F2009).
	- Zodpovědný za elektronický formulář : OVM jež dle zákona a příslušné agendy připravuje elektronické formuláře a dle povinností stanovených v zákoně 111/2009 a 12/2020 jej předá [DIA](https://architektovani.tiddlyhost.com/#DIA) a zajistí jeho fungování jak v lokálním portálu, tak ale i v rámci Portálu veřejné správy / Portálu občana. Role OVM
	- Poskytovatel služeb s využitím ZEID : Ten, kdo umožňuje prokázání totožnosti, které vyžaduje právní předpis nebo výkon působnosti, s využitím elektronické identifikace Role OVM
	- Správce informačního systému Správce IS zejména podle [zákona o ISVS](https://architektovani.tiddlyhost.com/#z%C3%A1kona%20o%20ISVS) Role OVM
	- Publikátor sdílení údajů : OVM, který poskytuje sdílené údaje podle [PDS](https://architektovani.tiddlyhost.com/#PDS) a [ZZR](https://architektovani.tiddlyhost.com/#ZZR). Role OVM
	- Čtenář sdílení údajů OVM, který v rámci sdílení údajů tyto údaje čte a využívá ke své činnosti. Role OVM
	- Editor údajů v agendovém informačním systému Editor ISVS, respektive editor údajů v ISVS Role OVM
	- Uživatel údajů z informačního systému Orgán, který prostřednictvím služeb užívá údaje z IS. Role OVM

Základní schéma spolupráce je následující:

- Ohlašovatel agendy si splní veškeré povinnosti související s aktuálností a úplností agendy v Registru práv a povinností. Mimo jiné správně ohlásí služby do Katalogu služeb veřejné správy.
- Poskytovatel digitální služby je orgánem veřejné moci působící v dané agendě a také si doplní a zkontroluje veškeré údaje o sobě a o svých agendách a službách.
- Pokud je ohlašovatel zároveň zodpovědný za službu a formuláře, zajistí centrální prostředky pro danou službu (formuláře, agendový porál, propojení na Portál občana apod.) a pokud ne, zajistí maximum možného pro OVM poskytující služby svými prostředky.

Součinnost ohlašovatelů, zodpovědných OVM a OVM poskytovatelů je tedy nezbytná a to na procesní úrovni i na technické úrovni (kterou řeší propojený datový fond).

## 2.5 Oblasti a funkční celky potřebné k naplnění [PDS](https://architektovani.tiddlyhost.com/#PDS)

Aby právo na digitální služby fungovalo v úřadě tak jak má, je potřeba se zabývat těmito oblastmi:

- Řízení služeb a zodpovědností, Poskytování ohlášených služeb, Poskytování našich služeb
- Životní události a služby a úkony a postupy, Digitální úkony, Elektronické funkční formuláře, Informace o poskytnutých službách a úkonech
- Klienti v rolích, Elektronická identifikace a důvěryhodnost úkonu
- Data a údaje potřebné pro funkční služby a jejich zdroj, Zpřístupnění údajů a výpisy, Propojený datový fond a sdílení údajů v AISech, Odkazování klientem na cizí údaje a zápis skutečnosti v [RPP](https://architektovani.tiddlyhost.com/#RPP), Zapsání skutečnosti do [RPP](https://architektovani.tiddlyhost.com/#RPP) na žádost, Reklamace
- Logování


# 3. Dopady na úřad
V této kapitole se strukturovaně uvádí co je třeba pro implementaci PDS na úrovni celého úřadu.

## 3.1 Zhodnocení obecné připravenosti úřadu
OVM podrobně prostudovalo legislativní rámec a to zejména [předpis 12/2020 Sb. Zákon o právu na digitální služby](https://www.zakonyprolidi.cz/cs/2020-12), [předpis 111/2009 Sb. Zákon o základních registrech](https://www.zakonyprolidi.cz/cs/2009-111), [předpis 365/2000 Sb. Zákon o informačních systémech veřejné správy](https://www.zakonyprolidi.cz/cs/2000-365), [předpis 250/2017 Sb. Zákon o elektronické identifikaci](https://www.zakonyprolidi.cz/cs/2017-250), [předpis 297/2016 Sb. Zákon o službách vytvářejících důvěru pro elektronické transakce](Https://www.zakonyprolidi.cz/cs/2016-297), [předpis 499/2004 Sb. Zákon o archivnictví a spisové službě](https://www.zakonyprolidi.cz/cs/2004-499), [předpis 300/2008 Sb. Zákon o elektronických úkonech a autorizované konverzi dokumentů](https://www.zakonyprolidi.cz/cs/2008-300) a [předpis 99/2019 Sb. Zákon o přístupnosti internetových stránek a mobilních aplikací a o změně zákona č. 365/2000 Sb., o ...](https://www.zakonyprolidi.cz/cs/2019-99). Klíčové jsou i předpisy tzv. nového legislativního rámce EG a to novely [předpis 261/2021 Sb. Zákon, kterým se mění některé zákony v souvislosti s další elektronizací postupů orgánů veřejné moci](https://www.zakonyprolidi.cz/cs/2021-261) a [předpis 471/2022 Sb. Zákon, kterým se mění zákon č. 12/2020 Sb., o právu na digitální služby a o změně některých zákonů, (Transformační zákon)](https://www.zakonyprolidi.cz/cs/2022-471).

V rámci platné informační koncepce máme v souvislosti s PDS následující záměry: xxx

Celkově lze zhodnotit připravenost na PDS takto:

* xxx




## 3.2 Stanovení základních zodpovědností

* Digitálním zmocněncem OVM je xxx
* Správcem služeb je digitální zmocněnec pro úroveň celého úřadu.
* Administrátory s přístupem do AIS působnostního jsou xxx
* Hlavním architektem je xxx, na architektuře se dále podílejí xxx
* Zodpovědným za legislativní kompatibilitu jsou xxx
* Máme stanovené role zodpovědných útvarů jako věcných správců služeb po jednotlivých oblastech: xxx
* Věcnými a technickými správci pro klíčové IS jsou: xxx




## 3.3 Jak budeme naplňovat jednotlivá práva či oblasti
Shrnující informace pro jednotlivé oblasti PDS:

### Poskytování ohlášených služeb
### Poskytování našich služeb
### Klienti v rolích
### Digitální úkony 
### Elektronická identifikace a důvěryhodnost úkonu
### Zpřístupnění údajů a výpisy 
### Životní události a služby a úkony a postupy 
### Data a údaje potřebné pro funkční služby a jejich zdroj
### Propojený datový fond a sdílení údajů v AISech 
### Odkazování klientem na cizí údaje a zápis skutečnosti v RPP
### Zapsání skutečnosti do RPP na žádost
### Elektronické funkční formuláře
### Reklamace
### Logování
### Informace o poskytnutých službách a úkonech
### Řízení služeb a zodpovědností
## 3.4 Součinnost útvarů v úřadu
# 4. Potřeby úprav ICT nástrojů
Co se kde musí obecně udělat?

## 4.1 Informační koncepce úřadu

Aktuální informační koncepce úřadu, jež je v souladu s požadavky na IK je z roku xxx, aktualizaci provedeme xxx.

Do IK je třeba promítnout následující požadavky a principy ke splnění PDS:

* xxx

Do IK je třeba zapsat následující záměry:

* xxx


## 4.2 Katalog služeb úřadu
## 4.3 Portál pro služby a úkony
## 4.4 Potřeby úprav informačních systémů

U následujících IS je třeba učinit tyto změny:

* Informační systém: xxx
	1. xxx




