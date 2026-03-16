# Návrh struktury bezpečnostní dokumentace IS

# Bezpečnostní dokumentace informačního systému [Název IS]

## 1. Identifikace systému a řízení rizik

### 1.1 Identifikace a popis systému (§ 5 odst. 3, § 7 písm. c) a f) vyhlášky)

- Název informačního systému a jeho jednoznačný identifikátor
- Účel a popis poskytované služby/funkcí systému
- Vlastník / garant aktiva (jméno, role, organizační zařazení)
- Provozovatel systému a hlavní administrátoři
- Vazba na regulovanou službu a primární aktiva
- Stručný popis architektury (aplikační vrstvy, databáze, integrace)

### 1.2 Klasifikace aktiv (§ 7, příloha č. 1 vyhlášky)

- Zařazení IS jako podpůrného aktiva a jeho vazby na primární aktiva
- Hodnocení z hlediska důvěrnosti, integrity a dostupnosti — zařazení do úrovní dle přílohy č. 1
- Seznam podpůrných aktiv IS (servery, databáze, middleware, síťové prvky, úložiště…)
- Pravidla ochrany dle stanovené úrovně:
  - Přípustné způsoby používání aktiv
  - Pravidla pro manipulaci včetně elektronického sdílení a fyzického přenášení
  - Pravidla pro klasifikaci a označování informací
  - Pravidla správy výměnných médií
  - Pravidla pro likvidaci informací, dat a technických aktiv dle přílohy č. 2

### 1.3 Hodnocení rizik specifické pro IS (§ 8, příloha č. 3 vyhlášky)

- Identifikace hrozeb a zranitelností relevantních pro IS (s ohledem na kategorie z přílohy č. 3)
- Výsledky hodnocení rizik IS (odkaz na zprávu o hodnocení rizik)
- Aplikovaná bezpečnostní opatření — odkaz na Prohlášení o aplikovatelnosti (SoA)
- Zbytková rizika a jejich akceptace
- Datum posledního hodnocení rizik a plánovaný termín příštího přezkumu

## 2. Architektura a infrastruktura

### 2.1 Síťová architektura a komunikace (§ 18 vyhlášky)

- Dokumentace topologie komunikační sítě a infrastruktury IS (síťový diagram)
- Dokumentace segmentace sítě — oddělení provozního, zálohovacího, vývojového, testovacího a administrátorského prostředí
- Pravidla řízení komunikace v rámci komunikační sítě
- Pravidla vzdáleného přístupu a vzdálené správy technických aktiv
- Povolená komunikace — pouze nezbytná pro řádné zajištění regulované služby
- Časové omezení komunikace a opětovné ověření identity po stanovené době
- Použité kryptografické protokoly pro přenos dat
- Nástroj pro ochranu integrity komunikační sítě

### 2.2 Fyzická bezpečnost (§ 17 vyhlášky)

- Umístění technických aktiv IS — fyzický bezpečnostní perimetr
- Pravidla fyzického přístupu ke komponentám IS
- Ochrana před poškozením prostředí — napájení, klimatizace, požární ochrana
- Detekce narušení fyzického perimetru
- Evidence vstupů a přístupů do fyzického bezpečnostního perimetru

### 2.3 Zajišťování dostupnosti (§ 26 vyhlášky)

- Opatření pro zajištění dostupnosti IS v souladu s hodnocením aktiv
- Zálohovací strategie — co se zálohuje, frekvence, cílové úložiště, ověřování obnovy
- Redundance a vysoká dostupnost (pokud vyžadováno úrovní aktiva)
- Monitoring dostupnosti a výkonnosti

## 3. Řízení přístupu a identit

### 3.1 Řízení přístupu (§ 13 vyhlášky)

- Přístupová politika specifická pro daný IS
- Řízení přístupu na základě skupin nebo rolí
- Matice přístupových práv a oprávnění — uživatelské a administrátorské účty, princip nejnižších oprávnění
- Identifikátory a oprávnění technických (servisních) účtů
- Bezpečnostní opatření pro řízení přístupu technických aktiv
- Pravidla pro mobilní zařízení a zařízení mimo správu organizace (vč. BYOD)
- Omezení nástrojů schopných překonat systémové nebo aplikační kontroly
- Proces přidělování a odebírání práv, pravidelné přezkoumávání
- Bezodkladné odebrání nebo změna přístupových práv při změně role nebo ukončení vztahu

### 3.2 Správa a ověřování identit (§ 19 vyhlášky)

- Způsoby autentizace uživatelů a administrátorů v IS
- Pravidla tvorby a správy hesel specifická pro IS
- Vícefaktorová autentizace — kde je vyžadována a jak je implementována
- Správa sdílených a servisních účtů — pověřené osoby, evidence manipulace, intervaly změn hesel (min. 1× za 18 měsíců)
- Evidování manipulace a pokusů o manipulaci s účty a hesly

### 3.3 Řízení přístupových práv a oprávnění (§ 20 vyhlášky)

- Popis centralizovaného nástroje pro řízení přístupových práv
- Řízení práv k jednotlivým aktivům IS
- Řízení oprávnění pro čtení, zápis a změnu oprávnění

## 4. Bezpečnost provozu

