# LIVENT
**LIVENT (Live & Event)** - sebuah progressive web app yang menghadirkan referensi berbagai kegiatan yang dapat diikuti sesuai dengan interest user. Dilengkapi dengan informasi hingga artikel dokumentasi kegiatan yang telah berhasil terlaksana.

You can visit our development project here: <br>
<a href="https://mini-project-f-frontend.herokuapp.com/">Livent</a> <br>
Note: It's not a final release web, it's still under deveopment progress

# Development Guidelines (In Progress)

## 1. Project Initiation
---
```bash
# Change example.env to .env
mv example.env .env

# Install packages
npm install

# Create database
sequelize db:create

# Migrating the tables into database
sequelize db:migrate

# Seeding the default data
sequelize db:seed:all

# Run the dev script
npm run dev
```

## 2. Project Structure (Android)
---
```app
├── manifests
|   ├── AndroidManifest.xml
├── java
|   ├── com.krisnachy.livent
|   |   ├── MainActivity
├── res
|   ├── layout
|   |   ├── activity_main.xml
```

## 3. API Specification
---

Visit this link to see the full API Specifications. <br>
<a href="https://documenter.getpostman.com/view/12168381/Tz5qadAw">API</a>
