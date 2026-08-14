# MANOU SOLUTIONS — Livraisons et Courses

## Structure
- `client/index.html` : site public à partager aux clients.
- `client/devenir-livreur.html` : candidature livreur.
- `admin/admin.html` : prototype du tableau d'administration.

## Important
GitHub Pages est un hébergement statique. Cette version sépare l'interface client de l'interface admin, mais le tableau admin n'est **pas une vraie sécurité serveur** et ne reçoit pas automatiquement les commandes des autres appareils.

Pour une production réelle :
1. mettre les commandes dans une base de données (Supabase/Firebase ou backend);
2. ajouter une authentification serveur pour l'admin et les livreurs;
3. intégrer CinetPay côté serveur;
4. utiliser WhatsApp Business API pour les notifications automatiques;
5. ne jamais mettre une clé secrète CinetPay dans le HTML.

## Tarifs
- Moto : 80 F/km
- Tricycle : 150 F/km
- Voiture : 250 F/km
- Commission livreur : 20%

## Contact
WhatsApp : +228 72 65 28 02
Email : manousolutionsbtp@gmail.com
Zone : Grand Lomé
