# IU-Fraud-Detection-Model
Fraud Detection Model for Bank and Insurance Data

Ziel der Studie ist es ein numerisches Modell zur Identifizierung von bekannten Fraud-Mustern in einem vorgegebenen Datensatz zu entwickeln. Dazu sollen zunächst aus unterschiedlichen Datensätzen (von Banken und Versicherungen) bekannte 
Muster extrahiert werden, welche es erlauben, Fraud-Muster zu definieren. Aus diesen Fraud-Mustern soll ein  Algorithmus entwickelt werden, der diese bekannten Muster in einem neuen Datensatz erkennt und dem Nutzer der Software Hinweise darüber vermittelt, ob es sich bei bestimmten Transaktionen um bekannte Frau-Muster handelt bzw. potentiell Fraud deklariert.

Dazu möchten wir im Kurs einerseits einen klassisch analytischen Ansatz verwenden, der erstmal einfach bekannte Fraud-Parameter zur Klassifizierung von Fraud nutzt, z.B. durch den Abgleich der Nutzerkonten mit den Transaktionsdaten. Die als Fraud bekannten Konten werden dann gespeichert und derart bei neuen Transaktionen Verdachtsfälle zur Prüfung deklariert. In einer Modellierung soll also ein neuer datensatz nach cden bekannten Kontendaten durchsucht werden.

Komplexere Modellierungen mit Vorhersagecharakter der Fraudwahrscheinlichkeiten bzw. der Einstufung als Fraud oder nicht, wird im Rahmen der ML Modelle Logistische Regression und SVM genutzt. Die in der Vorlesung gemeinsam entwickelten Source Codes sollen bei den Studenten Anwendung finden, insofern als das Modell selbst installiert und (in der Klausur) zur Abschätzung von Modellparametern genutzt werden soll.

