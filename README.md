# Appli piano Sophia

Petite app web pour apprendre le piano à un enfant : des notes colorées tombent sur un clavier arc-en-ciel (Do → Do).

- **Pas à pas** : la note attendue s'arrête sur la ligne, on avance quand elle est jouée.
- **En musique** : les notes défilent en rythme, avec trois vitesses.
- **Bibliothèque** de comptines traditionnelles, **Partition** en cases de couleur.
- **Créer ma chanson** : au clavier, en texte (`Do Ré Mi- Sol.`) ou depuis un fichier audio.

Tout tient dans `index.html`, sans dépendance ni étape de build. Les chansons créées restent dans le navigateur de l'appareil.

## Déploiement

Site statique : Netlify publie la racine du dépôt (voir `netlify.toml`).
