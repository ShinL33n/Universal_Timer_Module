[PL]
# Sprawozdanie
## Opis montażu 
Na początku montażu zostały nawiercone pady w miejscach gdzie powinny znajdować się elementy przewlekane. Następnie do płytki przylutowano podstawki pod układy scalone oraz potencjometr i elementy przewlekane, a na koniec elementy SMD. Przebieg lutowania wyglądał następująco; przykładano grot do elementu w celu punktowego rozgrzania materiału a następnie podawano odpowiednią ilość cyny z topnikiem. Po przylutowaniu każdego elementu odcinano nóżki, jeżeli dany element je posiadał. Połyskujące luty świadczą o dobrej jakości połączeń. Na każdym etapie montażu elementów oceniano wizualnie czy lut jest odpowiedniej jakości oraz czy nie doszło do zwarcia ścieżek. W pewnych miejscach potrzebne było wywiercenie szerszych otworów aby umiejscowić w nich  elementy o grubszych nóżkach. Podczas wiercenia jednego z nich przypadkiem przewiercono łączenie ścieżki z padem, co jednak naprawiono przez naniesienie lutowia pomiędzy nóżkę elementu a rozłączoną ścieżkę. Oprócz tego nie doszło do żadnych nieprzewidywalnych zdarzeń (takich jak zły rozstaw nóżek w porównaniu do otworów).
## Opis zestawu uruchomieniowego
Zestaw uruchomieniowy składał się z następujących elementów: 
- układ czasowy, 
- zasilacz, 
- multimetr
Do płytki podłączono zasilacz, oraz do 2 z 3 wyjść podłączono multimetr. Wartość napięcia potrzebnego do prawidłowego działania układu to 12V.
## Opis uruchomienia 
Po upewnieniu się, że w układzie nie ma żadnych zwarć, stopniowo zwiększano poziom napięcia zasilacza. Taki zabieg miał na celu uchronienie układu przed spaleniem się. Przed osiągnięciem wymaganego poziomu napięcia układ działał nieprzewidywalnie, czyli przełączał się w losowych momentach. Podczas zwiększania napięcia obserwowano również poziom prądu zasilacza, w celu wykrycia ewentualnego zwarcia.
## Przebieg pomiarów  
Po ustawieniu odpowiedniego wypełnienia oraz napięcia, układ zaczął działać. Za pomocą potencjometrów można było zmieniać czasy przełączania układu. Bardzo pomocna była dioda LED która w jednym ustawieniu się świeciła, a w drugim gasła. Za pomocą górnego potencjometru można było regulować czas kiedy przekaźnik był w pozycji która odpowiadała zapalonej diodzie, a za pomocą dolnego w drugiej pozycji. Pozycję która odpowiadała zapalonej diodzie można było zmienić od zakresu 0.2 sekundy do 7 sekund. Zmierzono to za pomocą stopera (przy dłuższych okresach) oraz za pomocą telefonu, nagrywając diodę i spowalniając nagranie. Pozycję odpowiadającą zgaszonej diodzie można było zmienić od 0.2 sekundy do 1 minuty i 12 sekund. Różnica spowodowana jest tym, że dolny potencjometr ma wartość do 1 MΩ, natomiast górny do 50KΩ.

<img width="1021" height="797" alt="image" src="https://github.com/user-attachments/assets/f66676ad-4e3f-45dd-96ee-c6841e97816b" />
_Rys. 1 Zmontowana płytka widziana ze strony komponentów THT._

<img width="749" height="569" alt="image" src="https://github.com/user-attachments/assets/1ea3d107-fe8c-4760-930e-16a060001f1e" />
_Rys. 2 Zwizualizowana zasada działania układu._
## Podsumowanie
Układ działa zgodnie z oczekiwaniami, co oznacza poprawne zamontowanie elementów na płytce. Poprawne zaprojektowanie płytki w programie EAGLE znacząco ułatwia późniejsze montowanie. Podczas pomiarów stwierdzono, że dobrze byłoby zastosować 2 takie same potencjometry, aby mieć możliwość ustawienia równych wartości czasów przełączania.

[ENG]
# Report
## Assembly Description
At the start of assembly, pads were drilled in the places where through-hole components were to be mounted. Next, IC sockets, the potentiometer and the other through-hole components were soldered to the board, and the SMD components were soldered last. The soldering procedure was as follows: the iron tip was applied to the component to heat the joint locally, and then an appropriate amount of flux-core solder was fed in. After each component was soldered, its leads were trimmed, if it had any. Shiny solder joints indicate good connection quality. At every stage of assembly, the solder joints were visually inspected for quality and for short circuits between traces. In some places, wider holes had to be drilled to fit components with thicker leads. While drilling one of them, the connection between a trace and a pad was accidentally drilled through, but this was repaired by applying solder between the component lead and the disconnected trace. Apart from that, no unforeseen problems occurred (such as lead spacing not matching the holes).
## Description of the Test Setup
The test setup consisted of the following elements:
- timer circuit,
- power supply,
- multimeter.
The power supply was connected to the board, and a multimeter was connected to 2 of the 3 outputs. The voltage required for the circuit to operate correctly is 12 V.
## Start-up Description
After making sure there were no short circuits in the circuit, the power supply voltage was increased gradually. This was done to protect the circuit from burning out. Before the required voltage level was reached, the circuit behaved unpredictably, i.e. it switched at random moments. While the voltage was being increased, the supply current was also monitored in order to detect a possible short circuit.
## Measurement Procedure
After setting the appropriate duty cycle and voltage, the circuit started working. The potentiometers could be used to change the switching times of the circuit. An LED, which was lit in one state and off in the other, was very helpful. The upper potentiometer adjusted the time during which the relay was in the position corresponding to the lit LED, and the lower one adjusted the time in the other position. The time of the position corresponding to the lit LED could be varied from 0.2 seconds to 7 seconds. This was measured with a stopwatch (for longer periods) and with a phone, by recording the LED and slowing down the video. The time of the position corresponding to the unlit LED could be varied from 0.2 seconds to 1 minute and 12 seconds. The difference is caused by the fact that the lower potentiometer has a value of up to 1 MΩ, while the upper one has up to 50 kΩ.

<img width="1021" height="797" alt="image" src="https://github.com/user-attachments/assets/f66676ad-4e3f-45dd-96ee-c6841e97816b" />
_Fig. 1 The assembled board, viewed from the THT component side._

<img width="749" height="569" alt="image" src="https://github.com/user-attachments/assets/1ea3d107-fe8c-4760-930e-16a060001f1e" />
_Fig. 2 Visualization of the circuit’s operating principle._
## Summary
The circuit works as expected, which means the components were mounted on the board correctly. Designing the board properly in EAGLE significantly makes the later assembly easier. During the measurements, it was concluded that it would be good to use 2 identical potentiometers in order to be able to set equal switching times.
