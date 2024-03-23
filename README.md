# FCSC 2020 IT Security 101

Vous suivez un cours de sécurité informatique dans une célèbre université. Pour faciliter l’échange de documents, votre professeur a mis en ligne un service pour déposer les devoirs au format PDF. Hacker dans l’âme, vous voulez évaluer la sécurité de ce système. Vous savez que votre professeur consulte fréquemment ce service, et vous l’avez vu utiliser le lecteur muPDF sur son ordinateur. Vous avez par ailleurs réussi à intercepter les fichiers message.tex et message.pdf envoyés par le directeur de l’université à votre professeur qui indique un deuxième échange de fichier. Grâce à vos incroyables talents, vous avez également intercepté ce deuxième fichier (flag.pdf), mais celui-ci est malheureusement protégé par un mot de passe que vous ne connaissez pas. Saurez-vous malgré tout lire le contenu de ce fichier ?

Notes :

Note 1: Les PDFs acceptés sont limités à 8ko.
Note 2: Le professeur ouvre régulièrement les fichiers PDF envoyés, entre son mot de passe si besoin, et clique dedans avec sa souris.
Note 3: Les dossiers it-security-101_PoW, it-security-101_uploaded et it-security-101_processed dans /tmp sont montés par les conteneurs et doivent avoir les bonnes permissions (chmod 777):

```
mkdir -p /tmp/it-security-101_PoW /tmp/it-security-101_uploaded /tmp/it-security-101_processed
chmod 777 /tmp/it-security-101_PoW /tmp/it-security-101_uploaded /tmp/it-security-101_processed
```


Fichiers :
- [message.tex](message.tex)
- [message.pdf](message.pdf)
- [flag.pdf](flag.pdf)



Auteur : [Cryptanalyse](https://twitter.com/Cryptanalyse)

Origine : [IT Security 101](https://hackropole.fr/fr/challenges/misc/fcsc2020-misc-it-security-101/)


## Connectez vous 
> http://localhost



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2020-misc-it-security.git

> cd fcsc2020-misc-it-security


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/misc/fcsc2020-misc-it-security-101/