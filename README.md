/*HTMl*/
Niektoré link v hlavicke su mozno zbytocne, ale prenasam ich z page do page, a su to tie kt. sa casto hodia takmer vsade. Linkovane vacsinou cez CDN.

Elementy header,section, footer, sú tu iba pre konzistentosť

Rozhodol som sa spraviť layout bez Bootstrap gridu. Príde mi jednoduchšie a rýchlejšie použiť na tento layout tabulku.

/*CSS*/

-použil som SCSS

Na úvod CSS som hodil premenné, funkcie, mixiny kt su použitelne pre tuto stránku.
 - v <!-- GLOBAL --> sú všeobecné nastavenia, kt. prenášam z page do page. Viem že niektoré (napr. tie pre images) sú tu zbytočné, ale nechávam to tam, keďže je to len test.

Ostatne časti CSS myslím netreba popisovať.
Keďže sú tu iba 2 classes (bez Bootstrap-ovskych) tak som im dal vseobecne nazvy.

CSS metodiku BEM poznám, niečo z nej viem, stále ju študujem pretože je toho dosť ale myslím že pri tomto čo som vytvoril nie je moc priestoru na to aby som BEM použil nejako efektívne.
Nemám moc obsahum kde by som napríklad uplatnil classes.

 - CSS partials som nepoužil pretože pri takomto množstve HTML & CSS  je to viac na škodu (otvoriť si napr. 4 okná _variables.scss _colors.scss, typography.scss, _mixins.scss )
   - v zadani kt. som robil pre Justmighty - som tieto ciastocne CSS pouzil (môžte si to pozrieť - dam to tiez na github)

Viem že je lepšie štýlovať hlavne pomocou classes, pretože prehliadače "vypočítavajú" tie selektory rýchlejšie, ale ID -čka kt. som použil sú tam len pre výraz.

Robil som v Sublime text 3, Windows 7


