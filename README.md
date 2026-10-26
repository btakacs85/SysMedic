# SysMedic

**Windows 10/11 mentő, javító és diagnosztikai eszköz rendszergazdáknak** — egyetlen exe, telepítés nélkül.
Magyar és angol felülettel, beépített súgóval.

*A Windows 10/11 rescue, repair and diagnostics toolkit for IT technicians — a single portable exe, Hungarian and English UI.*

## Mit tud

- **Kezdőlap:** állapotpontszám (0–100) és javaslatok egy-egy javító gombbal (lemez, szabad hely, kékhalál, frissítések…).
- **Mentés:** felhasználói adatok és programlista mentése tömörített fájlba, visszaállítással; illesztőprogramok mentése.
- **Illesztőprogramok:** hibás eszközök, frissítések a Windows Update-ről és a gép gyártójától (Dell / HP / Lenovo).
- **Programok:** frissítés és telepítés WinGettel; **automatikus indítás** áttekintése.
- **Lemezállapot:** SMART-adatok, előzmény, önteszt, USB-kapcsolat; **sebességmérés** (internet és lemez).
- **Szenzorok és fogyasztás:** hőmérsékletek, ventilátorok, terhelés, energiafogyasztás grafikonon.
- **Rendszerinfó:** processzor, memória, videokártya, monitor, tárolók, hálózat — részletesen.
- **Stabilitásteszt** (processzor, videokártya, memória) és **összeomlások** elemzése (kékhalál, okozó driver).
- **Rendszerjavítás:** DISM, SFC és társai elakadás-figyeléssel; **nyomtatómegosztás** javítása (visszaállítható).
- **Tisztítás** és **licenc** információ.
- **Önfrissítés:** naponta megnézi, van-e új verzió, és kattintásra frissíti magát.

## Letöltés

A legfrissebb **`SysMedic.exe`** a [Releases](../../releases/latest) oldalon. Egyetlen fájl, telepítés nélkül fut
(.NET Framework 4.8 — a Windows része). Rendszergazdai jogot kér, mert a javításokhoz és a szenzorokhoz ez kell.

## Biztonság

- A frissítést csak akkor telepíti, ha a kiadás leírója (`SysMedic-frissites.txt`) a kiadó titkos kulcsával van
  aláírva, és a letöltött exe mérete és SHA-256-ja egyezik vele. Így a rendszergazdai joggal futó programon keresztül
  más exe nem juthat a gépre.
- Az exe nincs kódaláíró tanúsítvánnyal aláírva, ezért a Windows SmartScreen (vagy egy céges víruskereső)
  figyelmeztethet.

---

Saját fejlesztés. A forráskód nincs nyilvánosan fent; ez a tároló a kiadásokat (Releases) hordozza.
