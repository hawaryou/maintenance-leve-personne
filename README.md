# ENR11-V02 — Maintenance lève-personnes

Application web mobile reprenant le style et les fonctionnalités du projet ENR09-V02. La checklist reprend les contrôles visuels, fonctionnels et la décision de maintien en service de la fiche ENR11-V02 fournie.

Fonctionnalités :
- maintenance annuelle ou périodique ;
- lecture QR Code, Data Matrix, Code 128 et EAN-13 par caméra ou photo ;
- contrôles avec choix non applicable / conforme / non conforme ;
- saisie du numéro des sangles ;
- décision de maintien en service : approuvé, approuvé sous réserve, non approuvé ;
- PDF avec résultat des contrôles, signatures, observations, pièces changées et niveau d’obsolescence ;
- envoi du PDF par e-mail via Google Apps Script ;
- mode normal et tournée multi-appareils avec une seule signature client.

## Déploiement

Publier les fichiers du dépôt sur GitHub Pages. Pour l’envoi e-mail, déployer `Code.gs` comme application Web Google Apps Script et vérifier le destinataire configuré avant mise en service.


## Menu, aperçu PDF et confidentialité

- Le menu graphique « Menu » en haut à gauche renvoie vers le HUB EuroMed.
- « Aperçu / Télécharger PDF » ouvre une prévisualisation du PDF ENR11-V02.
- « Aperçu puis envoyer » ouvre le même aperçu ; l'envoi ne démarre qu'après validation explicite.
- La notice « Confidentialité et données personnelles » est accessible depuis le pied de page, y compris sur mobile.
- Le fichier `Code.gs` de ce dépôt est destiné à ENR11-V02. Il doit être déployé dans un projet Apps Script dédié au lève-personnes, distinct des autres formulaires EuroMed.

La notice ne garantit pas à elle seule la conformité RGPD : EuroMed doit compléter les informations relatives au responsable de traitement, aux durées de conservation, à la base légale, aux droits des personnes et aux prestataires.
