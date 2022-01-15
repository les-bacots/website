# Hugo WebSite

Ce dépôt est destiné à la gestion des documents du groupe lesbacots.org. Une fois relu et approuvée, le résultat est publié automatiquement sur la page github du projet.

Toute contribution est la bienvenue. Pour plus de détails vous pouvez vous référer au [guide de contribution](CONTRIBUTING.md).

## Installation

Pour contribuer localement on peut cloner le projet avec les commandes suivantes:

```bash
~$ git clone git@github.com:les-bacots/website.git
Clonage dans 'website'...
...
Résolution des deltas: 100% (9/9), fait.
```

Une fois les fichiers récupérés, on peut installer les dépendances comme suit:

```bash
~$ npm install
...
Hugo Installer

> Checking for existing binary
  Binary already exists!
> Verifying binary health

Hugo is now available in "node_modules/.bin/hugo".
...
Success!

up to date, audited 735 packages in 2s
```

| :memo: besoin de l'outil [`git`](https://git-scm.com/downloads) et [`npm`](https://github.com/nvm-sh/nvm#installing-and-updating) |
|-----------------------------------------------------------------------------------------------------------------------------------|


## Lancement

Une fois installer on lance le site de la façon suivante:

```bash
~$ npm run start
...
Environment: "development"
Serving pages from memory
Web Server is available at http://localhost:7759/ (bind address 0.0.0.0)
Press Ctrl+C to stop
```

Le site peut alors être consulter à l'adresse suivante dans un navigateur -> http://localhost:7759.

## License

[MIT](LICENSE)
