# Calculul autoutilitarelor electrice

Aplicația îndrumarului „Proiectarea sistemelor de propulsie electrice ale autoutilitarelor” (C. Tudor, A.-M. Beldugan, Universitatea „Ovidius” din Constanța, 2026).
Rulează integral în browser, fără server și fără instalare.

- **Mase și dimensionare (cap. 1–3):** sarcina utilă maximă, masa de încercare WLTP N1, motorul, reductorul, bateria, performanțele la masa de încercare și la masa maximă.
- **Validare WLTC:** autonomia la masa de încercare, comparată cu cea publicată.
- **Traseu și sarcină utilă (cap. 2, 5):** traseul parametric de livrări, consumul în funcție de sarcina utilă.
- **Tura zilnică (cap. 3, 5):** patru scenarii (gol / încărcat, vară, caniculă, iarnă), bateria nouă și la SOH de sfârșit.
- **Agregat frigorific (cap. 4):** consumul ePTO, cu deschiderile ușii.
- **Încărcare la depou (cap. 6), Cost pe km (cap. 7), Verificări (§10.2).**

Exemplele eJolly furgon (49 / 75 kWh) și eJolly frigorific dau exact valorile din îndrumar.

## Publicare pe GitHub Pages

1. Creați depozitul public `calcul-utilitare` în contul `beldugan` și încărcați în rădăcina lui fișierele `index.html`, `style.css`, `app.js`, `lcv.js`, `presets.js`, `ciclu.js` (și, opțional, acest README).
2. Settings → Pages → Source: *Deploy from a branch*, ramura `main`, dosarul `/ (root)`.
3. Aplicația devine disponibilă la `https://beldugan.github.io/calcul-utilitare/` (adresa din codul QR al îndrumarului).
