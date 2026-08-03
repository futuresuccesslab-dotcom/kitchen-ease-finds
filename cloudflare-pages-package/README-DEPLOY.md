# Kitchen Ease Finds — GitHub + Cloudflare Pages

Acest pachet este un site static. Nu necesita Node.js, npm, WordPress sau baze
de date.

## 1. Incarcarea in GitHub

1. Creeaza un repository nou, de exemplu `kitchen-ease-finds`.
2. Dezarhiveaza pachetul pe calculator.
3. In GitHub apasa **Add file → Upload files**.
4. Incarca folderul `public` si fisierul `README-DEPLOY.md`.
5. Apasa **Commit changes**.

Important: in repository trebuie sa se vada direct folderul `public`, nu un
folder suplimentar care contine intregul proiect.

## 2. Publicarea prin Cloudflare Pages

1. Intra in Cloudflare Dashboard.
2. Deschide **Workers & Pages**.
3. Alege **Create application → Pages → Connect to Git**.
4. Selecteaza repository-ul `kitchen-ease-finds`.
5. Foloseste urmatoarele setari:

- Framework preset: `None`
- Build command: `exit 0`
- Build output directory: `public`
- Root directory: lasa necompletat

6. Apasa **Save and Deploy**.

## 3. Adaugarea unui produs nou

1. Duplica folderul:

   `public/products/product-template`

2. Redenumeste copia folosind litere mici si cratime, de exemplu:

   `public/products/vegetable-chopper`

3. Deschide fisierul `index.html` din folderul nou.
4. Inlocuieste toate textele marcate cu:

   `REPLACE:`

5. Adauga o imagine editoriala originala sau o fotografie autorizata in `public/assets/products`.
6. Inlocuieste `AFFILIATE_LINK_HERE` cu linkul Amazon afiliat.
7. Adauga un card pentru produs pe pagina `public/index.html`.

## Reguli importante

- Foloseste imagini editoriale originale sau fotografii ale produsului pentru care ai drepturi clare de utilizare.
- Nu introduce preturi fixe; preturile Amazon se pot modifica.
- Nu spune ca produsul este testat daca nu a fost testat.
- Nu face afirmatii medicale sau promisiuni garantate.
- Pastreaza declaratia Amazon Associates pe fiecare pagina comerciala.
