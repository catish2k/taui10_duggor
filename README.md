# Matteduggor

En responsiv, statisk hemsida i HTML och CSS. Ingen backend, installation eller byggprocess behövs.

## Lägg in dina PDF:er

Lägg de tio filerna i mappen `pdfs/` med exakt dessa namn:

```text
pdfs/
  dugga_1.pdf
  dugga_2.pdf
  dugga_3.pdf
  dugga_4.pdf
  dugga_5.pdf
  dugga_6.pdf
  dugga_7.pdf
  dugga_8.pdf
  dugga_9.pdf
  dugga_10.pdf
```

Länkarna finns i `index.html`. Varje PDF öppnas i samma flik med webbläsarens PDF-visare (eller laddas ner beroende på webbläsarens inställningar). PDF:erna ingår inte: länkarna fungerar när du har lagt in filerna. Använd små bokstäver i filnamnen.

## Förhandsgranska

Öppna `index.html` direkt i din webbläsare. Även PDF-länkarna fungerar lokalt när filerna finns i mappen.

## Publicera på Vercel

1. Lägg projektet inklusive PDF:erna i ett GitHub-repository.
2. Importera repositoryt som ett nytt projekt i Vercel.
3. Välj **Other** som Framework Preset. Ingen Build Command behövs; Output Directory är `.`. Konfigurationen finns i `vercel.json`.
4. Klicka på **Deploy**. Vercel ger sidan en `vercel.app`-adress.

Sidan kräver endast statisk filhosting och kan köras på Vercels kostnadsfria Hobby-plan inom planens användningsvillkor och kvoter. Inga miljövariabler eller betaltjänster behövs.

När du lägger till eller ersätter PDF:er, pusha ändringarna till det anslutna repositoryt för en ny publicering.

Vercels dokumentation: https://vercel.com/docs/builds/configure-a-build
