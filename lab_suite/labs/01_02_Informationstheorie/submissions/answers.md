# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf? 
Das der Buchstabe e extremst oft vorkommt. Sogar äfter als Leerzeichen so wie ich das sehen kann. 
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*

---

## Konsolenausgabe

```
Analyze the file:  c:\FH Joanneum_local\KT\KT-course\lab_suite\labs\01_02_Informationstheorie\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
Die fÃ¼nf Axiome umfassen verschiedene Aspekte der menschlichen Interaktion. Sie

zeigen, dass nicht nur die gesprochenen Worte, sondern auch KÃ¶rpersprache, Tonfall

und Kontext eine zentrale Rolle spielen. Auch die Beziehungsebene, auf der eine

Kommunikation stattfindet, beeinflusst maÃŸgeblich, wie eine Nachricht

wahrgenommen wird. Kommunikation ist ein wechselseitiger Prozess, der durch

bewusste oder unbewusste Signale gesteuert wird. Selbst wenn eine Person nicht

spricht oder bewusst nicht reagiert, sendet sie dennoch eine Botschaft aus. Dies

verdeutlicht, dass die Ãœbermittlung von Informationen nicht nur das gesprochene Wort

umfasst, sondern eben auch nonverbale Elemente wie Mimik, Gestik und Tonfall

miteinbezogen sind.
Number of characters: 734
Character Dictionary: {'D': 2, 'i': 51, 'e': 103, ' ': 86, 'f': 11, 'Ã': 4, '¼': 1, 'n': 64, 'A': 3, 'x': 2, 'o': 28, 'm': 16, 'u': 23, 'a': 25, 's': 44, 'v': 4, 'r': 35, 'c': 22, 'h': 24, 'd': 24, 'p': 7, 'k': 6, 't': 42, 'l': 18, 'I': 2, '.': 6, 'S': 3, '\n': 9, 'z': 5, 'g': 12, ',': 11, 'W': 2, 'K': 4, '¶': 1, 'T': 2, 'R': 1, 'B': 2, 'b': 11, 'Ÿ': 1, 'w': 10, 'N': 1, 'P': 2, 'œ': 1, 'E': 1, 'M': 1, 'G': 1}

-------Table of characters:----------------
 e     | cnt=103    p=0.140   H=2.833 bit/char  H_av=0.398 bit/char
       | cnt= 86    p=0.117   H=3.093 bit/char  H_av=0.362 bit/char
 n     | cnt= 64    p=0.087   H=3.520 bit/char  H_av=0.307 bit/char
 i     | cnt= 51    p=0.069   H=3.847 bit/char  H_av=0.267 bit/char
 s     | cnt= 44    p=0.060   H=4.060 bit/char  H_av=0.243 bit/char
 t     | cnt= 42    p=0.057   H=4.127 bit/char  H_av=0.236 bit/char
 r     | cnt= 35    p=0.048   H=4.390 bit/char  H_av=0.209 bit/char
 o     | cnt= 28    p=0.038   H=4.712 bit/char  H_av=0.180 bit/char
 a     | cnt= 25    p=0.034   H=4.876 bit/char  H_av=0.166 bit/char
 h     | cnt= 24    p=0.033   H=4.935 bit/char  H_av=0.161 bit/char
 d     | cnt= 24    p=0.033   H=4.935 bit/char  H_av=0.161 bit/char
 u     | cnt= 23    p=0.031   H=4.996 bit/char  H_av=0.157 bit/char
 c     | cnt= 22    p=0.030   H=5.060 bit/char  H_av=0.152 bit/char
 l     | cnt= 18    p=0.025   H=5.350 bit/char  H_av=0.131 bit/char
 m     | cnt= 16    p=0.022   H=5.520 bit/char  H_av=0.120 bit/char
 g     | cnt= 12    p=0.016   H=5.935 bit/char  H_av=0.097 bit/char
 f     | cnt= 11    p=0.015   H=6.060 bit/char  H_av=0.091 bit/char
 ,     | cnt= 11    p=0.015   H=6.060 bit/char  H_av=0.091 bit/char
 b     | cnt= 11    p=0.015   H=6.060 bit/char  H_av=0.091 bit/char
 w     | cnt= 10    p=0.014   H=6.198 bit/char  H_av=0.084 bit/char
 b'\n' | cnt=  9    p=0.012   H=6.350 bit/char  H_av=0.078 bit/char
 p     | cnt=  7    p=0.010   H=6.712 bit/char  H_av=0.064 bit/char
 k     | cnt=  6    p=0.008   H=6.935 bit/char  H_av=0.057 bit/char
 .     | cnt=  6    p=0.008   H=6.935 bit/char  H_av=0.057 bit/char
 z     | cnt=  5    p=0.007   H=7.198 bit/char  H_av=0.049 bit/char
 Ã     | cnt=  4    p=0.005   H=7.520 bit/char  H_av=0.041 bit/char
 v     | cnt=  4    p=0.005   H=7.520 bit/char  H_av=0.041 bit/char
 K     | cnt=  4    p=0.005   H=7.520 bit/char  H_av=0.041 bit/char
 A     | cnt=  3    p=0.004   H=7.935 bit/char  H_av=0.032 bit/char
 S     | cnt=  3    p=0.004   H=7.935 bit/char  H_av=0.032 bit/char
 D     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 x     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 I     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 W     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 T     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 B     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 P     | cnt=  2    p=0.003   H=8.520 bit/char  H_av=0.023 bit/char
 ¼     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 ¶     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 R     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 Ÿ     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 N     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 œ     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 E     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 M     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
 G     | cnt=  1    p=0.001   H=9.520 bit/char  H_av=0.013 bit/char
-------------------------------------------

Average Entropy H = 4.477 bit/char
Total Entropy of 734 characters H=3285.83 bit = 411.00 byte
```
