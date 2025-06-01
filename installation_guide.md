# 📱 Quiz Egzaminacyjny - Instrukcja instalacji PWA

## 🚀 Co otrzymujesz:

✅ **Aplikację działającą offline** - po pierwszym załadowaniu  
✅ **Instalację jak prawdziwa aplikacja** na telefonie i komputerze  
✅ **Wszystkie 50 pytań** z Twojego dokumentu już wbudowane  
✅ **Losowe pytania** - za każdym razem inna kolejność  
✅ **Statystyki postępu** - widzisz ile pytań już zrobiłeś  

---

## 💻 **INSTALACJA NA WINDOWS:**

### Opcja 1: Zwykłe użycie
1. Zapisz pierwszy plik jako `index.html` 
2. Kliknij dwukrotnie - otworzy się w przeglądarce
3. Gotowe! Możesz już używać

### Opcja 2: Instalacja jako PWA
1. Zapisz wszystkie 3 pliki w tym samym folderze:
   - `index.html` (główny plik aplikacji)
   - `manifest.json` (konfiguracja PWA)
   - `sw.js` (service worker)

2. Otwórz `index.html` w **Chrome** lub **Edge**

3. W pasku adresu pojawi się ikona instalacji (+) - kliknij ją

4. Kliknij **"Zainstaluj"**

5. Aplikacja zostanie zainstalowana jak program - znajdziesz ją w menu Start!

---

## 📱 **INSTALACJA PWA NA ANDROID (KROK PO KROKU):**

### **Metoda 1: Przez Google Drive (ZALECANA)**

1. **Wgraj pliki na Google Drive:**
   - Otwórz Google Drive na komputerze
   - Utwórz nowy folder "Quiz"
   - Wgraj wszystkie 3 pliki (`index.html`, `manifest.json`, `sw.js`)

2. **Otwórz na telefonie:**
   - Otwórz Google Drive na telefonie
   - Znajdź folder "Quiz"
   - Kliknij na `index.html`
   - Wybierz **"Otwórz w przeglądarce"** lub **Chrome**

3. **Zainstaluj PWA:**
   - W Chrome kliknij **3 kropki** (menu)
   - Wybierz **"Dodaj do ekranu głównego"**
   - Potwierdź nazwę aplikacji
   - **Gotowe!** Ikona pojawi się na ekranie głównym

### **Metoda 2: Przez lokalny serwer**

1. **Na komputerze uruchom prosty serwer:**
   ```bash
   # W folderze z plikami:
   python -m http.server 8000
   # LUB
   npx serve
   ```

2. **Na telefonie:**
   - Znajdź adres IP komputera (np. 192.168.1.100)
   - W Chrome wejdź na `http://192.168.1.100:8000`
   - Menu Chrome → "Dodaj do ekranu głównego"

### **Metoda 3: Przez hosting**

1. **Wgraj pliki na darmowy hosting:**
   - GitHub Pages
   - Netlify
   - Vercel

2. **Na telefonie otwórz link w Chrome**

3. **Zainstaluj jak w Metodzie 1**

---

## ⚡ **NAJSZYBSZY SPOSÓB - tylko HTML:**

Jeśli chcesz **od razu zacząć** bez instalacji PWA:

1. Skopiuj kod z pierwszego pliku (index.html)
2. Wklej do dowolnego edytora tekstu
3. Zapisz jako `quiz.html` 
4. Wyślij sobie mailem lub przez komunikator
5. Otwórz na telefonie w przeglądarce

**Uwaga:** Bez plików PWA nie będzie działać offline ani się instalować.

---

## 🔧 **Rozwiązywanie problemów:**

### **Nie mogę zainstalować PWA:**
- ✅ Upewnij się, że masz wszystkie 3 pliki w tym samym folderze
- ✅ Otwieraj przez **Chrome** (nie przez domyślną przeglądarkę)
- ✅ Sprawdź czy pliki mają prawidłowe rozszerzenia (`.html`, `.json`, `.js`)

### **Nie widzę opcji "Dodaj do ekranu głównego":**
- ✅ Spróbuj odświeżyć stronę (F5)
- ✅ Sprawdź czy wszystkie pliki są w tym samym miejscu
- ✅ Upewnij się, że używasz Chrome (nie Firefox/Safari)

### **Aplikacja nie działa offline:**
- ✅ Pierwszy raz otwórz z internetem (żeby pobrać pliki)
- ✅ Sprawdź czy service worker się załadował (F12 → Application → Service Workers)

---

## 🎯 **Jak używać:**

1. **Start:** Kliknij jeden z trybów (quiz uruchamia się od razu)
2. **Tryb nauki:** Odpowiedzi pokazują się automatycznie, nawiguj strzałkami  
3. **Tryb quiz:** Kliknij "Pokaż odpowiedź" → "Następne pytanie"
4. **Skróty:** Strzałki lewo/prawo w trybie nauki, Enter/Spacja w quizach

---

## 💡 **Wskazówki:**

- **Najłatwiej:** Metoda przez Google Drive
- **Najszybciej:** Tylko HTML bez PWA
- **Najlepiej:** Pełna instalacja PWA z wszystkimi funkcjami
- **Problem?** Spróbuj najpierw przez Google Drive

---

**Powodzenia na egzaminie! 🎓**