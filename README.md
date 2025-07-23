#  Product Price Comparison App – Microservices Final Project

Dies ist ein Full-Stack-Microservice-Projekt zur Preisvergleichsanwendung. Es wurde im Rahmen des IBM Full Stack Cloud Developer Kurses umgesetzt. Die Anwendung nutzt mehrere Microservices, die auf IBM Cloud Code Engine bereitgestellt sind.

##  Projektübersicht

Die Anwendung besteht aus drei Komponenten:

1. ** Produktservice (Python Flask)**  
   Bietet Produktinformationen über eine RESTful API.

2. ** Händlerpreisservice (Node.js Express)**  
   Gibt Händlerinformationen und Preise für ausgewählte Produkte zurück.

3. ** Frontend (HTML/CSS/JS)**  
   Kommuniziert mit den beiden Backends und visualisiert die Daten dynamisch per Dropdown und Preisanzeige.

---

##  Technologien & Tools

- IBM Cloud Code Engine
- REST APIs (Flask & Express)
- HTML, CSS, JavaScript (Axios)
- Git & GitHub
- Docker (für Builds)
- CI/CD über IBM Code Engine Builds

---

##  Deployment-URLs

> Hinweis: Diese URLs sind öffentlich über IBM Cloud Code Engine bereitgestellt.

-  Produkt-API: `https://prodlist.1y6lhjpo3fpx.us-south.codeengine.appdomain.cloud/`
-  Händler-API: `https://dealerdetails.1y6lhjpo3fpx.us-south.codeengine.appdomain.cloud/`
-  Frontend: `https://frontend.1y6lhjpo3fpx.us-south.codeengine.appdomain.cloud/`

---

##  Screenshots

| Ansicht                    | Screenshot-Datei              |
|---------------------------|-------------------------------|
| Git-Klon erfolgreich       | `git_clone.png`               |
| Geänderte index.html-URLs | `index_urlchanges.png`        |
| Frontend erfolgreich deployt | `frontend_deploy.png`      |
| Produktliste sichtbar      | `homepage.png`                |
| Einzelner Händlerpreis     | `product_dealer_price.png`    |
| Alle Händlerpreise         | `product_all_dealers_prices.png` |

---

##  Projektstruktur

