# Plan 30 jours → premier client

## Semaine 1 : Préparer (5 h au total)

- [ ] **J1** : Créer la micro-entreprise (formalites.entreprises.gouv.fr). Tu peux prospecter en attendant le SIRET.
- [ ] **J1** : Mettre `index.html` en ligne (voir README) et configurer Formspree.
- [ ] **J2** : Créer une adresse e-mail pro dédiée et une signature avec le lien de ton site.
- [ ] **J2** : Créer 2 sites de démo de plus en dupliquant `demo/plombier.html` : un **restaurant/boulangerie** et une **coiffeuse/esthéticienne**. Ajoute-les sur ta page d'accueil.
- [ ] **J3** : Choisir **1 métier cible** et **1 zone** (ta ville et 20 km autour). Se spécialiser fait vendre plus.
- [ ] **J3-J5** : Construire une liste de **100 prospects** dans `prospection/suivi-prospects.csv` :
  - Google Maps : cherche « plombier [ville] » et repère les fiches **sans site web** ou avec un site très daté.
  - Pages Jaunes, groupes Facebook locaux, annuaire des chambres de métiers.

## Semaine 2 : Prospecter (1 à 2 h par jour)

- [ ] **20 contacts par jour**, en mélangeant appels, e-mails et visites (scripts dans `prospection/scripts.md`).
- [ ] **L'arme secrète** : pour les 5 prospects les plus prometteurs, crée **la maquette de leur site AVANT de les contacter** (30 min avec la démo). Envoie-leur le lien : « J'ai préparé ça pour vous ». C'est de loin le taux de réponse le plus élevé.
- [ ] Relance J+3 puis J+7 pour chaque prospect qui n'a pas répondu.
- [ ] Note tout dans le tableau de suivi.

## Semaine 3 : Convertir

- [ ] Appel découverte de 15 min (questions dans `scripts.md`).
- [ ] Maquette livrée sous 48h.
- [ ] Validation, puis facture, puis paiement, puis mise en ligne.
- [ ] Proposer systématiquement la formule **Sérénité à 29 €/mois**.

## Semaine 4 : Faire boule de neige

- [ ] Demander un **avis Google** et un **témoignage** au 1er client, puis l'ajouter sur ton site.
- [ ] Ajouter son site dans ton portfolio.
- [ ] Demander **2 recommandations** : « Vous connaissez un autre artisan qui aurait besoin d'un site ? » Offre 50 € par client recommandé.
- [ ] Continuer les 20 contacts par jour.

## Livrer un site client en 2h (process)

1. Copier `demo/plombier.html` vers `clients/<nom-client>/index.html`.
2. Demander à Claude : « Adapte ce site pour [métier, ville, services, horaires, téléphone], ton professionnel, optimisé SEO local ».
3. Changer `--brand` (couleur) selon le logo du client.
4. Photos : celles du client, sinon Unsplash ou Pexels (libres de droits).
5. Publier gratuitement sur Netlify et relier le nom de domaine du client.
6. Créer ou optimiser sa **fiche Google Business Profile** et y mettre le lien du site.

## Indicateurs à suivre chaque semaine

| Indicateur | Objectif |
|---|---|
| Prospects contactés | 100 |
| Réponses positives | 10 |
| Maquettes envoyées | 5 |
| Ventes | 1 à 2 |
