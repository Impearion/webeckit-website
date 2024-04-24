# **Webseite WeBeckIT**
# Inhaltsverzeichnis:
## 1. Projektbeschreibung und Konzept
Es soll eine Webseite für ein IT-Unternehmen entwickelt werden, welches sich auf Web-Entwicklung und IT-Dienstleistungen spezialisiert. Die Entwicklung teilt sich in mehrere Bereiche auf: Web-Design, Web-Entwicklung und Web-Security.

Die Webseite wird das Aushängeschild des Unternehmen, es soll die Reichweite erhöhen und damit neue potenzielle Kunden gewinnen. 

### 1.1. Zielgruppe
Die Zielgruppe des Unternehmens und der Website sind kleinere Unternehmen und Startups die sich im DACH Bereich oder in der EU befinden. Deshalb muss sie  Professionalität und Sicherheit ausstrahlen. 

## 2. Design
Das Design soll modern, simple, sicher und professionell wirken. 

### 2.1. Farbschema
Das Farbenschema ist an das Logo angelehnt. Die Primärfarben sind Blau und Violet, als Sekundärfarben werden derren Abstufungen sowie Weiß und Schwarz verwendet.

### 2.2. Typografie
#### 2.2.1 Font
Als Font wird eine serifenlose Schrift nämlich Poppins verwendet, da eine serifenlose Schrift besser zu einem IT-Unternehmen passt.

Die größe der Paragraphen ist 18px, welches größer als der Standard von 16px ist. Durch "Whitespacing" und der Reduzierung von unnötigen Text wird der Lesefluss verbessert.

Als Schriftfarbe wurde sich für Schwarz entschieden, damit es leichter und besser lesbar ist wird #1B2C37 verwendet.

| Element | Größe | Line-height | Farbe   |
|---------|-------|-------------|---------|
| p       | 18 px | 1.4         | #1B2C37 |
| h1      | 54 px | 1.6         | #1B2C37 |
| h2      | 44 px | 1.6         | #1B2C37 |
| h3      | 38 px | 1.6         | #1B2C37 |
| h4      | 30 px | 1.6         | #1B2C37 |
| h5      | 26 px | 1.6         | #1B2C37 |
| h6      | 21 px | 1.6         | #1B2C37 |

#### 2.2.2. Whitespacing
Der Abstand links und rechts vom Content beläuft ist jeweils ca. 12vw. <br>
Der vertikale Abstand zwischen den Elementen ist ca. 16vh.

Diese Abstände ermöglicht einen guten Lesefluss sowie einer einfacheren Zuteilung des Contents.

## 3. Struktur der Webseite
Die Webseite besteht aus folgenden Seiten: 
- Homepage
- Blog
- Leistungen
    - Web-Entwicklung
    - IT-Dienstleistungen
- Kontakt

### Navigation
Die Navigation ist fixiert oben und nimmt den ganzen Bereich von links nach rechts ein. Auf der linken Seite befindet sich das Logo und rechts die Navigation (dropdown) sowie ein Icon um die Sprache von Deutsch auf Englisch zu stellen.

### Hero
Jede Seite hat einen Hero, mit einer jeweiligen Überschrift. Damit weiß der Besucher immer wo er sich befindet. Unter der Überschrift sind Links die auf die Themenbereiche dieser Seite verweisen. Rechts neben diesem Bereich ist eine Illustration positioniert, um den Hero einen flavor zu geben.

### Footer
Der Footer ist simple aufgebaut. Logo, Kurzbeschreibung, Sitemap, CAT (Call to Action), Impressum, DSGVO und Copyright beinhaltet dieser. 

### 3.2. Homepage
Die Homepage dient dazu den Besuchern der Webseite grundlegende Informationen über das Unternehmen sowie derren Dienstleistungen vorzustellen. Ein CAT soll die User aufrufen auf die Web-Entwicklungs- oder IT-Dienstleistungsseite zu gehen. Mit einem Porftfolio werden die Fähigkeiten des Unternehmens noch einmal unterstrichen. 

### 3.3. Blog
Die Hauptaufgabe des Blogs ist den SEO Score durch Backlinks zu erhöhen. Es sollen monatlich neue Beiträge erscheinen die jeweils über Web-Entwicklung oder IT-Dienstleisungen handeln. Darüber hinaus dient dieser Blog als wertvolle Wissensquelle, die es sowohl Kunden als auch anderen Entwicklern ermöglicht, sich neues Wissen anzueignen.

### 3.4. Web-Entwicklung
Es werden detalierte Informationen angezeigt. Angefangen von den Vorteilen einer eigenen Webseite bis hin zur Erklärungen von Webhosting und Co.

Besucher sollen informiert werden, die herangehensweise der Entwicklung der Webseite nahegebracht werden und welche Funktionen auf der Webseite hinzugefügt werden können. 

Da es einen universeller Fixpreis in der Web-Entwicklung nicht gibt und der Kunde sich trotzdem preislich ein Bild machen will, wird ein Kostenrechner hinzugefügt. Mit diesem kann ein grober Preis ermittelt werden. <br>
Der Kunde füllt ein Formular aus und wählt im Rechner was er haben will und dies wird dann an das Unternehmen per Mail weitergeleitet. Dadurch wird es für das Unternehmen einfacher, einen maßgeschneiderten Preis für jedes Projekt festzulegen. 

### 3.5. IT-Dienstleistungen
- Hier werden Services wie Backup-Systeme, Netzwerkaufbau und ähnliches angeboten. 

- Mit einem Kontaktformular kann der Kunde sich mit dem Unternehmen in Verbindung setzen.

### 3.6. Kontakt
- Ein Kontaktformular mit dem sich Kunden mit dem Unternehmen in Kontakt treten können.

## 4. Technische Aspekte
### 4.1. E-Mails
E-Mails werden durch die Library PHPMailer versendet. 

### 4.2. Bots
Die Webseite wird mit Google reCAPTCHA v3 geschützt um sicherzustellen, dass Daten wie E-Mail Adressen nicht von web scraper ausgelesen werden können.

### 4.3. Cloudflare
Cloudflare wird als CDN (Content Delivery Network) verwendet um sicherzustellen das die Webseite auf der ganzen Welt schnell aufgerufen werden kann. Ein zusätzlicher Vorteil von der Verwendung von Cloudflare ist der DDoS-Schutz.

### 4.4. Sprachen
Die Webseite wird in HTML, CSS, JavaScript und PHP geschrieben. 







