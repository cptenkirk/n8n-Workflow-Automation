# Automatisierung mit zwei Formularstufen

###

Dieses Projekt zeigt, wie  Bewerbungsprozesse mit n8n und OpenForm automatisiert werden kann. Die Automatisierung läuft in zwei Formularstufen: Nach Formular 1 werden Kandidatendaten in einer PostgreSQL-Datenbank gespeichert, inklusiv einer SQL-Logik gegen Dupletten (statt Konflikten werden Updates ausgeführt), danach erfolgt ein Versand der E-Mail in der vom Kandidaten gewählten Sprache. In Formular 2 werden weitere Daten ergänzt, anschließend werden die vollständigen Profildaten an einen lokalen Open-Source-KI-Agenten (Ollama3.1:8b) übergeben, der HR sachlich eine Empfehlung gibt. Zum Abschluss werden Profildaten in ein JSON umgewandelt und zusammen mit dem Lebenslauf als PDF verarbeitet.

## Formular 1 Workflow

<img width="1916" height="929" alt="image" src="https://github.com/user-attachments/assets/70acc29b-4fad-4d81-94dd-ac9cf08b231c" />

## Formular 2 Workflow

<img width="1767" height="939" alt="image" src="https://github.com/user-attachments/assets/65fea462-71a0-45b3-8bb2-93de83e171a1" />


