# 🚀 Atelier JS n°2 — Programmation Orientée Objet & Structures avancées

![Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Atelier%202%20JS&fontSize=40&fontAlign=center)

Cet atelier approfondit la **programmation orientée objet (POO)** en JavaScript à travers plusieurs cas pratiques : véhicules, personnes, vecteurs, blog, et gestion de données via `Set`, `Map` et `localStorage`.

---

## 🧠 Objectifs pédagogiques

🎯 Maîtriser les concepts suivants :

- Création et héritage de classes
- Encapsulation et surcharge
- Utilisation de `Set`, `Map` et `localStorage`
- Interaction DOM + JSON
- Sérialisation d’objets
- Structuration des données en mémoire

---

## 🗂️ Contenu par exercice

### ✅ Exercice 1 : Héritage entre classes (Voitures)

```js
class Voiture {
  static Trier(Liste) { Liste.sort((a, b) => a.annee - b.annee); }
  constructor(model, marque, annee, type, carburant) { ... }
  afficher() { console.log(...); }
}
```

> Mise en œuvre de l’héritage via `Hyundai`, `Ford`, surcharge de méthodes, et méthode statique.

---

### ✅ Exercice 2 : Représentation des personnes

```js
class Personne { constructor(nom, age) {...} }
class Etudiant extends Personne { ... }
class Professeur extends Personne { ... }
```

> Affichage personnalisé, tri de tableaux d’objets, gestion de classes métiers.

---

### ✅ Exercice 3 : Objets mathématiques

```js
class Vecteur2D { additionner(v) { ... } }
class Rectangle { surface() { ... } }
class Carre extends Rectangle { ... }
```

> Implémentation de la POO pour des formes géométriques : vecteurs, rectangles, segments.

---

### ✅ Exercice 4 : Mini Blog (HTML + Classes JS)

**Version DOM interactive avec `localStorage` :**

```js
class Post {
  toHTML() {
    return `
      <div class="post">
        <h3>${this.title}</h3>
        <p>${this.content}</p>
        <small><i>by ${this.author.name}</i></small>
      </div>`;
  }
}
```

---

## 📸 Capture d’écran – Mini Blog

> Interface de saisie et affichage dynamique des posts :

![image](https://github.com/user-attachments/assets/f114cb4c-383b-4bdd-886d-dea6752c7ffe)

---

### ✅ Exercice 5 : Manipulation de données (Array, Set, Map)

#### 📚 Tableau dynamique

```js
let books = ["Antigone", "Les Misérables"];
books.push("Le Petit Prince");
books.shift();
```

#### 🧠 Sets

```js
let Categories = new Set(["Fiction", "Science"]);
Categories.add("Philosophie");
Categories.delete("Histoire");
```

#### 🗺️ Maps

```js
let Borrows = new Map();
Borrows.set("Antigone", "Anas");
Borrows.delete("Antigone");
```

---

## 📎 Fichiers inclus

- `Exercice1.js` – Héritage & polymorphisme automobile  
- `Exercice2.js` – Modèle personne (objet & class)  
- `Exercice3.js` – Vecteurs, figures géométriques  
- `Exercice4V1.html` + `Exercice4V2.js` – Blog local interactif  
- `Exercice5.js` – Collections JS (`Set`, `Map`, `Array`)  

---

## ✍️ Auteur

**👤 Fadi AICH**  
🎓 Étudiant ingénieur en cybersécurité | 🧠 Passionné d’ethical hacking  
🔗 [GitHub](https://github.com/Fadi-AICH)

---

## ✨ Citation Dev du jour

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

> *"Un bon objet est un monde qui se suffit à lui-même, mais qui coopère avec tous les autres."*
