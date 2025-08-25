# Brujo Aflicción — Drain Tanking (leveo 1–60)

> Basado en *Dive’s Drain Tanking Guide* (adaptado y resumido en español). La idea es subir con **DoTs + robo de vida**, sin parar a comer/beber y sin depender del vacío como “tanque”. :contentReference[oaicite:0]{index=0}

---

## ¿Qué es *drain tanking* y por qué funciona?

![Drain Life](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_lifedrain02.jpg){ width=22 } **Drain tanking** = aplicar **DoTs** (Corruption, CoA) y **sostenerte** con **Drain Life** + **Siphon Life** + **Life Tap/Dark Pact**, convirtiendo **vida⇄maná** para **cero downtime**. No dependes del aggro del demonio (el vacío en Classic pega poco), así que no te frenas por amenaza o por fragmentos. Es un estilo activo y muy constante para farmear horas. :contentReference[oaicite:1]{index=1}

---

## Núcleo del kit

- ![Corruption](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_abominationexplosion.jpg){ width=22 } **Corruption** – Tu DoT base (2.0 s de casteo en Classic). :contentReference[oaicite:2]{index=2}  
- ![Curse of Agony](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_curseofsargeras.jpg){ width=22 } **Curse of Agony** – Escala hacia el final; aplícala al principio del combate.  
- ![Siphon Life](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_requiem.jpg){ width=22 } **Siphon Life** – Robo de vida periódico, pieza clave del sustain. :contentReference[oaicite:3]{index=3}  
- ![Drain Life](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_lifedrain02.jpg){ width=22 } **Drain Life** – Canalizas daño y te curas; el “tanqueo” lo haces tú. :contentReference[oaicite:4]{index=4}  
- ![Life Tap](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_burningspirit.jpg){ width=22 } **Life Tap** – Convierte vida en maná (mantén tu ciclo vida⇄maná). :contentReference[oaicite:5]{index=5}  
- ![Dark Pact](https://wow.zamimg.com/images/wow/icons/large/spell_shadow_darkritual.jpg){ width=22 } **Dark Pact** – Roba maná al demonio (talento Affli 30 pts). :contentReference[oaicite:6]{index=6}  
- **Demonio**: **Súcubo** (DPS/control) desde 20; **Felhunter** si necesitas purgas/silencios. El **Voidwalker** es más lento y se queda corto de amenaza (justo lo que evita este estilo). :contentReference[oaicite:7]{index=7}

---

## Rotación (single target)

1) **Corruption** → **Curse of Agony** → **Siphon Life**.  
2) **Wand**/**Shadow Bolt** si necesitas abrir distancia.  
3) **Drain Life** cuando el objetivo está “cargado” de DoTs (y tu vida lo agradece).  
4) **Life Tap** según necesites maná; **Dark Pact** cuando tengas súcubo/felhunter activos.  
5) Control: **Fear** (juega con el terreno) y **Seduction** de la súcubo para adds.

> Objetivo: **encadenar pulls** con vida/maná casi estables (vida 40–80%, maná 30–70%) gracias al bucle *Tap ↔ Drain Life/Siphon*. :contentReference[oaicite:8]{index=8}

---

## Talentos (esqueleto 1–60)

**Aflicción** pura, pivotando al *drain tank*:

- Early: *Improved Corruption 5/5*, *Suppression* 2–3/5 (según equipo), *Improved Life Tap 2/2*, *Grim Reach*, *Nightfall 2/2*.  
- Mid (20–40): *Siphon Life*, *Amplify Curse*, *Shadow Mastery*.  
- Late (40+): *Dark Pact* (30 pts Affli) + rellenos de utilidad.

> El punto de inflexión es cuando ya tienes **Siphon Life** (30) y **Dark Pact** (40): el flujo vida⇄maná se vuelve **comodísimo** y apenas paras. :contentReference[oaicite:9]{index=9}

---

## Demonios y manejo

- **Súcubo**: mejor DPS y **Seduction** para controlar. Ideal al levear en PvP.  
- **Felhunter**: utilidad (purga, silencio) en zonas con casters.  
- **Voidwalker**: útil al principio o para quests específicas; **no** es la base del método. :contentReference[oaicite:10]{index=10}

---

## Prioridades de estadística / equipo

- **+Spell Power (Sombra)** y **Varita potente** durante 20–40.  
- **Espíritu** ayuda a regen out-of-combat, pero tu sustain real viene de **Tap/Pact/Drain/Siphon**.  
- **Bastón/vara** con buen DPS y *+shadow* cuando puedas.

---

## Macros útiles

```macro
#showtooltip Drain Life
/stopcasting
/cast Drain Life

#showtooltip Seduction
/cast [@focus,harm,nodead][] Seduction

#showtooltip
/petattack
/castsequence reset=target Corruption, Curse of Agony, Siphon Life

#showtooltip Dark Pact
/cast Dark Pact
/cast Life Tap
