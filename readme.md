Från LearnWeCode "Bavk end web development"
https://youtu.be/1oTuMPIwHmk?si=nGj9YlUPu-47dVpU

starta server med: npm run dev

Se users i databasen:

- gå in i DB Browser for AQLite
- öppna aktuell databas som heter "ourApp.db" inte de som slutar Wal eller shm
- markera users, högerklicka och välj "browse table"
- En user att använda assar/bajsar

Forstätt 1,26,28
Fortsätt 1,47,50
Fortsätt 1,56,46 list of posts..
2,16,00 kan inte se andras posts

---

DEPENDENDCIES i detta project:

Här är en kort beskrivning av varje dependency och en kommentar om eventuella populära alternativ:

# bcrypt:

Används för att hasha lösenord innan de lagras i databasen för att öka säkerheten. Den skapar ett hash av lösenordet som är svårt att reversera.
Populära alternativ: argon2 (som anses säkrare) eller bcryptjs (en ren JavaScript-implementation av bcrypt).

# better-sqlite3:

En synkron SQLite-databasmodul som är snabbare och enklare att använda än många andra SQLite-bibliotek. Det används ofta för mindre projekt som behöver en inbäddad databas.
Populära alternativ: sqlite3 (som använder asynkrona operationer) eller Sequelize (en ORM som stöder flera databaser).

# cookie-parser:

Middleware för Express som analyserar cookie-huvuden och gör dem tillgängliga i req.cookies. Praktiskt för att hantera sessionshantering och autentisering.
Populära alternativ: express-session (för att hantera sessioner med cookies inbyggt).

# dotenv:

Används för att läsa in miljövariabler från en .env-fil och göra dem tillgängliga i process.env. Hjälper till att separera känslig information från koden.
Populära alternativ: config (ger en mer strukturerad konfigurationshantering) eller cross-env (för att sätta miljövariabler på tvärs av plattformar).

# ejs:

En enkel "templating engine" som låter dig skapa HTML med inbäddad JavaScript. Används ofta med Express för att generera dynamiska webbsidor.
Populära alternativ: pug (tidigare Jade, en mer kompakt syntax) eller handlebars (mer fokuserad på logiklös rendering).

# express:

Ett minimalistiskt webbapplikationsramverk för Node.js, populärt för att bygga REST API
och backend-servrar på ett enkelt sätt.
Populära alternativ: Koa (en modernare och mindre version av Express) eller Hapi (en kraftfullare, mer konfigurerbar lösning).

# jsonwebtoken:

Används för att skapa och verifiera JSON Web Tokens (JWT) som ofta används för autentisering och sessionshantering.
Populära alternativ: passport (som erbjuder flera strategier för autentisering) eller auth0 (en tjänst som hanterar autentisering via JWT).

# nodemon:

Ett utvecklingsverktyg som övervakar din kod för förändringar och automatiskt startar om din Node.js-applikation. Användbart för snabb utveckling.
Populära alternativ: pm2 (används för både utveckling och produktion med fler funktioner) eller forever (för långvarig drift).

# sanitize-html:

Ett bibliotek för att sanera HTML och skydda mot XSS (Cross-Site Scripting) attacker genom att filtrera bort skadliga element och attribut.
Populära alternativ: DOMPurify (mycket effektiv för client-side HTML-skydd) eller xss (ett annat bibliotek för server-side sanering).
