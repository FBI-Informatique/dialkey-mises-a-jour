# Mises à jour de DialKey

Versions publiées de DialKey (composition par raccourci clavier pour téléphones Yealink), FBI Informatique SA.

- `DialKey.exe` : dernière version stable, pour installer un nouveau poste.
- `stable.json`, `beta.json` : version proposée à chaque canal. Les postes installés les consultent toutes les 6 heures.
- `versions/` : toutes les versions publiées.
- `licences/` : prolongations de contrat signées (numéro de contrat et date de fin, sans nom de client).

Chaque fichier est signé : un poste n'installe une mise à jour ou une prolongation que si sa signature est valide.
Ne modifiez pas ces fichiers à la main : ils sont produits par `publier.cmd` et la gestion des licences.
