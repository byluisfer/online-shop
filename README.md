# UrbanVibes

- SQLite Datenbank
- Node.js Backend

# Installation

1. Module installieren wenn Sie nicht haben:
   `npm install`

2. Server starten:
   `node app.js`

Die Online Shop wird dann unter [http://localhost:3000/]

# Admin info

Um sich als Administrator anzumelden, verwenden Sie diese Daten:

- **Benutzername:** `admin`
- **Passwort:** `admin`

# Endpunkte

#### Registrierung

**URL:** `/register`
**Methode:** `POST`

#### Anmeldung

**URL:** `/login`
**Methode:** `POST`

#### Passwort zurücksetzen

**URL:** `/reset_password`
**Methode:** `POST`

#### Kategorien

  - **GET /categories**
  - **POST /categories**
  - **GET /categories/:id**
  - **PUT /categories/:id**
  - **DELETE /categories/:id**

### Produkte

  - **GET /products**
  - **POST /products**
  - **GET /products/:id**
  - **PUT /products/:id**
  - **DELETE /products/:id**

