# Dons EPDC Charleroi

Page statique : IBAN à copier et lien PayPal, sans QR bancaire.

## Publication GitHub Pages

- Branche `main`, dossier `/ (root)`.
- Domaine personnalisé : `don.epdccharleroi.be`.
- Activer HTTPS dès que le certificat est disponible.
- Conserver `index.html` et `logo-epdc.png` dans le même dossier, avec cette casse exacte.
- Le logo officiel de l’archive est conservé sans modification, sur fond blanc pour sa lisibilité.

## DNS OVH

Supprimer uniquement le TXT `don` dont la valeur est `don.epdccharleroi.be`, puis ajouter :

```dns
don 3600 IN CNAME zanksolutions-hash.github.io.
```

Ne pas modifier le domaine racine, `www`, la messagerie ou les serveurs DNS.

## Coordonnées conservées de l’archive fournie

- Bénéficiaire : Église Porte des Cieux Charleroi
- IBAN : BE95 0019 5644 7358
- PayPal : https://www.paypal.com/ncp/payment/M7DKRUCKY3GCY
