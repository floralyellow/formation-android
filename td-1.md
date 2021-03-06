# TD 1 - Introduction à Android

## Avant de commencer
Prendre en main l'IDE: vous pouvez aller dans les paramètres (<kbd>Cmd</kbd> + <kbd>, </kbd> ou  `Android Studio > Preferences`) et adapter à vos habitudes, par ex:
- La Font utilisée
- Le thème global
- La coloration syntaxique
- Les raccourcis clavier
- Les plugins

Je vous conseille en particulier de:
- Changer le raccourci pour les commentaires car sur AZERTY celui par défaut ne fonctionne pas (mettez <kbd>Cmd + :</kbd>)
- Changer la coloration syntaxique qui n'est pas terrible pour Kotlin: vous pouvez installer un plugin (ex: "Rainglow Color Schemes") et choisir parmis les divers proposés ou utiliser mon thème "Darculai" dispo sur ce repo (qui est juste le thème Darcula par défaut avec quelques ajouts)
- Ajouter des plugins comme RainbowBrackets, Codota, grep console, SonarLint (et regardez les plus téléchargés dans l'onglet MarketPlace)
- Activer les imports automatiques: `Editor > General > Auto Import > Kotlin > cocher "Add unambiguous import on the fly" et "Optimize imports on the fly..."`

## Kotlin Koans

Suivre les exercices des [Kotlin Koans](https://try.kotlinlang.org) dans Android Studio (en ajoutant le plugin "Edutools" puis `File > Learn and Teach > Browse Courses > Kotlin Koans`) ou sur le site [try.kotl.in](https://try.kotl.in) (mais vous n'aurez pas l'auto-complétion)

## Google Codelabs
Faire les tutos de la collection
[Android Kotlin Fundamentals](https://codelabs.developers.google.com/android-kotlin-fundamentals/) à partir de 02.1 (vous pouvez survoler rapidement ceux d'avant) et 

⚠️ Attention:
- Ne restez pas bloqués sur les pages "Introduction", "Overview", ce sont juste des résumés de ce que vous allez faire.
- Parfois l'IDE bug et n'affiche pas certains attributs dans le layout editor (typiquement textAlignment, fontFamily,...) dans ce cas, rien de grave, passez juste en mode Text
- Parfois les attributs avec start/end ne s'affiche pas: idem rien de grave vous pouvez utiliser left/right (ex: marginLeft au lieu de marginRight)
