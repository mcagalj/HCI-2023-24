# Korisnička sučelja <!-- omit in toc -->

## FESB, 2023/24 <!-- omit in toc -->

- [Uvod](#uvod)
- [Zahtjevi web aplikacije](#zahtjevi-web-aplikacije)
- [Demonstracija projekta](#demonstracija-projekta)
- [Praktične vježbe](#praktične-vježbe)
  - [Class projects](#class-projects)
  - [Za rad u laboratoriju](#za-rad-u-laboratoriju)
  - [Za samostalan rad](#za-samostalan-rad)

Cilj kolegija je upoznati studente sa važnim aspekatima procesa dizajna (sučelja) usmjerenog krajnjim korisnicima. Studenti će realizirati praktičan projekt u okviru kojeg će primjeniti odgovarajuće principe *dobrog dizajna*. Za realizaciju projekta koristiti će moderne tehnologije poput [React.js](https://reactjs.org/), [Next.js](https://nextjs.org/), [Figma](https://www.figma.com/), [headless CMS](https://jamstack.org/headless-cms/), Git i druge.

## Uvod

Dizajn je iterativni postupak u kojem iteriramo faze *dizajna*, *implementacije* i *evaluacije*. Vaš rad na projektu će se odvijati okvirno u sljedećim fazama:

1. **Razumijevanje korisnika i njihovih zadaća**

    > Vi niste tipičan korisnik. Ne znate koje zadaće su važne korisnicima. Da bi bili sigurni da imate dobar opis zadaća trebate ih evaluirati zajedno s korisnicima.

    U procesu _user experience_ (UX) dizajna, vrlo važnu ulogu ima koncept **persone**. Persona predstavlja model osobe (arhetip), osobnosti i/ili ponašanja koji se izgradi na osnovu razgovora, intervjua, promatranja korisnika. Model osobe uključuje i sliku tog modela osobe. Vrijednost ovog alata u UX dizajnu proizlazi i činjenice da persone pomažu dizajnerima i developerima razviti suosjećanje sa krajnjim korisnicima, čime se smanjuje rizik razvoja produkta koji će biti neintuitivan i/ili težak za korištenje.

    > [What are Personas?](https://youtu.be/XnG4c4gXaQY)

2. **Izrada *low-fidelity* i *high-fidelity* prototipa i njihova evaluacija**

    > Pokušajte odoljeti programerskom porivu da u ovoj fazi otvorite vaš preferirani editor i započnete programirati. U ovoj fazi razvoja projekta vaš dobar prijatelj su olovka i papir, razni grafički editori (npr. [Excalidraw](https://excalidraw.com/)), te alati za brzu izradu prototipa (npr. [Figma](https://www.figma.com), [Balsamiq](https://balsamiq.com/wireframes/), [Sketch](https://www.sketch.com/), [inVision](https://www.invisionapp.com/), [Draw.io](https://drawio-app.com/)).
    >
    >
    > Provedite evaluaciju vašeg prototipa s kolegama ili profesorom i popravite uočene *usability bug*-ove.

3. **Implementacija prototipa i njegova evaluacija**

    U ovoj fazi konačno možete otvoriti svoj preferirani editor i započeti s implementacijom.

    > Nemojte zaboraviti na evaluaciju u ovoj fazi (provedite heurističku evaluaciju vašeg produkta i/ili *usability testing* sa stvarnim korisnicima ako je to moguće).

## Zahtjevi web aplikacije

- Aplikacija će se koristiti iz web preglednika.
- Koristiti će se na uređajima različite veličine.
- Korisnik može pretraživati/filtrirati proizvode ili usluge.
- ~~Aplikacija će podržati logiranje korisnika za prikaz privatnog sadržaja.~~
- Jedna od javnih stranica je blog koji treba sadržavati veći broj postova različitog sadržaja (slike, videa, *code snippets*).
- Dio sadržaja aplikacije pohranjivati će se na udaljenom *headless* CMS sustavu (npr. [Contentful](https://www.contentful.com), [Strapi](https://strapi.io) i sl.) koji je prilagođen za jednostvano editiranje sadržaja. Detaljniji popis prikladnih CMS sustava dostupan je na [Jamstack](https://jamstack.org/headless-cms/).

  > Student može po želji uključiti i druge sustave (lokalne ili udaljene) pohrane podatka.

## Demonstracija projekta

- Student će pokazati produkcijsku verziju projekta.
- Produkcijska verzija projekta će biti postavljena *online* na odgovarajuću *cloud* platformu ([Vercel](https://vercel.com), [Netlify](https://www.netlify.com/) ili neku sličnu).
- Student će analizirati performanse aplikacije korištenjem sljedećeg servisa:
  - [https://www.webpagetest.org](https://www.webpagetest.org)
  - Rezultati ove analize će biti dio finalnog izvještaja.

## Praktične vježbe

### Class projects

1. [Figma essentials](/docs/class-projects/class-project-1.md)
2. [Personas, information architecture and sitemaps](/docs/class-projects/class-project-2.md)
3. [Next.js - Deploying Application](/docs/class-projects/class-project-3.md)
4. [Low/High-fidelity prototype](/docs/class-projects/class-project-4.md)
5. [Next.js - Dynamic routes, data fetching](/docs/class-projects/class-project-5.md)
6. [Full Responsive Page Coding](/docs/class-projects/class-project-6.md)
7. Weekly progress, status and problems (1/4)
8. Weekly progress, status and problems (2/4)
9. Weekly progress, status and problems (3/4)
10. Weekly progress, status and problems (4/4)


### Za rad u laboratoriju

- [Figma essentials and prototypes](/docs/figma-essentials-prototypes.md)
- [Next.js](https://nextjs.org/docs/app/building-your-application)
  - [Routing Fundamentals](https://nextjs.org/docs/app/building-your-application/routing)
  - [Pages and Layouts](https://nextjs.org/docs/app/building-your-application/routing/pages-and-layouts)
  - [Linking and Navigating](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating)
  - [Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes)
  - [Data Fetching (on the server)](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching-caching-and-revalidating)
- [Tailwind: Responsive Design](https://tailwindcss.com/docs/responsive-design)
- [Learn React: Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

### Za samostalan rad

> NEW: [Learn Next.js](https://nextjs.org/learn)

- [GitHub repository template](https://github.com/mcagalj/HCI-2023-24-template.git)
- [JavaScript tutorial](https://www.javascripttutorial.net/)
  - [JavaScript Event Loop](https://www.javascripttutorial.net/javascript-event-loop/)
- [JavaScript za rad s React-om](/docs/js-for-react.md)
- [TypeScript tutorial](https://www.typescripttutorial.net/)
- [Learn Git branching by playing a game](https://learngitbranching.js.org/)



