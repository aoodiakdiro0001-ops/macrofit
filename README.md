# 🥗 MacroFit — Macro & Meal Calculator (MIT)

Calories, macros and smart food swaps. UI in EN/TR/AR. Static single file.

## Math (standard, verified)

- **BMR:** Mifflin-St Jeor; **TDEE:** × activity (1.2–1.9).
- **Goals:** lose/cut by weekly rate (0.25/0.5/1.0 kg → ±275/550/1100 kcal),
  bulk +300. Safety floor (1200/1350/BMR×1.05) with warning.
- **Macros:** protein 1.7–2.1 g/kg by goal, fat 25% kcal, carbs remainder;
  fiber 14g/1000kcal, water 35ml/kg. Macrobar + per-meal split.
- **Swaps:** 25-food database (per-100g P/C/F); equivalents by kcal,
  protein or carbs; full comparison table.
- **Sample menu:** greedy builder from targets (approximate).

## Money & contact

- `CONFIG.supp` affiliate slots (iHerb/Amazon search URLs) with REF badges.
- `CONFIG.ads` footer slot (health-food/supplement ads).
- Donate: BTC + USDT-TRC20 + IBANs.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd macrofit
python3 -m http.server 8080
```

## License

MIT. Educational estimates — not medical advice.
