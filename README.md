# securite_mobile_Analyse_statique_APK_MobSF_Mobexler

Task 1 — Préparation de l'environnement d'analyse

Démarrer la VM Mobexler

Créer un dossier de travail dédié à cette analyse
<img width="1232" height="202" alt="image" src="https://github.com/user-attachments/assets/cba786c7-5feb-4b7f-8323-e244ff10ef88" />

Copier l'APK à analyser dans ce dossier
<img width="1429" height="333" alt="image" src="https://github.com/user-attachments/assets/d7e346db-531c-40ba-9c5a-6868cdb2a369" />

Vérifier l'intégrité de l'APK :
<img width="1432" height="405" alt="image" src="https://github.com/user-attachments/assets/3af81522-51cf-4ae8-abfa-b4d7b36c9ce1" />

Documenter l'environnement d'analyse :
<img width="1904" height="612" alt="image" src="https://github.com/user-attachments/assets/0a3659dc-0303-448e-9ad9-56dd30b43ec9" />
<img width="1643" height="300" alt="image" src="https://github.com/user-attachments/assets/1da3cd26-6ef6-4f8e-a2ee-0cbbd3f64477" />

Task 2 — Lancement de MobSF
Lancer MobSF depuis le terminal ou le menu d'applications
<img width="1440" height="789" alt="image" src="https://github.com/user-attachments/assets/2cfb0def-7ff3-4cb2-bbf0-90b7e7a8cb65" />

Vérifier que l'interface web est accessible
<img width="1914" height="671" alt="image" src="https://github.com/user-attachments/assets/22d6c220-0995-44fa-8330-3a4915d8aaf1" />
version 
<img width="1339" height="93" alt="image" src="https://github.com/user-attachments/assets/37f9beb6-c292-402e-ad0f-719d8f1b8842" />
<img width="1535" height="116" alt="image" src="https://github.com/user-attachments/assets/527ccbb9-c92d-4a1f-938b-b92471a69386" />

les menus principaux 
<img width="1536" height="121" alt="image" src="https://github.com/user-attachments/assets/1d858b2d-1df6-4416-8201-7df897bbed34" />

 le formulaire d'upload
<img width="1151" height="545" alt="image" src="https://github.com/user-attachments/assets/c6a7125f-a54f-46c1-beda-6f2eb825d6f4" />

Task 3 — Import et analyse de l'APK

Importer l'APK dans MobSF pour analyse
<img width="1226" height="548" alt="image" src="https://github.com/user-attachments/assets/f3f74485-79d8-48f8-b7d3-9608281a4b0d" />
<img width="1772" height="506" alt="image" src="https://github.com/user-attachments/assets/f031003b-562b-418b-996b-64cb7a077c70" />

 la page de résultats générée
 <img width="1569" height="458" alt="image" src="https://github.com/user-attachments/assets/eae41eac-efe3-4dac-ab13-440622ae5246" />
<img width="1503" height="456" alt="image" src="https://github.com/user-attachments/assets/1abc3cdc-0cbd-44e8-9023-ae662c19779b" />

 l'heure de fin d'analyse dans le fichier de traçabilité 
 <img width="1729" height="638" alt="image" src="https://github.com/user-attachments/assets/52d16c0e-3fae-41a3-b2fb-4a7895711698" />

Task 4 — Analyse du manifeste et des permissions

Naviguer vers la section "App Information" du rapport
<img width="686" height="349" alt="image" src="https://github.com/user-attachments/assets/8ce5b3f9-0dc2-4d7a-bccd-e2e95f462e1d" />

Examiner les informations de base (package, version, SDK)
*AndroidManifest.xml *
Application Debuggable
<img width="1878" height="151" alt="image" src="https://github.com/user-attachments/assets/66b6d144-4177-4b20-a908-85a29c97847c" />

Autorise les sauvegardes
<img width="370" height="126" alt="image" src="https://github.com/user-attachments/assets/62fa9dca-d522-4881-a877-f54fdd644e9e" />

Niveau d’API cible
<img width="806" height="79" alt="image" src="https://github.com/user-attachments/assets/d53b7624-4fd6-492f-bd09-18c4ab517bc5" />

Accéder à la section "Manifest Analysis"
voila les avertissements de sécurité signalés par MobSF
<img width="1818" height="479" alt="image" src="https://github.com/user-attachments/assets/fa79a044-30dd-4381-87ea-cc987b2bd9f2" />

Analyser les permissions listées
les permissions normales
<img width="1795" height="232" alt="image" src="https://github.com/user-attachments/assets/c2f57581-24ae-474b-b49d-6ee08ed1bd85" />

 les permissions dangereuses
 <img width="1799" height="186" alt="image" src="https://github.com/user-attachments/assets/5ae787a0-57fd-40b7-a00d-88679a96ffb8" />

 Vérifier les composants exportés
 <img width="1622" height="147" alt="image" src="https://github.com/user-attachments/assets/f3d266a3-9b4d-431a-8510-87708263b21c" />
Task 5 — Analyse de la configuration réseau


