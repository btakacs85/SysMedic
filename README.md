# SysMedic

**[Magyar](#magyarul) · [English](#english)**

## Magyarul

**Windows 10/11 mentő, javító és diagnosztikai eszköz rendszergazdáknak** — egyetlen exe, telepítés nélkül.
Magyar és angol felülettel, beépített súgóval.

### Mit tud

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
- **Önfrissítés:** naponta megnézi, van-e új verzió, és kattintásra frissíti magát; az újdonságokat a program nyelvén mutatja.

### Letöltés

A legfrissebb **`SysMedic.exe`** a [Releases](../../releases/latest) oldalon. Egyetlen fájl, telepítés nélkül fut
(.NET Framework 4.8 — a Windows része). Rendszergazdai jogot kér, mert a javításokhoz és a szenzorokhoz ez kell.

### Biztonság

- A frissítést csak akkor telepíti, ha a kiadás leírója (`SysMedic-frissites.txt`) a kiadó titkos kulcsával van
  aláírva, és a letöltött exe mérete és SHA-256-ja egyezik vele. Így a rendszergazdai joggal futó programon keresztül
  más exe nem juthat a gépre.
- Az exe nincs kódaláíró tanúsítvánnyal aláírva, ezért a Windows SmartScreen (vagy egy céges víruskereső)
  figyelmeztethet.

Saját fejlesztés. A forráskód nincs nyilvánosan fent; ez a tároló a kiadásokat (Releases) hordozza.

---

## English

**A Windows 10/11 rescue, repair and diagnostics toolkit for IT technicians** — a single exe, no installation.
Hungarian and English interface, built-in help.

### What it does

- **Home:** health score (0–100) and recommendations, each with a fix button (disk, free space, blue screens, updates…).
- **Backup:** user data and the list of installed apps into a compressed file, with restore; driver backup.
- **Drivers:** faulty devices, updates from Windows Update and from the PC maker (Dell / HP / Lenovo).
- **Apps:** update and install with WinGet; overview of **startup** items.
- **Disk health:** SMART data, history, self-test, USB connection; **speed tests** (internet and disk).
- **Sensors and power:** temperatures, fans, load, power draw on charts.
- **System info:** processor, memory, graphics card, monitor, drives, network — in detail.
- **Stability test** (processor, graphics card, memory) and **crash** analysis (blue screens, the driver behind them).
- **System repair:** DISM, SFC and friends with stall detection; **printer sharing** repair (reversible).
- **Cleanup** and **licence** information.
- **Self-update:** checks for a new version daily and updates itself with one click; shows the release notes in the program's language.

### Download

The latest **`SysMedic.exe`** is on the [Releases](../../releases/latest) page. A single file that runs without installation
(.NET Framework 4.8 — part of Windows). It asks for administrator rights, because repairs and sensors need them.

### Security

- An update is installed only if the release descriptor (`SysMedic-frissites.txt`) is signed with the publisher's
  private key, and the downloaded exe's size and SHA-256 match it. So no other exe can reach the PC through a program
  running with administrator rights.
- The exe is not signed with a code-signing certificate, so Windows SmartScreen (or a corporate antivirus) may warn.

Personal project. The source code is not public; this repository hosts the releases.
