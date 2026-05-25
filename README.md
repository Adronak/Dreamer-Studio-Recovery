# Dreamer Studio Recovery Portal

Auteur: Adro

Ce dossier contient le portail statique minimal pour `REC-009_GITHUB_PAGES_INSTALLER_PORTAL`.

But:

- fournir un lien simple de recuperation;
- pointer vers les GitHub Releases privees;
- rappeler le runbook recovery;
- ne jamais heberger de backup, secret ou configuration locale.

Le fichier `index.html` contient des placeholders remplaces par le workflow:

- `__GITHUB_REPOSITORY__`
- `__REPOSITORY_URL__`
- `__RELEASES_URL__`
- `__LATEST_RELEASE_URL__`
- `__INSTALLER_RELEASE_URL__`
- `__INSTALLER_DOWNLOAD_URL__`
- `__GENERATED_AT__`

Le portail est volontairement statique et sans dependance de build pour rester deployable sur un PC/repo minimal.

Assets locaux:

- `assets/dreamer-logo.png`: logo applicatif Dreamer Studio copie depuis `studio/app/dreamer-studio/src-tauri/icons/Square310x310Logo.png`.
- `assets/dreamer-logo-v4.png`: logo DST V4 fourni par Adro, utilise comme logo principal du portail premium.

Regle:

- ne pas hotlink d'image externe dans ce portail;
- ne pas inclure d'image sous licence douteuse;
- garder le portail autonome pour GitHub Pages et offline preview.
