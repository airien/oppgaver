Scratch
=======

Scratch er et programmeringsspråk utviklet ved MIT, med spesiell fokus
på å lære barn og unge å være kreative, tenke systematisk og
samarbeide med andre. Scratch er tilgjengelig på <http://scratch.mit.edu/>.

## Guide til oppgaveskrivere og oversettere

Scratchoppgavene ligger i denne katalogen. Se
[hoved README.md](/README.md#filstruktur-og-formatering) for mer info om den
generelle katalogstrukturen.

## Kodeblokker

Scratchkode kan skrives rett inn i Markdown-teksten. Denne blir oversatt til
figurer av et verktøy som heter [Scratchblocks]. Et nyttig verktøy er
[scratchblocks generatoren] som lar deg hente ut og oversette scratchkode fra
prosjekter på scratch.mit.edu. På hjemmesidene til Scratch finnes det også en
[dokumentasjon over syntaksen].

[Scratchblocks]: https://github.com/tjvr/scratchblocks
[dokumentasjon over syntaks]: http://wiki.scratch.mit.edu/wiki/Block_Plugin/Syntax
[scratchblocks generatoren]: http://scratchblocks.github.io/generator/

Hele kodesnutter skrives som et eget avsnitt på følgende måte:

<pre>
```blocks
når grønt flagg trykkes
for alltid
pek mot [musepekeren v]
slutt
```
</pre>

Hvis du vil referere til enkeltblokker i teksten kan det gjøres slik:
`` `for alltid`{.b}``. I tillegg er fargene for kategoriene tilgjengenlig:

- `` `Bevegelse`{.blockmotion}``
- `` `Utseende`{.blocklooks}``
- `` `Lyd`{.blocksound}``
- `` `Penn`{.blockpen}``
- `` `Data`{.blockdata}``
- `` `Hendelser`{.blockevents}``
- `` `Styring`{.blockcontrol}``
- `` `Sansning`{.blocksensing}``
- `` `Operatorer`{.blockoperators}``
- `` `Flere klosser`{.blockmoreblocks}``

For å referere til en fane som skript, drakter eller lyder, brukes `` ` `` slik
som dette: `` `Drakter` ``
