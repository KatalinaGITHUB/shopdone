# 🛍️ Shopdone – Magazin Online Modern (PHP 8.3)

**Shopdone** este o aplicație ecommerce construită cu cele mai recente standarde PHP, focusată pe securitate, performanță și experiență modernă pentru utilizator.

---

## 🚀 Funcționalități

- ✅ Arhitectură MVC conform PSR-4, încărcare automată via Composer
- ✅ PHP 8.3 modern cu `declare(strict_types=1)` și:
  - Promovarea proprietăților în constructor
  - Expresii `match`, `readonly`, etc.
- ✅ Autentificare securizată:
  - Hashing parole cu **Argon2ID**
  - Autentificare 2FA (Google Authenticator + cod QR)
  - Protecție CSRF, XSS, SQL Injection
- ✅ Gestionare sesiuni & validare date robuste
- ✅ Căutare AJAX cu debounce + UI responsive
- ✅ Sistem de cupoane (prima și a 10-a comandă)
- ✅ Programare livrare Fan Curier / Poșta Română
- ✅ UI responsive cu Tailwind CSS + Bootstrap 5 carusel
- ✅ Template-uri `.tpl` via View Engine (Twig ready)

---

## ⚙️ Cerințe

- PHP >= 8.3
- Composer
- MySQL sau MariaDB
- Apache/Nginx (cu `mod_rewrite` activ dacă e cazul)

---

## 🔧 Instalare locală

```bash
git clone https://github.com/KatalinaGITHUB/shopdone.git
cd shopdone

composer install
cp .env.example .env
php -S localhost:8000 -t public
