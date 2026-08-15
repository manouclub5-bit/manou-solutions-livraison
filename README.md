# MANOU SOLUTIONS LIVRAISON

Déploiement GitHub Pages.

## Fichiers
- `index.html` : espace public client.
- `livreur/index.html` : espace livreur sécurisé par Supabase Auth.
- `admin/index.html` : espace administrateur sécurisé par Supabase Auth + rôle admin.

## Supabase
Projet configuré avec :
- URL `https://jgcbwtxdwbwetiugbfrk.supabase.co`
- clé Publishable côté navigateur.

Exécuter le schéma SQL fourni dans `supabase.sql` dans Supabase SQL Editor.

## Important
CinetPay n'est pas exécuté directement avec une clé secrète dans le navigateur. Il faut ajouter une Supabase Edge Function pour initier/vérifier les paiements.
Les notifications WhatsApp automatiques vers +228 72 65 28 02 nécessitent une API WhatsApp Business/Provider côté serveur.
