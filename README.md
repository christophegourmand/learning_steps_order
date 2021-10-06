# learning_steps_order
Html and CSS Page to indicate list of what to learn for web developement, in an order that I consider optimized and logical. 
That list is just my personnal opinion, is not complete as unfortunately I have to focus on my own learning and I didn't update everytime I learn something new.

**Written in french**, for now, but I'll re-write it in english as soon as I can.


# ORDI

- ORDI :  Couches d'un ordinateur :   Application ,  Système d'exploitation , Matériel
    - explication
        
        Le Systeme d'exploitation est là pour gérer les ressources matérielles (souris, écran, mais surtout processeurs, mémoires vives et dur) pour que l'utilisateur ait seulement besoin de s'occuper d'utiliser son logiciel (avant, il devait **en plus** s'occuper de gérer lui-même les ressources mémoires et processeur, etc..)
        
- ORDI : toutes ressources matérielles
    - Ce qui est connecté à la carte mère.
        - processeur
        - RAM
        - disques durs
        - cartes réseaux , son, graphique,
        - Ports pour clavier, souris, écran, micro, casque-ou-enceinte, etc..
    - Le processeur
    - Les différents types de mémoires
        - Mémoires permanentes : Disque dur à plateau, disque SSD, clé USB, Carte SD / microSD .
        - Mémoires volatiles : Mémoires Centrales (dite RAM), mémoires Caches, Registres.    (les plus proches du processeur = petite capacité // très rapide)   (les plus loin du processeur = grande capacité // très lente)
        - 
        

# RÉSEAU

- modèle OSI et ses 7 couches.
    - voir vidéos youtube
        - celle du youtubeur indien qui explique toutes les couches.
    - suivre cours OpenClassroom sur le Réseau
        - expliquera le modèle OSI
        - expliquera les conversions    Base 10 ←→ Binaire
- modèle TCP/IP
    - video youtube
        - celle du français qui fait le parallèle entre [l'envoi d'un requête HTTP] et [l'envoi d'un courrier d'une entreprise à une autre].
- Comprendre l'intérieur d'une "HTTP Request".
    - les méthodes GET et POST

# CLAVIER

- CLAVIER : Dispositions (qwerty | qwerty international | qwerty CanadaFr) + symboles souvent utilisés pour leur position en qwerty.
    - < > ; : { } [ ] , . ' " ` / | \ & $ # @ ! ( ) - _ = + * ? ^ ~
    - explication
        
        *La syntaxe de programmation a été inventée par des personnes qui utilisaient majoritairement des claviers qwerty, ils ont simplement utilisé les symboles les plus accessibles sous leurs doigts. Et leurs doigts utilisaient des qwerty, et ils tapaient avec la méthode HomeRow.* 
        
        Tout écrivain a commencé par la base : 
        1. apprendre à tenir son stylo, 
        2. apprendre à tracer des lettres, 
        3. apprendre à les enchaîner, 
        4. apprendre les mots, 
        5. apprendre à les combiner en phrase,
        6. apprendre la base de tournure de phrase,
        7. apprendre de meilleurs tournures de phrase,
        8. apprendre à organiser les phrases en paragraphes,
        9. apprendre comment avoir une logique entre les paragraphes (but de chaque + organisation entre eux)
        10. organiser les paraphes (but + inter-actions + ordre + ... ) pour obtenir un Chapitre, ou une Lettre. 
        
        Tout développeur a commencé par la base : 
        1. apprendre à placer ses doigts sur le clavier en méthode home-row,
        2. apprendre la position des touches sans regarder, 
        3. apprendre à les enchaîner, (site d'entraînement)
        4. apprendre à taper les mots et symboles en programmation,
        5. apprendre à les combiner pour créer 1 ligne d'instruction,
        6. apprendre la base de rédaction d'instruction de type ceci, cela,
        7. apprendre des instructions rédigées d'une manière plus efficace,
        8. apprendre à organiser ses instructions en fonctions et méthodes,
        9. apprendre comment avoir une logique entre les fonctions. (but de chaque + organisation entre elles)
        10. organiser les fonctions pour obtenir un Objet, ou une classe.
        11. etc....
        
- CLAVIER : méthode de saisie "Home-row"  + sites d'entraînement pour une rapidité de Frappe d'au moins 50 wpm (mot par minute). *penser à s'entraîner autant pour du texte (surtout anglais, puis français,  mais bien évidemment et surtout la frappe de Code !)

# HTML / CSS

- HTML : rédaction d'une balise (chevrons) + rédaction d'un attribut (avec ou sans valeur)
- HTML : structure d'un fichier (`doctype`, `head`, `body`)
- HTML : dans body: balises de titres et texte (`h1`..`h6` , `p` )
- HTML : balises d'organisation de la page. (`header`, `main`, `article`, `section`, `aside`, `footer`, `div`, )
- dans head: ( `<html lang="fr">` )+ (`<meta charset="utf-8">` ) + (`<link ..>` pour fichier css)
- HTML : attributs id="__" et class="__  __  __"
- CSS : base de la  rédaction.  `selecteur {propriété: valeur; propriété: valeur;}`
- CSS : sélecteurs `taBalise { }`    `#tonId { }`   `.taClasse { }`
- ANGLAIS : les mots les plus utilisés. (*parler anglais permet de maîtriser 50% plus vite les balises Html, et le CSS, puis les méthodes Javascript).*
- CSS :
    - texte (taille&unités (`px`, `rem`, `em`, `%`)
    - + alignement,
    - + couleur (`#...` , `hsl(_,_%,_%)`, `rvb`, )   Je recommande particulièrement d'apprendre la roue de couleur HSL (*permet de créer de tête n'importe quelle couleur*).
- CSS : hauteurs + largeurs + unités % | vh | vw |
- CSS : le "flow" = éléments html qui se positionne en *block*, *inline*, *inline-block*.
- HTML : balises de liens (`a`), de listes (`ol` , `ul`, `li`)
- HTML : balises d'images (`img` et attributs *src*, *alt*, *title*) + (`figcaption`)
- HTML : balises sémantiques de texte (`em`, `strong`, `sub`, `sup`, `del`, `small`)
- HTML : balises de tables (`table`, `tr`, `th`, `td`, `thead`, `tbody`) et les attributs (*colspan="nbr"* , *rowspan*="nb")
- HTML : balises de citations (`q`, `blockquote`, `cite`)
- HTML : balises de vidéos (`video` et `source` + `embed` + `iframe`)

# CSS

- CSS : tous les sélecteurs restants : les **pseudos-classes**.
- CSS : sélecteurs : les **pseudos-éléments** pour créer + propriété `content : "";`
- CSS : gestion des polices (propriétés `font-.....` et `text-.....` et qq autres )

# JavaScript

- JS : variables
- JS : opérateurs simples
- JS : comparateurs
- JS : conditions ( `if` , `if..else` , `if..else`, `if.. else` )
- JS : boucles ( `for`, `for in` , `for of` , `while`, `do while`)        .......... (le forEach après les fonctions callback).
- JS : fonctions + return + arguments ( sans + avec + valeurs par défault + illimités via `...` ).
- JS : fonctions (anonyme) + (anonyme & auto-invoquées) +
- JS : fonction (anonyme & stockée dans une variable) (+ instanciation et le but)
- fonctions imbriquées (nested): soit passer des fonctions en argument d'une autre).
- ...
- JS : étudier `export` depuis un scritp annexe ET `import` depuis un script principal.
- JS : changer le style CSS d'un élément.
- JS : gérer les délais avec les timeout.
- JS : gérer les événements pour les click | les hover | les scoll | les keydowns.
    >> puis les utiliser pour manipuler les classes CSS.
- CSS : mettre un panneau caché à gauche, ou à droite.
- CSS : animations (et gestion des timings et des accélérations de transitions)
- stocker des infos dans les `cookies` , et surtout dans le `local storage`.

# PHP

# SQL
