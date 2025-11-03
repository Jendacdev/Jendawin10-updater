# 🧩 Jenda Update System for Windows 10

> Neoficiální komunitní systém údržby a aktualizací Windows 10 po ukončení podpory (od října 2025).  
> Vytvořil **Jenda Tomášek (JendaSoft)** pro uživatele, kteří chtějí, aby jejich Windows 10 zůstaly bezpečné, rychlé a aktuální.

---

## 📦 Projekty

### 🔹 1️⃣ [Jenda Update Check Kit (2025.11)](releases/latest/download/JendaUpdate_Check_Kit_2025-11.zip)

Diagnostický nástroj, který zkontroluje, jestli je systém **Windows 10 22H2 (build 19045)** a klíčové komponenty aktuální.

#### ✅ Kontroluje
- Windows build 19045 (22H2)  
- Microsoft Defender signatury  
- Microsoft Edge (Chromium)  
- .NET Framework 4.8.1 a .NET Runtime 8.x  
- VC++ Redistributables 2015–2022 (x64/x86)  
- PowerShell 7 + WinGet  
- Firefox ESR (volitelně)

#### 🧰 Použití
```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\JendaCheck.ps1
# nebo s opravami:
.\JendaCheck.ps1 -Fix
