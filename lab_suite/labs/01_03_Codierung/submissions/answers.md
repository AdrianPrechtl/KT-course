# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*
Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'B': 1, 'A': 6, 'C': 3, 'D': 4}
Dictionary converted into a list:                   dict_items([('B', 1), ('A', 6), ('C', 3), ('D', 4)])
List of characters sorted to descending frequency:  [('A', 6), ('D', 4), ('C', 3), ('B', 1)]
Huffman Code Dictionary:                            {'A': '0', 'B': '100', 'C': '101', 'D': '11'}

 Char | Huffman code 
----------------------
 'A'  |           0
 'D'  |          11
 'C'  |         101
 'B'  |         100

---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  Jedem Zeichen bzw. Buchstaben wird ein Binärcode zugewiesen

- Warum haben häufigere Zeichen kürzere Codewörter?  
  Je öfter sie auftreten desto kürzer soll der Code sein um effizienter zu sein
