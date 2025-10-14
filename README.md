# Verkefni 5 — Gæðaeiginleikar (HBV301G)

## Yfirlit
Í þessu verkefni veljið þið **5 ytri** (external) og **3 innri** (internal) gæðaeiginleika fyrir kerfið ykkar (úr Verkefni 1 eða nýtt kerfi).  
Fyrir **hvern** eiginleika:
- Skrifið **1 gæðakröfu** í óformlegri setningu.
- Bætið við **2–3 röksetningum** um af hverju krafan á við og hvaða **forsendur** gilda.

Veljið síðan **3 pör** úr þessum eiginleikum:
- Lýsið í **2–3 setningum** mögulegum **árekstri** milli þeirra.
- Rökstyðjið **forgangsröðun**: hvor fær að ganga fyrir og af hverju.

## Mappa & skráauppsetning
- `answers/quality-attributes.md` — allar 8 kröfurnar (5 ytri, 3 innri).
- `answers/conflicts.md` — 3 árekstrapör + rök.
- `templates/QUALITY_ATTRIBUTE.md` — endurnýtið fyrir hvern gæðaeiginleika.
- `templates/CONFLICT_PAIR.md` — endurnýtið fyrir hvert par.
- `docs/glossary.md` — *(valfrjálst)* orðasafn hugtaka.

## Hvernig á að vinna
1. Opnið sniðmát í `templates/`.
2. Afritið (copy) og límið í `answers/quality-attributes.md` eða búið til sérskrár ef óskað er.
3. Fyllið út. Notið **kerfissértækar** forsendur (notendafjölda, tengingar, rekstrarumhverfi o.s.frv.).
4. Gerið commit með skýrum skilaboðum.

## Dæmi — ein stutt færsla
**Gæðaeiginleiki (ytri):** Afköst (Performance)  
**Krafa (óformleg):** Kerfið skal svara vefbeiðnum á innan við 500 ms að meðaltali undir venjulegu álagi.  
**Rök/forsendur (2–3 setn.):** Notendur hætta við aðgerðir ef bið > 1s. Við reiknum með allt að 300 samhliða notendum í hámarki; CDN og gagnagrunnsbætur styðja markið.

> Ath.: Þetta er *leiðbeinandi* dæmi. Notið eigin tölur/forsendur.