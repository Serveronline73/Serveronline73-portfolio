# Styling4You  
**Digitale Salon- & Terminmanagement-App**  
  
---  
  
## Projektüberblick  
**Styling4You** ist eine mobile Anwendung für Friseursalons und Beauty-Studios zur digitalen Verwaltung von Terminen, Services und Kundenkommunikation.  
Ziel ist es, manuelle Prozesse zu reduzieren und sowohl für Betriebe als auch für Kunden eine klare, effiziente Lösung bereitzustellen.  
  
> Der Quellcode dieses Projekts ist bewusst **privat**.  
> Diese Seite beschreibt **Konzept, Architektur und Mehrwert**.  
  
# Screenshots

![Startscreen](../simulator_screenshot_0EE7AC43-443C-4422-8F15-ABC9B0BAE835.png)  

![Salon-Besitzer-Login](../simulator_screenshot_3C98232C-324B-4859-A7F8-915B569668C1.png)  

![Salon-Registrierung](../simulator_screenshot_D8A8D842-E811-4282-92F0-EB11BD5E8F5B.png)  

![Kunden-Login](../simulator_screenshot_EDD041FF-235A-4B5B-B161-0BDDE7DB59BF.png) 
---  
## Screenshots

> Klick auf ein Bild öffnet die Ansicht in voller Grße.

---

### Dashboard & Schnellzugriff (Salon)

<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_476A9F07-93E8-49B0-9412-259F6CB875EB.png">
  <img src="../simulator_screenshot_476A9F07-93E8-49B0-9412-259F6CB875EB.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_19BC4F29-DFD5-43CB-875B-A7E99DE84010.png">
  <img src="../simulator_screenshot_19BC4F29-DFD5-43CB-875B-A7E99DE84010.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_30ADD803-F438-4510-B4F3-BEBD144F1790.png">
  <img src="../simulator_screenshot_30ADD803-F438-4510-B4F3-BEBD144F1790.png" width="260" />
</a>

---

### Einstellungen & Salonverwaltung

<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_B721A631-A51C-4D47-B19F-7BAD7CC9AD3F.png">
  <img src="../simulator_screenshot_B721A631-A51C-4D47-B19F-7BAD7CC9AD3F.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_81214B57-F3D1-4528-A898-20806B5512F0.png">
  <img src="../simulator_screenshot_81214B57-F3D1-4528-A898-20806B5512F0.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_027208C3-B9D8-462C-B890-9D9AC6752FC7.png">
  <img src="../simulator_screenshot_027208C3-B9D8-462C-B890-9D9AC6752FC7.png" width="260" />
</a>

---

### Öffnungszeiten & Kunden-Informationen

<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_0AEC9F54-FF21-4094-93CA-DC51FB622E05.png">
  <img src="../simulator_screenshot_0AEC9F54-FF21-4094-93CA-DC51FB622E05.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_2EF9B494-C331-47D6-A0DF-6BB94CD60BB6.png">
  <img src="../simulator_screenshot_2EF9B494-C331-47D6-A0DF-6BB94CD60BB6.png" width="260" />
</a>

---

### Mitarbeiterverwaltung & Skills

<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_DD1044A6-057B-4E6F-807D-597D587FA59A.png">
  <img src="../simulator_screenshot_DD1044A6-057B-4E6F-807D-597D587FA59A.png" width="260" />
</a>

---

### Terminverwaltung & Kalender

<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_0EE7AC43-443C-4422-8F15-ABC9B0BAE835.png">
  <img src="../simulator_screenshot_0EE7AC43-443C-4422-8F15-ABC9B0BAE835.png" width="260" />
</a>
<a href="https://github.com/Serveronline73/Serveronline73-portfolio/blob/main/simulator_screenshot_EDD041FF-235A-4B5B-B161-0BDDE7DB59BF.png">
  <img src="../simulator_screenshot_EDD041FF-235A-4B5B-B161-0BDDE7DB59BF.png" width="260" />
</a>

  
## Ausgangslage / Problemstellung  
Viele Salons arbeiten weiterhin mit:  
- telefonischer Terminvergabe  
- manueller Planung (Kalender, Zettel, WhatsApp)  
- fehlender Transparenz für Kunden  
- hohem Zeitaufwand für Organisation  
  
Das führt zu:  
- unnötiger Arbeitsbelastung  
- Terminfehlern  
- eingeschränkter Skalierbarkeit  
  
---  
  
## Zielsetzung  
Entwicklung einer **zentralen, mobilen Lösung**, die:  
- Terminverwaltung vereinfacht  
- Kundenkommunikation automatisiert  
- für Salons sofort nutzbar ist  
- für Endkunden intuitiv bleibt  
  
---  
  
## Lösungskonzept  
Styling4You bündelt alle relevanten Abläufe in einer App:  
  
- Digitale Terminbuchung  
- Service- & Zeitlogik pro Salon  
- Rollenbasiertes System (Salon / Kunde)  
- Direkte Informations- & Terminbenachrichtigungen  
  
---  
  
## Zentrale Funktionen  
  
### Salon-Seite  
- Salon-Profil mit Logo & Beschreibung  
- Individuelle Service-Liste inkl. Dauer  
- Terminübersicht & Statusverwaltung  
- Push-Benachrichtigungen an Kunden  
- Foto-Galerie zur Präsentation  
  
### Kunden-Seite  
- Einfache Terminbuchung  
- Übersicht über eigene Termine  
- Automatische Benachrichtigungen  
- Transparente Service-Informationen  
  
---  
  
## Benutzerrollen & Zugriff  
- **Saloninhaber**  
  - Verwaltung von Services, Terminen & Inhalten  
- **Kunde**  
  - Buchung & Einsicht eigener Termine  
  
Zugriffe sind klar getrennt und rollenbasiert aufgebaut.  
  
---  
  
## Mehrwert  
  
### Für Salons  
- Zeitersparnis durch weniger Telefonate  
- Strukturierte Planung  
- Professioneller Außenauftritt  
- Skalierbar für wachsende Betriebe  
  
### Für Kunden  
- Flexible Terminbuchung  
- Klare Übersicht  
- Direkte Kommunikation  
  
---  
  
## Technischer Ansatz (High Level)  
- **Flutter** – plattformübergreifend (iOS & Android)  
- **Firebase**  
  - Authentifizierung  
  - Datenbank (strukturierte Salon- & Termindaten)  
  - Storage für Medien  
- **Rollenbasierte Architektur**  
- Fokus auf wartbaren, modularen Code  
  
---  
  
## Aktueller Status  
- Konzept & Kernfunktionen definiert  
- UI/UX-Struktur ausgearbeitet  
- Architektur & Rollenmodell festgelegt  
  
---  
  
## Geplante Weiterentwicklung  
- Erweiterte Statistiken für Salons  
- Mehrsprachigkeit  
- Erweiterte Benachrichtigungslogik  
- Optimierung für größere Salonketten  
  
---  
  
## Lernergebnisse & Fokus  
Dieses Projekt zeigt:  
- strukturiertes Produktdenken  
- saubere Trennung von Rollen & Verantwortlichkeiten  
- Fokus auf reale Business-Probleme  
- nachhaltige Architektur statt kurzfristiger Lösungen  
  
---  
  
## Einsatz im Bewerbungsprozess  
Dieses Projekt dient als:  
- Gesprächsgrundlage in Interviews  
- Beispiel für selbstständige Projektumsetzung  
- Nachweis für Architektur- & Produktverständnis 
