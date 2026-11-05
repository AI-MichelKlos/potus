# Præsidentvalg i USA, delstat for delstat

Interaktivt kort over, hvem der fik flest stemmer i hver delstat ved alle præsidentvalg fra 1864 til 2024.

- `index.html`: kortet som selvstændig side
- `embed.html`: samme kort som et indlejringsstykke til "Embed (HTML)"-feltet på danskeakasser.dk (CSS og JavaScript er afgrænset til kortets egen beholder)

Kortet bruger D3 og TopoJSON, som hentes fra jsDelivr. Delstatsgrænser er fra US Atlas (indlejret i filen).

Kilde: Wikipedia, resultater pr. delstat (samlet i datasættet Margin Matters). Grafik og databehandling: Danske A-kasser.

Valgmænd er fordelt efter delstatens resultat, med kendte delinger (fx Californien 1892 og 1912 og Alabama 1960). Ved ældre valg er valgmænd, som Kongressen ikke talte med (fx Louisiana og Tennessee 1864), markeret i kortet. Enkelte valgmænd har stemt anderledes end deres delstat (fx 7 i 2016), så de officielle totaler kan afvige med få stemmer.

Portrætter af de valgte præsidenter kan lægges i mappen `billeder/`. Se `billeder/README.md` for filnavne.