### 4.1 Aplikační bezpečnost (§ 24 vyhlášky)

- Evidence podporovanosti IS výrobcem/dodavatelem
- Proces aplikování bezpečnostních aktualizací (patch management)
- Evidence nepodporovaných komponent a náhradní bezpečnostní opatření
- Ochrana aplikací, transakcí a identifikátorů relací před neoprávněnou činností a popřením provedených činností
- Plán a výsledky skenování zranitelností — vnitřní i vnější síť, min. 1× ročně
- Plán a výsledky penetračních testů — min. 1× za 2 roky, před uvedením do provozu a při významných změnách

### 4.2 Kryptografické algoritmy (§ 25 vyhlášky)

- Přehled použitých kryptografických algoritmů v IS
- Způsob zajištění jejich aktuální odolnosti
- Správa klíčů — generování, distribuce, ukládání, výměna, zálohování, zneplatnění, likvidace

### 4.3 Detekce kybernetických bezpečnostních událostí (§ 21 vyhlášky)

- Popis nástrojů detekce pro daný IS
- Ověření a kontrola přenášených dat v rámci a mezi komunikačními sítěmi
- Ověření a kontrola dat na síťovém perimetru
- Aktivní blokování nežádoucí komunikace
- Centralizovaný nástroj s nepřetržitou ochranou před škodlivým kódem
- Detekce na základě chování technických aktiv, administrátorů a uživatelů
- Pravidelná aktualizace nástrojů včetně detekčních pravidel

### 4.4 Zaznamenávání událostí (§ 22 vyhlášky)

- Rozsah zaznamenávaných událostí:
  - Přihlašování a odhlašování vč. neúspěšných pokusů
  - Provedení a pokusy o privilegované činnosti
  - Manipulace s účty, oprávněními a právy
  - Neprovedení činností z důvodu nedostatku práv
  - Zahájení a ukončení činností technických aktiv
  - Kritická a chybová hlášení
  - Přístupy a manipulace se záznamy událostí
- Zaznamenávané atributy: datum a čas vč. časového pásma, typ činnosti, identifikace aktiva, identifikace účtu, identifikace zařízení, úspěšnost/neúspěšnost
- Ochrana logů — důvěrnost, integrita, ochrana před neoprávněným čtením a změnou
- Centralizovaný nástroj pro sběr a uchovávání záznamů
- Retenční doba: minimálně 18 měsíců
- Synchronizace jednotného času technických aktiv

### 4.5 Vyhodnocování kybernetických bezpečnostních událostí (§ 23 vyhlášky)

- Napojení na nástroj pro nepřetržité vyhodnocování (SIEM / obdobný)
- Sběr, vyhledávání a seskupování souvisejících záznamů
- Nepřetržité poskytování informací o detekovaných událostech vč. včasného varování
- Pravidelná aktualizace nastavení a pravidel pro detekci a vyhodnocování
- Využití získaných informací pro optimalizaci ISMS

## 5. Kontinuita a zvládání incidentů

### 5.1 Řízení kontinuity a obnovy (§ 15 zákona, § 26 vyhlášky)

- Analýza dopadů (BIA) specifická pro IS
- Plán kontinuity činností pro IS — definice RTO a RPO
- Plán obnovy IS
- Výsledky testování plánů kontinuity a obnovy
- Eskalace a kontaktní osoby pro krizové situace

### 5.2 Zvládání kybernetických bezpečnostních incidentů (§ 14 vyhlášky; § 15–16 zákona)

- Postupy detekce, klasifikace a eskalace incidentů v IS
- Kontaktní osoby a role pro zvládání incidentů
- Vazba na celkový proces hlášení incidentů organizace (Úřadu / Národnímu CERT)
- Postupy pro omezení dopadů, reakci a následnou obnovu
- Evidence a dokumentace incidentů

## 6. Řízení životního cyklu systému

### 6.1 Řízení změn (§ 11 vyhlášky)

- Pravidla pro evidenci a schvalování změn v IS
- Definice významných změn pro daný IS
- Vazba na opakované hodnocení rizik při významných změnách
- Testování změn před nasazením do produkčního prostředí
- Dokumentace provedených změn

### 6.2 Řízení dodavatelů IS (§ 9, příloha č. 5 vyhlášky)

- Seznam významných dodavatelů IS
- Bezpečnostní požadavky ve smlouvách (v souladu s přílohou č. 5):
  - Ustanovení o důvěrnosti, integritě a dostupnosti
  - Pravidla zákaznického auditu
  - Ustanovení o řetězení dodavatelů
  - Povinnost informovat o incidentech a změnách
  - Podmínky při ukončení smlouvy (exit strategie)
- Řízení rizik spojených s dodavateli IS

### 6.3 Akvizice, vývoj a údržba (§ 12 vyhlášky)

- Bezpečnostní požadavky zohledněné při akvizici nebo vývoji IS
- Ověření splnění bezpečnostních požadavků
- Ověření souladu kryptografických algoritmů s požadavky § 25
- Řízení a soulad bezpečného vývoje se standardem ASVS (česky na https://www.asvsvcestine.cz)
- Dostupnost bezpečnostních aktualizací po dobu životního cyklu
- Pravidla bezpečného vývoje (pokud je IS vyvíjen interně)
