# 🤖 Automatisk Elevplacerare 3000

Ett smart, snabbt och enkelt webbaserat verktyg skapat för lärare som vill automatisera och optimera bordsplaceringar och gruppindelningar i klassrummet. 

Istället för att pussla med post-it-lappar kan du låta programmet testa tiotusentals kombinationer på en sekund för att hitta en placering där alla dina sociala och pedagogiska regler följs.

## ✨ Funktioner

* **Två lägen:** Skapa en fysisk bordsplacering utifrån klassrummets form, eller dela in klassen i ett valfritt antal arbetsgrupper.
* **Flexibel klassrumsdesign:** Rita upp exakt hur dina bänkar står (rader, parbänkar, u-sittning osv).
* **Smarta anpassningar (Regler):**
  * Tvinga elever att sitta längst fram eller längst bak (gäller bordsplacering).
  * Bestäm vilka som *måste* sitta bredvid varandra i klassrummet.
  * Bestäm vilka som *inte* får sitta bredvid varandra eller hamna i samma grupp.
* **Spara och Ladda:** Spara dina klasser, layouter och regler som en fil på datorn och ladda in dem nästa gång.
* **Utskriftsvänlig:** Exportera direkt till en snygg och tydlig PDF, redo att sättas upp på tavlan.
* **Integritetssäker:** Allt körs direkt i din webbläsare. Inga elevnamn skickas till någon server.

---

## 🚀 Kom igång (Användning)

Du kan testa programmet live här: **[https://ivanlarare.github.io/Elevplacerare/](https://ivanlarare.github.io/Elevplacerare/)**

*(Eller ladda ner `index.html` och dubbelklicka på filen för att öppna den direkt i din webbläsare).*

**1. Klasslista och Layout**
1. Klistra in dina elever i rutan **Klasslista** (ett namn per rad).
2. Klicka på **⚙️ Inställningar (Layout)** för att "rita" ditt klassrum. 
   * Skriv `X` för en bänk.
   * Skriv `-` (bindestreck) för ett tomrum / en gång.

**2. Anpassningar (De sociala reglerna)**
Inne i inställningarna klickar du på **❌ Öppna** bredvid *Anpassningar*. Separera alltid namn med ett kommatecken.
* **Längst fram / Längst bak:** Skriv in elever som behöver sitta på första eller sista raden i klassrummet.
* **MÅSTE sitta ihop (Endast Klassrum):** Skriv in ett par per rad (t.ex. `Anna, Kalle`). De garanteras att sitta horisontellt axel mot axel, utan någon gång emellan. *(Obs: Denna regel ignoreras när du skapar grupper).*
* **Får INTE sitta/vara i grupp ihop:** Skriv in par som behöver arbetsro från varandra. Eleverna kommer aldrig hamna i samma arbetsgrupp eller direkt intill varandra i bänkarna.

**3. Slumpa fram ett resultat!**
* **Bordsplacering:** Klicka på **Placera i Klassrummet!** för en klassisk bordsplacering.
* **Grupper:** Välj antal grupper och klicka på **Slumpa Grupper!** för att dela in klassen i projektgrupper.
* Blev det inte perfekt? Klicka på knappen igen för att slumpa fram ett helt nytt alternativ som fortfarande följer alla dina regler!

---

## 👨‍💻 Skapad av
Utvecklad av **Ivan Kljucevic** för att underlätta lärares vardag.

## ⚖️ Licens
Detta projekt är licensierat under **GPL-3.0 License**. Detta innebär att programmet är öppen källkod och fri att använda, ändra och distribuera, så länge alla framtida versioner också förblir öppna och gratis under samma licens.
