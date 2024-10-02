Prikazy:
Is-yypise obsah domovskeho priecinka
cd-change directory (napr.- cd Dokumenty/dev)
npx create-next-app@latest - prikaz na instalaciu o
npm run dev – spustenie
npm run build – alt spustenie
npm install @mui/material @emotion/react @emotion/styled - prikaz na instalaciu mui
ak nejde instalacia mui ( 1 error) tak : -npm audit fix –force
github config
git init -
git branch -m main-
git config --global user.name "GregorFury123“
git config --global user.email „mbig2653@gmail.com“
git remote add origin https:/GregorFury123/github.com/insta.git
git remote -v
git add .
npm run build
Poznámky:
1.
GRID - The Grid component works well for a layout with a known number of columns. The columns can be configured with multiple breakpoints to specify the column span of each child.
COTAINER - While containers can be nested, most layouts do not require a nested container.
BOX - The Box component is a generic, theme-aware container with access to CSS utilities from MUI System.
2.
github je nasa kolekcia suborov s kotrymi pracujeme, ktoré nakoniec kompilujeme a oridávame do živého internetu pomocou stránky Vercel. Na github ukladáme pomocou „commit“ a „sync changes“ toto nám umožní preniesť lokálne zmenu kódu priamo na iternet
