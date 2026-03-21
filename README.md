# Relais-Karte

Relais-Karte für ein 24V-System auf ELIDA.

---

## 🔧 Gedachte Verwendung

Über **J1** wird die Schaltung mit Strom versorgt.  
Über **J2** kann eine weitere Platine mit Spannung versorgt werden.

Eine **Autosicherung** schützt die Schaltung bzw. die angeschlossene Last.

Der **Schiebeschalter** ermöglicht es, die Last **unabhängig vom Relais** einzuschalten.

---

## 💡 Statusanzeigen (LEDs)

Die Platine verfügt über **zwei LEDs zur Zustandsanzeige**:

- **LED 1 – Versorgung & Sicherung OK**  
  - Leuchtet, wenn **Spannung anliegt** und die **Sicherung in Ordnung** ist

- **LED 2 – Relais aktiv / Last versorgt**  
  - Leuchtet, wenn das **Relais geschaltet hat**  
  - → Die angeschlossene **Last erhält Spannung**

---

## ⚙️ Relaissteuerung

An **J4** wird das **Schaltsignal** angeschlossen, mit dem das Relais aktiviert wird.  
Hier kann z. B. ein **Schwimmerschalter** verwendet werden.

---

## 🔌 Anschluss der Last

Die Last (z. B. eine **Pumpe**) wird an **J3** angeschlossen.

### Betriebsarten:

- **Relais schaltet EIN (NO - Normally Open):**  
  - Last zwischen **NO (+24V)** und **GND** anschließen  
  - → Last ist aktiv, wenn das Relais angezogen ist

- **Relais schaltet AUS (NC - Normally Closed):**  
  - Last zwischen **NC (+24V)** und **GND** anschließen  
  - → Last ist aktiv, wenn das Relais **nicht** angezogen ist

💡 Es können auch **zwei Lasten gleichzeitig angeschlossen** werden:  
- Eine an **NO**
- Eine an **NC**  
→ Es ist dabei **immer nur eine Last aktiv**

---

## 📝 Sonstiges

Das **weiße Feld** auf der Platine ist für Notizen vorgesehen, z. B.:

- Nummerierung
- Bezeichnung der angeschlossenen Last

---

## 📏 Technische Daten

- **PCB Maße:** 38,5 mm × 75,5 mm

![alt text](https://github.com/pellematrose/Relais-Karte/blob/main/3D_render.png "3D Render")
---
