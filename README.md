<h1 align="center">🛠️ Auto Maintenance Script</h1>
<p align="center">
  <b>Automatyzacja podstawowych zadań administracyjnych w Ubuntu</b> 🚀<br>
  <i>Projekt w Bashu z backupem, logowaniem i czyszczeniem systemu</i>
</p>

---

## ✨ Funkcje
✅ Aktualizacja pakietów systemowych  
✅ Usuwanie zbędnych pakietów i czyszczenie pamięci podręcznej  
✅ Tworzenie kopii zapasowej wybranego katalogu (`~/Documents`)  
✅ Zapisywanie logów z wykonanych operacji  

---

## 📂 Struktura projektu

| Plik / Folder          | Opis                                      |
|-------------------------|-------------------------------------------|
| `auto_maintenance.sh`  | Główny skrypt automatyzacji w Bashu        |
| `backup/`              | Folder, w którym zapisywane są kopie       |
| `logs/`                | Folder z logami systemowymi               |
| `.gitignore`           | Ignoruje backupy i logi w repozytorium     |
| `README.md`            | Dokumentacja projektu                     |


## 🚀 Jak uruchomić

1️⃣ **Pobierz repozytorium** lub skopiuj pliki projektu.  
2️⃣ **Nadaj uprawnienia** do uruchomienia skryptu:
```
chmod +x auto_maintenance.sh
```
3️⃣ Uruchom skrypt:
```
./auto_maintenance.sh
```
---

## 🔍 Jak działa skrypt

📦 Aktualizacja systemu – ```sudo apt update && sudo apt upgrade -y```
🧹 Czyszczenie systemu – ```sudo apt autoremove -y && sudo apt autoclean```
📂 Backup – spakowanie - ~/Documents do backup/ w formacie .tar.gz
📝 Logi – zapis przebiegu działań w logs/activity.log

---

## 🧰 Technologie i narzędzia:
🐧 Linux (Ubuntu 22.04)
💻 Bash
📦 APT
📜 tar

---

## 🚧 Możliwe rozszerzenia:
⏱️ Automatyczne uruchamianie przez cron
📧 Wysyłanie logów na e-mail
📁 Backup wielu katalogów
⚙️ Parametry w wierszu poleceń (np. wybór katalogu do backupu)

<p align="center"> ✍️ Autor: <b>Kaes04</b> 📅 Rok: 2025 </p> 
