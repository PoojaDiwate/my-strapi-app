# Strapi Project – Assignment

## Overview

This is a sample Strapi project created as part of the assignment. It demonstrates:

* Running Strapi locally
* Admin Panel usage
* Creating a content type
* Adding sample content

## Steps Followed

### 1. Setup Project

```
npx create-strapi-app@latest my-strapi-app --quickstart
```

### 2. Run Strapi

```
cd my-strapi-app
npm run develop
```

* Access Admin Panel: [http://localhost:1337/admin](http://localhost:1337/admin)
* Register admin user

### 3. Create Content Type

* Content-Type Builder → Create `Blog`
* Fields:

  * `title` → Text
  * `description` → Rich Text
* Save and restart Strapi
* Add sample entries in Content Manager

### 4. GitHub Setup

```
git init
git add .
git commit -m "Initial Strapi setup with Blog content type"
git branch -M Pooja
git remote add origin https://github.com/PoojaDiwate/my-strapi-app.git
git push -u origin Pooja
```

### 5. Project Structure

* `src/api/` → contains content types
* `config/` → project configurations
* `database/` → SQLite DB (default)
* `public/` → uploaded files
* `package.json` → scripts & dependencies

## Notes

* Run `npm run develop` to start the server locally whenever needed.
* API tokens are **not required** for this assignment.

