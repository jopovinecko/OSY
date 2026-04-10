# 🐧 Live Linux vo WebVM (browser Linux)

## 💡 Popis
WebVM je systém, ktorý umožňuje spustiť Linux priamo v prehliadači bez inštalácie.

Linux beží ako webová aplikácia v Google Chrome a nevyžaduje USB, VirtualBox ani administrátorské práva.

---

## ⚙️ Ako to funguje
- Linux beží v prehliadači (Chrome / Edge)
- využíva emuláciu hardvéru cez WebAssembly
- všetko beží online
- súbory sú uložené vo virtuálnom systéme

---

## 🚀 Spustenie
1. Otvor WebVM stránku
2. Klikni na "Launch"
3. Počkajte na načítanie systému
4. Používaj Linux terminál

---

## 📁 Práca so súbormi

nenasiel som ako stiahnut subor,
mali by sa ukladat priamo na google


# 🟠 Dual Boot Linux + Windows cez USB

## 💡 Čo je Dual Boot
Dual Boot je spôsob, ako mať na jednom počítači dva operačné systémy – Windows a Linux – a pri štarte si vybrať, ktorý chceš použiť.

---

## ⚙️ Ako to funguje
- Windows zostáva na disku
- Linux sa nainštaluje na druhú partíciu
- pri štarte PC sa zobrazí boot menu
- používateľ si vyberie systém

---

## 🧰 Potrebné nástroje
- USB kľúč (min. 8 GB)
- Linux ISO:
  - Ubuntu alebo Linux Mint
- nástroj Rufus:
  - :contentReference[oaicite:0]{index=0}
- Windows 10 počítač

---

## 🚀 Postup inštalácie

### 1. Stiahnutie Linuxu
Stiahni ISO súbor:
- :contentReference[oaicite:1]{index=1}
- alebo :contentReference[oaicite:2]{index=2}

---

### 2. Vytvorenie boot USB
1. Otvor Rufus
2. Vlož USB kľúč
3. Vyber ISO súbor
4. Klikni START

---

### 3. Bootovanie z USB
- reštartuj PC
- stlač F12 / ESC / F9
- vyber USB

---

### 4. Inštalácia Linuxu
- klikni Install Linux
- vyber:
  👉 Install alongside Windows

---

### 5. Dokončenie
- dokonči inštaláciu
- reštartuj PC

---

## ⚠️ Riziká
- nesprávne rozdelenie disku môže spôsobiť stratu dát
- odporúča sa záloha Windows
- niektoré školy blokujú bootovanie z USB

---

## ✅ Výhody
- plný Linux výkon
- Windows zostáva zachovaný
- vhodné na učenie a programovanie

---

## ❌ Nevýhody
- riziko pri inštalácii
- potreba USB
- nie vždy povolené v škole

---

## 🧠 Zhrnutie
Dual Boot umožňuje používať Windows aj Linux na jednom počítači a vybrať si systém pri štarte PC.
``` id="dualboot_md"

---

# 🟢 3. steps.md (krátky návod)

```md id="dualboot_steps"
# 🟠 Dual Boot – rýchly postup

1. Stiahni Ubuntu / Linux Mint  
2. Vytvor USB cez Rufus  
3. Reštartuj PC  
4. Otvor boot menu (F12 / ESC)  
5. Spusť USB  
6. Vyber "Install alongside Windows"  
7. Dokonči inštaláciu  
8. Vyber systém pri štarte  
``` id="steps_md"

---

# 🟢 4. notes.txt (poznámky)

```txt id="notes_txt"
Dual Boot = Windows + Linux na jednom PC.

Používa sa boot menu pri štarte.