# OnErp: ERP Client Management System - JavaFX

[![Java](https://img.shields.io/badge/Java-17-blue)](https://java.com)
[![JavaFX](https://img.shields.io/badge/JavaFX-20-deepskyblue)](https://openjfx.io)
[![IDE](https://img.shields.io/badge/IDE-IntelliJ_IDEA-black)](https://www.jetbrains.com/idea/)

Σύστημα διαχείρισης πελατολογίου και κινήσεων για γραφεία. Υλοποιημένο σε JavaFX με δυνατότητα **πολλαπλών καταχωρήσεων** και **πλήρες ιστορικό κινήσεων** ανά πελάτη. 

## Κύριες Λειτουργίες
- **Πελατολόγιο**:
  - Καταχώρηση νέων πελατών (Φυσικά/Νομικά Πρόσωπα)
  - Αναζήτηση με φίλτρα (ΑΦΜ, Επωνυμία, Κατηγορία)
- **Διαχείριση Κινήσεων**:
  - Πολλαπλές καταχωρήσεις ανά πελάτη (Συναλλαγές, Σημειώσεις, Έγγραφα)
  - Χρονολογικό ιστορικό με δυνατότητα αναζήτησης
- **Αναφορές**:
  - Εξαγωγή σε Excel/PDF (να γίνει)
  - Στατιστικά κινήσεων ανά πελάτη/χρονική περίοδο (να γίνει)

## Τεχνολογικό Stack
| Component       | Technology Used           |
|-----------------|---------------------------|
| Frontend        | JavaFX 20, Scene Builder  |
| Business Logic  | Java 17 (Records, Streams)|
| Data Storage    | SQLite (Embedded)         |
| ORM             | JDBC + Custom DAO Layer   |
| Reporting       | Apache POI (Excel)        |
| Build Tool      | Maven                     |

