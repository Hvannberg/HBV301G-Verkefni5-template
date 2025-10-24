test 6
> 💡 **ATHUGIÐ:**  
> Þetta sniðmát (template) inniheldur sjálfvirkar gæðaskoðanir (GitHub Actions) sem keyra þegar þú opnar **Pull Request (PR)**.  
> Þær:
> - sýna form þar sem þú metur eigin innsendingu (t.d. „Uppfyllir atriðið matskvarða?“ og „Hvað má betur fara?“),
> - athuga að svör séu til staðar og nægilega ítarleg áður en PR má samþykkja,
> - senda áminningu ef eitthvað vantar.
>
> 🔧 **Eftir að þú býrð til repo úr þessu sniðmáti**, vertu viss um að:
> Virkja **GitHub Actions** undir *Settings → Actions → General → Allow all actions*, og

> Sjá nánar leiðbeiningar neðst í þessari skrá.

# Verkefni 5 — Gæðaeiginleikar (HBV301G)

Setjið ykkar eigin texta um **verkefnið ykkar** og takið út eða aðlagið textann hér að neðan að ykkar verkefni. 

## Nafn kerfis

## Stutt lýsing á kerfi 

## Hópmeðlimir 


## Yfirlit
Í þessu verkefni veljið þið **5 ytri** (external) og **3 innri** (internal) gæðaeiginleika fyrir kerfið ykkar (úr Verkefni 1 eða nýtt kerfi).  
Fyrir **hvern** eiginleika:
- Skrifið **1 gæðakröfu** 
  Viðbótarskilyrði: Fyrir einn af eiginleikunum skrifaðu gæðakröfu í formlegri setningu (PLanguage). Fyrir aðra eiginleika, skrifaðu  gæðakröfuna í óformlegri setningu (informal sentence form)
- Bætið við **2–3 röksetningum** um af hverju krafan á við og hvaða **forsendur** gilda.

Veljið síðan **3 pör** úr þessum eiginleikum:
- Lýsið í **2–3 setningum** mögulegum **árekstri** milli þeirra.
- Rökstyðjið **forgangsröðun**: hvor fær að ganga fyrir og af hverju.

## Mappa & skráauppsetning
- `answers/quality-attributes.md` — allar 8 kröfurnar (5 ytri, 3 innri).
- `answers/conflicts.md` — 3 árekstrapör + rök.
- `templates/QUALITY_ATTRIBUTE.md` — endurnýtið fyrir hvern gæðaeiginleika.
- `templates/CONFLICT_PAIR.md` — endurnýtið fyrir hvert par.
- `templates/PLANGUAGE.md` — Sniðmát fyrir eina gæðakröfu skrifaða með **PLanguage** samkvæmt kafla 14 í *Wiegers & Beatty*. |
- `docs/glossary.md` — *(valfrjálst)* orðasafn hugtaka.

## Hvernig á að vinna verkefnið með þessu repo-i 
1. Opnið sniðmát í `templates/`.
2. Afritið (copy) og límið í `answers/quality-attributes.md` eða búið til sérskrár ef óskað er.
3. Fyllið út. Notið **kerfissértækar** forsendur (notendafjölda, tengingar, rekstrarumhverfi o.s.frv.).
4. Gerið commit /push með skýrum skilaboðum.
5. Samstarfsnemandinn á að rýna pull request og skrifa athugasemdir 

## Dæmi — ein stutt færsla
**Gæðaeiginleiki (ytri):** Afköst (Performance)  
**Krafa (óformleg):** Kerfið skal svara vefbeiðnum á innan við 500 ms að meðaltali undir venjulegu álagi.  
**Rök/forsendur (2–3 setn.):** Notendur hætta við aðgerðir ef bið > 1s. Við reiknum með allt að 300 samhliða notendum í hámarki; CDN og gagnagrunnsbætur styðja markið.

> Ath.: Þetta er *leiðbeinandi* dæmi. Notið eigin tölur/forsendur.
> 
> ---

## 🔧 Uppsetning eftir að þú býrð til repo úr sniðmáti

Þetta sniðmát inniheldur sjálfvirkar athuganir og spurningar sem hjálpa þér að skila vönduðu verkefni
Til að þær virki í þínu eigin repo þarftu að virkja þær í stillingum.

---

## PR-flæði 
1. **Opna PR** → haka í:
   - „Uppfyllir atriðið matskvarða…“
   - „Er textinn læsilegur og réttur?“
2. ✍️ **Skrifa „Hvað má betur fara“ í Comment** (1–3 atriði).
3. **PR Quality Check** verður að vera **grænn** áður en má merge-a.

> Ef “PR Quality Check” vantar í lista yfir required checks:  
> *Settings → Branches → Add rule → main → Require status checks → PR Quality Check.*

---

## Fljót uppsetning (fyrir repo úr sniðmáti)
1. *Settings → Actions → General* → **Allow all actions and reusable workflows**.  
2. *(Valkv.)* *Settings → Branches* → setja **PR Quality Check** sem required.

---
