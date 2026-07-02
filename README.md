# Office Click Challenge

Loje e thjeshte me klikime per koleget e zyres. Projekti eshte statik dhe mund te publikohet direkt me GitHub Pages.
 
## Publikimi ne GitHub Pages

1. Krijo nje repository te ri ne GitHub, p.sh. `office-click-game`.
2. Ngarko file-at `index.html` dhe `README.md` ne repository.
3. Hap `Settings`.
4. Shko te `Pages`.
5. Te `Build and deployment`, zgjidh:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Kliko `Save`.

Pas pak minutash, loja hapet ne linkun qe GitHub Pages shfaq te seksioni `Pages`.

## Ruajtja e pikeve

Loja ruan automatikisht lojtarin e fundit dhe statistikat ne `localStorage`.
Kur i njejti lojtar futet perseri nga i njejti browser, emri plotesohet automatikisht dhe pikeve u shtohet rezultati i lojes se re.

Kur rezultati i lojes aktuale kalon rekordin me te larte te arritur deri ne ate moment, shfaqet automatikisht nje animacion surprize me konfeti.

Renditja eshte lokale per browser. Per renditje te perbashket per te gjithe koleget duhet shtuar backend, Firebase ose Supabase.
