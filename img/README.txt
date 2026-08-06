LÁSKA V KRAJKÁCH — složka s grafikou
=====================================

Celou složku "img" nahrajte na web VEDLE souboru index.html.
Struktura na serveru:

    index.html
    img/
      logo.svg, srdce.svg, mono.svg, silueta.svg, krajka.svg, favicon.svg
      (a sem přijdou fotky)


FOTKY — stačí je sem nakopírovat pod těmito názvy:

  sortiment-podprsenky.jpg    na výšku, poměr 5:4 až 3:4, min. šířka 900 px
  sortiment-kalhotky.jpg      dtto
  sortiment-plavky.jpg        dtto
  sortiment-doplnky.jpg       dtto
  interier-butiku.jpg         na šířku, min. 1400 px

Dokud fotka neexistuje, stránka místo ní ukáže srdíčkový podklad
jako dosud — nic se nerozbije a není potřeba nic přepisovat v kódu.

Doporučení: fotky před nahráním zmenšit tak, aby žádná neměla víc
než ~300 kB. Formát .webp funguje také — jen změňte příponu
v index.html (hledejte "tile-photo").


GRAFIKA — proč jsou soubory černé

logo.svg a spol. používají "currentColor" a v index.html se vkládají
jako CSS maska, takže barvu určuje styl stránky (mauve v hlavičce,
krémová v patičce). Když soubor otevřete samostatně, uvidíte ho černý.
To je v pořádku.
