

<a name="oben"></a>

# Paper-Circuit-Kippstufe
Einfache Blinkschaltung mit zwei Transistoren und zwei LEDs


## Schaltplan

![Schaltplan](/pic/Schaltplan.png)


## Funktion

In der Kippstufe, auch astabiler Multivibrator genannt, sind zwei Transistoren vorhanden. Abwechslungsweise leitet und sperrt jeweils ein Transistor. 
Die LED am Kollektor des leitenden Transistors leuchtet und die jenige am Kollektor des sperrenden Transistors bleibt dunkel.

Wenn T1 leitet und T2 sperrt, dann leuchtet die LED D1. Der Basisanschluss von T1 ist auf 0.6V und sein Kollektoranschluss auf 0.2V. 
Die Spannung am Kollektor von T2 ist gleich der Speisespannung. Über R2 wird C1 aufgeladen und die Spannung an der Basis von 
T2 steigt, bis sie 0.6V beträgt. T2 beginnt zu leiten.

Die Spannung am Kollektor von T2 wird auf 0.2V gezogen. Durch die Verbindung mit C2 sinkt dadurch auch die Basisspannung von T1. 
T1 beginnt zu sperren. LED D1 erlischt. LED D2 leuchtet.

T2 leitet jetzt und T1 sperrt. Der Basisanschluss von T2 ist auf 0.6V und sein Kollektoranschluss auf 0.2V. Die Spannung am Kollektor von T1 
ist gleich der Speisespannung. Über R3 wird C2 aufgeladen und die Spannung an der Basis von T1 steigt, bis sie 0.6V beträgt. T1 beginnt zu leiten.

Die Spannung am Kollektor von T1 wird auf 0.2V gezogen. Durch die Verbindung mit C1 sinkt dadurch auch die Basisspannung von T2. T2 beginnt zu sperren. 
LED D2 erlischt und LED D1 leuchtet. Der Zyklus biginnt von vorne.


## Berechnung der Frequenz

![Bild](/pic/Formel.png)

In unserem Beispiel mit R=47k und C=10uF beträgt die Blinkfrequenz ca. 1,5Hz


## Paper Circuit

Verwende beidseitig leitendes CU-Klebeband.

Variante 1:

![Bild](/pic/PaperCircuit1.png)

Variante 2:

![Bild](/pic/PaperCircuit2.png)

Variante 3:

![Bild](/pic/PaperCircuit3.png)




## BOM

| Stück | Bezeichnung |
| -------- | -------- | 
| 1        | 9V Clipp       | 
| 1        | 9V Batterie        | 
| 2       | R 470       | 
| 2        | R 47k       | 
| 2        | LED 5mm rot        |
| 2         | BC548       |
| 2       | 10uF     |
| 1        | Schaltdraht        |
| 1        | CU-Band       |

---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>

---

