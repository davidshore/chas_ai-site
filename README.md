# Grupparbete: Bygg en AI-driven webbplats med Gemini API

## **Mål**

I det här grupparbetet ska ni arbeta i team för att skapa en interaktiv webbplats som använder AI via Gemini API. Varje sida ska utnyttja AI-funktionalitet på något sätt, och varje gruppmedlem ansvarar för en sida. Ni ska använda **Next.js** för att bygga sajten och **Git** och **GitHub** för att samarbeta med koden.

---

## **Uppgift**

### **1. Bygg en AI-driven webbplats**

- Skapa en webbplats med **Next.js** som innehåller flera sidor.
- Varje sida ska använda Gemini API på ett kreativt sätt för att lösa olika användningsfall.
- Alla sidor ska ha en enhetlig design för att skapa en sammanhängande användarupplevelse.

### **2. Använd Gemini API**

- Anropa Gemini API från varje sida och implementera funktioner som använder AI, t.ex. textgenerering, bildskapande eller analys.

### **3. Samarbeta i Git och GitHub**

- Använd Git för versionshantering.
- Skapa ett gemensamt GitHub-repo där alla gruppmedlemmar bidrar.

---

## **Förslag på sidor**

#### 1. **AI-driven innehållsgenerering**

- **Beskrivning:** Använd AI för att generera texter baserat på användarens input. Det kan vara blogginlägg, produktbeskrivningar eller historier.
- **Exempel:** Användaren skriver in ett ämne, och AI genererar en artikel om ämnet.

#### 2. **AI-assisterad chattbot**

- **Beskrivning:** Skapa en chattbot som använder Gemini API för att svara på användarens frågor eller ge rekommendationer.
- **Exempel:** En AI som hjälper användaren att planera en resa, hitta recept eller förstå komplexa ämnen.

#### 3. **Språköversättning och textanalys**

- **Beskrivning:** Bygg en sida där användaren kan översätta texter mellan språk eller analysera texten för ton och struktur.
- **Exempel:** Användaren klistrar in en text, och AI översätter den eller identifierar tonläge, t.ex. "positiv" eller "neutral".

#### 4. **Personifierade rekommendationer**

- **Beskrivning:** En sida där AI ger personliga rekommendationer baserat på användarens intressen.
- **Exempel:** Rekommendera böcker, filmer eller musik baserat på användarens valda genrer.

#### 5. **AI-drivet quiz eller spel**

- **Beskrivning:** Bygg ett quiz eller ett interaktivt spel som använder AI för att skapa frågor eller dynamiska scenarier.
- **Exempel:** Ett AI-genererat quiz där frågorna anpassas efter spelarens nivå.

---

## **Krav**

1. **Tekniskt:**
   - Bygg sajten med **Next.js**.
   - Använd Gemini API på varje sida.
   - Sidan ska vara responsiv och fungera på både dator och mobil.
2. **Kodhantering:**
   - Alla gruppmedlemmar ska bidra till ett gemensamt GitHub-repo.
3. **Design:**
   - Alla sidor ska ha en enhetlig design för att skapa en professionell användarupplevelse.
   - Använd gärna komponentbibliotek som Radix, Daisy UI eller Flowbite React.

---

## **Arbetsprocess**

1. **Dag 1:**
   - Sätt upp ett gemensamt GitHub-repo och skapa grundstrukturen för Next.js-projektet.
2. **Dag 2-3:**
   - Utveckla individuella sidor och börja integrera Gemini API.
3. **Dag 4:**
   - Testa och optimera sidorna.
   - Fokusera på responsiv design och sammanhängande stil.
   - Slutför integrationen och förbered presentationen.

---

## **Extrauppgifter**

1. **Addera backend**

   - Skapa en backend i Express eller Nextjs som sköter all kommunikation med Gemini API:et.
   - Lägg till anrop med `fetch` i frontend för att kommunicera med backend.

2. **Local storage**
   - Använd `localStorage` för att spara data som kan delas mellan sidor eller användas senare.
   - **Exempel 1:**
     - På en sida kan användaren välja inställningar eller skriva in information, t.ex. ett namn eller preferenser.
     - Dessa inställningar sparas i `localStorage` och kan laddas på en annan sida för att personifiera innehållet.
   - **Exempel 2:**
     - Spara en lista med användarens favoriter (t.ex. favorit-karaktärer, frågor, eller artiklar) i `localStorage` så att dessa är tillgängliga även efter siduppdatering eller vid navigering till andra sidor.
   - **Tekniskt tips:**
     - **Spara till `localStorage`:**
       ```javascript
       localStorage.setItem("key", JSON.stringify(data));
       ```
     - **Hämta från `localStorage`:**
       ```javascript
       const data = JSON.parse(localStorage.getItem("key"));
       ```
     - **Ta bort från `localStorage`:**
       ```javascript
       localStorage.removeItem("key");
       ```
   - **Utmaning:** Skapa en flöde där en sida sparar användarens input (t.ex. sökningar eller inställningar) och en annan sida läser in och använder dessa data.

---

### **Resurser**

- **Gemini API-dokumentation:** [Gemini API](https://ai.google.dev/)
- **Next.js dokumentation:** [https://nextjs.org/docs](https://nextjs.org/docs)
- **Git och GitHub guide:** [https://guides.github.com/](https://guides.github.com/)
- **Design och komponenter:** [Radix-UI](https://www.radix-ui.com/), [Daisy UI](https://daisyui.com/) eller [Flowbite React](https://flowbite-react.com/)

---

### **Tips för samarbete**

- Håll regelbundna check-ins med gruppen för att säkerställa framsteg.
- Använd GitHub Issues för att skapa tydliga uppgifter.
- Dela skisser och idéer tidigt för att säkerställa en gemensam vision.

---

### **Deadline**

Projektet ska vara klart och redo att presenteras tisdag den 28:e januari.
