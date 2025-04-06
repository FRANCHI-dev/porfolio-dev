# Portfolio Personnel

Ce projet est mon portfolio personnel développé avec Next.js et hébergé sur un serveur VPS.

## Étapes pour démarrer le projet

1. **Création du dépôt sur GitHub**

   - Création d’un dépôt vide nommé `porfolio_vps` sur mon compte GitHub personnel `andref360`
   - Ajout d’un fichier `.gitignore` et d’une licence MIT (version française et anglaise)

2. **Clonage du dépôt via GitHub Desktop**

   - Connexion à mon compte GitHub dans GitHub Desktop
   - Clonage du dépôt localement dans le dossier `portfolio_vps`
   - Ouverture du projet dans Visual Studio Code

3. **Initialisation du projet avec Next.js**

   - Installation avec la commande :
     ```bash
     npx create-next-app@latest .
     ```
   - Configuration choisie :
     - ✅ TypeScript
     - ✅ ESLint
     - ❌ Tailwind CSS
     - ✅ Dossier `src/`
     - ✅ App Router (`/app`)
     - ✅ Alias `@/*`

4. **Structure du projet**

   - Dossiers créés pour les pages : `accueil`, `cv`, `contact`, `mentions-légales`
   - Dossier `components` pour Header, Footer, Boutons, Images
   - Dossier `public/` pour les ressources : `images/`, `fonts/`

5. **Ajout de Framer Motion**
   - Installation avec :
     ```bash
     npm install framer-motion
     ```
   - Création d’un composant animé de base (`FadeIn`) pour les entrées douces
   - Framer Motion sera utilisé pour les animations globales (pages, boutons, transitions)

---

🧪 **Étapes suivantes prévues** :

- Mise en place du layout global (`layout.tsx`) avec Header et Footer
- Intégration de la typographie Orbitron localement
- Développement des premières sections visuelles du portfolio
