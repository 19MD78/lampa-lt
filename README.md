# Lampa — lietuvių kalbos įskiepis

Pilnas **Lampa** (https://lampa.stream) vertimas į lietuvių kalbą.

## Kaip naudoti

1. Atidaryk Lampa
2. **Nustatymai → Plėtiniai → Pridėti įskiepį**
3. Įklijuok nuorodą:

```
https://19md78.github.io/lampa-lt/lt-plugin.js
```

4. Paleisk Lampa iš naujo
5. **Nustatymai → Sąsaja** (arba kalbos pasirinkimas) → pasirink **Lietuvių**

Oficialus PR į yumata/lampa: https://github.com/yumata/lampa/pull/311
(Priimus PR'ą, „Lietuvių“ atsiras visose Lampa versijose be įskiepio.)

## Failai

- `lt-plugin.js` — įskiepis (užregistruoja `lt` kalbą su 1253 vertimo raktais)

## Naudojami API

- `Lampa.Lang.addCodes({ lt: 'Lietuvių' })`
- `Lampa.Lang.AddTranslation('lt', { ... })`
