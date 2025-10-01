# 🍣 TokyoGarden – System Restauracji Japońskiej

Full-stackowa aplikacja dla restauracji **TokyoGarden**, pozwalająca klientom na przeglądanie menu, rejestrację, logowanie i składanie zamówień.  
Projekt zawiera zarówno **backend w ASP.NET Core WebAPI**, jak i **frontend w Angularze**.

---

## ✨ Funkcje

### 👨‍🍳 Dla użytkownika
- Rejestracja i logowanie
- Profil użytkownika z możliwością edycji danych
- Podgląd menu restauracji (z kategoriami i alergenami)
- Koszyk i składanie zamówień
- Formularz kontaktowy

### 🛠️ Dla administratora
- Zarządzanie kategoriami
- Zarządzanie pozycjami menu
- Zarządzanie alergenami
- Podgląd zamówień

---

## 🖥️ Technologie

- **Frontend:** Angular 16 (standalone components, TypeScript, RxJS)  
- **Backend:** ASP.NET Core 7 (C#, EF Core, WebAPI, Swagger)  
- **Baza danych:** MS SQL Server  
- **Inne:**  
  - JWT / tokeny sesji (localStorage / sessionStorage)  
  - Proxy Angulara do komunikacji z API  
  - Entity Framework Core (migracje + seeding)  
