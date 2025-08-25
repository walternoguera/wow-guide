# Paladín Retribución — Guía de leveo (20–40)

## ¿Boost ahora?
No, si tienes **2H lenta** (≥3.2–3.6) y usas **SoCr → Juicio → SoC**.  
Si te atascas: BFD/SFK o **RFK (28–30)** para arma grande.

## Prioridades
Arma **2H lenta** > Fuerza > Crit ≈ Agi > Sta > Int.  
Encantos: **Fiery** (barato) → **Crusader** si farmeas cómodo.

## Sellos y “swapping”
1) **Seal of the Crusader** → **Juicio** (aplica **JotC**).  
2) Cambia a **Seal of Command** y pega.  
> Usa **swing timer** y no cambies sello justo antes del swing.

## Rotación
Bendición **Might/Wisdom** · Aura **Retribution/Devotion** ·  
SoCr → Juicio → SoC → autoataques → **HoJ** si quieres burst/cortar ·  
**Consagración** solo en packs.

## Talentos 20→40
Benediction 5/5 → Imp. Judgement 2/2 → Conviction 5/5 → SoC → Two-Hand Spec 3/3.

## Ruta de armas
**Verigan’s Fist (18–29)** → **Corpsemaker (RFK ~28–30)** → **Ravager/Mograine (SM 36–40)**.

## Zonas (Alianza)
20–22 Redridge/Wetlands · 22–26 Duskwood · 26–30 Ashenvale/Thousand Needles · 30–36 Desolace/STV · 36–40 STV/Arathi/SM.

## Macros
```macro
#showtooltip
/startattack
/castsequence reset=12 Seal of the Crusader, Judgement, Seal of Command

#showtooltip Judgement
/startattack
/cast Judgement

#showtooltip Hammer of Justice
/cast [@mouseover,harm,nodead][] Hammer of Justice

#showtooltip Divine Protection
/cast Divine Protection
/stopcasting
/cast Holy Light

