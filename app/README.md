**Hur kopplas CSS in i React?**
import './App.css' + className\
**Hur ser användaren vilka todos som är klara? Peka på klassen i din CSS**
i CSS har .completed den line-through attributet. Om todon är klar och man clickar på Klar, gör funktionen i li elementet att .completed är true och får då ett streck genom det.\
**Tre steg när stil “inte tar”** spara → import → className → Inspect

**Felsökning**
1. Har du sparat klassen i CSS?\
2. Har du lagt till ternary i JSX och finns stavfel?\
3. Har du gjort import i JSX?
