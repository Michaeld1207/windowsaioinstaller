<img src="https://www.geexer.nl/wp-content/uploads/2025/03/GEEXER_logo_2025_RGB_lichtblauw-scaled.png" alt="Geexer logo" style="height: 42px; vertical-align: middle; margin-right: 8px;">

#  Windows AIO Installer

Een PowerShell-script om de configuratie van Windows 11 te automatiseren. Deze tool helpt systeembeheerders en eindgebruikers om snel een nieuwe Windows-installatie op te zetten met veelgebruikte applicaties en instellingen.

Gemaakt door Michael Smith.

* * *

## ✨ Functies

### 👤 Gebruikersbeheer

- Nieuwe lokale gebruikersaccounts aanmaken
- Weergavenaam en wachtwoord instellen
- Hostnaam configureren
- Ingebouwde `sysadmin`\-gebruiker uitschakelen

### ⚙️ Windows Configuratie

- Windows activeren (Windows 10, 11, Server 2016, 2019, 2022, 2025)
- Regio-instellingen instellen (tijdzone, tijdsynchronisatie)
- "Ultimate Performance"-energiebeheer inschakelen
- ICMP-verkeer (ping) toestaan in de firewall
- Downloadsmap uitzonderen in Windows Defender
- Taakbalk links uitlijnen & zoekoptie als pictogram instellen
- Web Experience-apps verwijderen (nieuws, widgets, enz.)
- Geexer Wallpaper instellen als bureaubladachtergrond
### 📦 Software-installatie
- **Basisapps:**
		- 7-Zip,
		- Adobe Reader
		  - Google Chrome
		  - VLC
- **Optionele installatie van Office 365 Business**  
- **Chocolatey & Winget** ten behoeve van extra software repository
- Extra tools voor productiviteit, media en ontwikkeling  




### 🔄 Systeemupdates

- Windows Update via `PSWindowsUpdate`
- Winget-pakketten updaten (behalve PowerShell zelf)
- Chocolatey-pakketten updaten

* * *

## ✅ Vereisten

- Windows 11 (x64)
- PowerShell 7 of hoger
- Administratorrechten

* * *

## 📥 Installatie

1.  Download dit script of kloon de repository
2.  Sla het script op in een map (bijv. je Bureaublad)
3.  Open PowerShell 7+ als Administrator
4.  Navigeer naar de map met het script:

```powershell
cd $home/desktop
```

6.  Zet tijdelijk de uitvoering van scripts aan:

```powershell
Set-ExecutionPolicy Bypass -Scope Process
```

7.  Start het script, gerbuik de juiste versie:

```powershell
./windows-aio-installer_v0.0*.ps1
```

* * *

## 🧭 Gebruik

Het script toont een interactief menu met opties:

1.  Nieuwe gebruiker aanmaken
    
2.  Windows configureren (voor huidige gebruiker)
    
3.  Windows activeren
    
4.  Windows en apps updaten
    
5.  Sysadmin-gebruiker uitschakelen
    
6.  Afmelden
    
7.  Computer herstarten
    
8.  Extra persoonlijke apps installeren
    

Selecteer het gewenste nummer en volg de stappen op het scherm.

* * *

## 🧰 Inbegrepen software

### 📌 Basisapplicaties

- 7-Zip
    
- Adobe Acrobat Reader
    
- Google Chrome
    
- VLC Media Player
    

* * *

## 📄 Licentie

Dit project is gelicenseerd onder de MIT-licentie.

* * *

## 🙏 Dankwoord

- ExplorerPatcher
    
- Microsoft PowerToys
    
- Chocolatey
    
- Windows Package Manager (winget)
    

* * *

## ⚠️ Disclaimer

Dit script bevat functionaliteit om Windows te activeren. Zorg ervoor dat je over de juiste licenties beschikt voordat je deze functie gebruikt.
