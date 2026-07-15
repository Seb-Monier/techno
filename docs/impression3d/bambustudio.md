# Guide de démarrage rapide de Bambu Studio

## Qu'est-ce que Bambu Studio ?
sfsfdsf
**Bambu Studio** est basé sur PrusaSlicer de Prusa Research, qui est lui-même issu de Slic3r par Alessandro Ranellucci et la communauté RepRap.

Bambu Studio est notre logiciel de tranchage de pointe et riche en fonctionnalités, développé par Bambu Lab, utilisé pour préparer les fichiers pour l'impression 3D. Il contient des flux de travail basés sur des projets, des algorithmes de tranchage systématiquement optimisés et une interface graphique facile à utiliser, offrant aux utilisateurs une expérience d'impression incroyablement fluide.

![studio_en.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/studio_en.png)

## Configuration système requise

* Windows 10 ou version ultérieure
* Mac OS X v10.15 ou version ultérieure
* Linux Ubuntu 20.02 ou version ultérieure/Fedora 36 ou version ultérieure (la version Linux doit être téléchargée depuis [github](https://github.com/bambulab/BambuStudio/releases))
* Processeur Intel® Core 2 ou AMD Athlon® 64 ; processeur de 2 GHz ou plus rapide
* Système compatible OpenGL 2.0
* 8 Go de RAM recommandé, 4 Go minimum
* 2,0 Go ou plus d'espace disque disponible

## Téléchargement et installation

1. Télécharger [Bambu Studio](https://bambulab.com/download)
2. Installer Bambu Studio en suivant le guide étape par étape

## Assistant de configuration

### Sélectionner la région de connexion

La première étape consiste à sélectionner la région dans laquelle vous vous trouvez. Un compte utilisateur enregistré en Amérique du Nord, par exemple, ne peut pas se connecter si la région est définie sur Chine.

![](https://wiki.bambulab.com/software/bambu-studio/quick-start/select_region.png)

### Sélection de l'imprimante

Choisissez les imprimantes/buses que vous souhaitez afficher dans le menu d'opération du logiciel de tranchage. Vous pouvez sélectionner toutes ou certaines des options qui vous sont proposées. Ces options peuvent être modifiées ultérieurement via le menu du logiciel de tranchage si vous ne souhaitez en choisir qu'une à ce stade et décider de changer la taille de la buse plus tard.

![](https://wiki.bambulab.com/quick-start-guide/print_selection.png)

### Sélection du filament

Sélectionnez les filaments que vous souhaitez voir apparaître dans la liste des préréglages de filament ; vous pouvez en choisir autant que disponibles.

![](https://wiki.bambulab.com/software/bambu-studio/quick-start/select_filament.png)

### Installer le plugin réseau Bambu

Le plugin réseau Bambu offre des fonctionnalités de mise en réseau, telles que l'impression via WAN/LAN, le contrôle à distance et la synchronisation des données utilisateur. L'installation du plugin nécessite une connexion Internet et sera automatiquement installée (si activée) après l'assistant de configuration.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/install_plugin.png)

## Première impression

### Connectez-vous à votre compte (facultatif, mais fortement recommandé)

***Prérequis : Le plugin BambuNetworking est nécessaire pour se connecter***.  
Ceci est requis pour activer l'historique d'impression, ce qui vous permet de réimprimer vos modèles depuis l'application Bambu Handy. De plus, vos paramètres utilisateur peuvent être synchronisés avec Bambu Cloud afin de partager des informations entre vos appareils PC.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/sign_in.png)

> **Remarque :** Étant donné que l'imprimante et Studio ne peuvent pas actualiser ou appeler automatiquement l'interface à intervalles réguliers, après avoir changé le surnom, les utilisateurs doivent dissocier et réassocier l'imprimante.  
> Pour Studio, veuillez vous déconnecter puis vous reconnecter pour afficher le surnom mis à jour.

### Connecter l'imprimante à Bambu Studio

Avant de lancer une tâche d'impression, vous devez lier votre imprimante à Bambu Studio.  
Si vous avez déjà effectué cette étape lors de la phase de configuration initiale, vous pouvez la passer – il s'agit juste d'un rappel. Cela permet la surveillance de l'état de l'appareil, le lancement de tâches à distance et le contrôle. Vous pouvez associer votre imprimante en utilisant l'application mobile Bambu Handy ou le client de bureau Bambu Studio.

**1. Bambu Handy**  
Ouvrez l'application, naviguez vers l'onglet **Appareils** en bas de l'écran, et appuyez sur **« + Associer imprimante »**.  
 ![1280x1280_(1).png](https://wiki.bambulab.com/software/bambu-studio/quick-start/1280x1280_(1).png)  
Une fois l'imprimante associée avec succès, connectez-vous simplement au même compte dans Bambu Studio pour synchroniser votre liste d'appareils.

> Nous recommandons d'utiliser Bambu Handy pour l'association de l'imprimante, car il prend en charge toutes les imprimantes de la série Bambu. Si vous souhaitez en savoir plus sur Bambu Handy, vous pouvez consulter ce wiki : [Guide de démarrage rapide de Bambu Handy](https://wiki.bambulab.com/fr/studio-handy/handy/bambu-handy-quick-start)

**2. Bambu Studio**  
Vous pouvez également associer votre imprimante directement depuis l'application de bureau Bambu Studio. Deux méthodes sont disponibles :

* **Association via code PIN** (Disponible uniquement pour les séries P et A).
* **Association via adresse IP et code d'accès** (Nécessite que l'imprimante soit en mode LAN ; convient aux réseaux isolés ou aux environnements sans accès Internet).

![1280x1280_(2).png](https://wiki.bambulab.com/software/bambu-studio/quick-start/1280x1280_(2).png)

> Pour des étapes détaillées, veuillez consulter les ressources wiki suivantes :
>
> 1. [Associer une imprimante dans Bambu Studio à l'aide d'un code PIN](https://wiki.bambulab.com/fr/bambu-studio/manual/pin-code)
> 2. [Utilisation du mode LAN sur une imprimante Bambu Lab](https://wiki.bambulab.com/fr/knowledge-sharing/enable-lan-mode)

Après avoir associé votre imprimante avec succès, naviguez vers la section **Appareil** pour vérifier son état et vous assurer que tout est prêt pour la tâche d'impression.

### Créer un nouveau projet

Pour commencer le tranchage d'un modèle, cliquez sur **Nouveau Projet**.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/create_project.png)

### Ajouter un modèle

Dans la barre d'outils supérieure du panneau d'aperçu, cliquez sur la première icône **ajouter** pour importer un modèle. Vous pouvez également glisser-déposer des fichiers de modèle d'un dossier vers Studio. Les fichiers pris en charge incluent .3mf .stl .stp .step .amf .obj.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/add_stl.png)

### Sélectionner les préréglages Imprimante/Filament/Processus

Pour commencer le tranchage du modèle, vous devez choisir les préréglages pour la machine que vous utilisez, pour le filament avec lequel vous imprimerez et également les réglages avec lesquels vous souhaitez imprimer le modèle.

1. Sélectionnez l'imprimante que vous utilisez dans la liste déroulante sous **Imprimante**. Cela inclura également la taille de buse avec laquelle vous imprimerez.
2. Sous la section **Filament**, sélectionnez le type de filament que vous comptez utiliser dans la liste déroulante.
3. Choisissez la hauteur de couche souhaitée pour l'impression de votre modèle dans le menu déroulant **Processus**. **Gardez toujours à l'esprit que plus la hauteur de couche est petite, plus l'impression prendra de temps.** Pour la majorité des impressions, une hauteur de couche de 0,20 mm est la norme.\*\*  
    ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/select_presets.png)

### Trancher le plateau

* Une fois cela fait, cliquez sur le bouton **Trancher** situé en haut à droite de Bambu Studio.  
   ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/slice.png)
* Si le fichier modèle contient plusieurs disques, cliquez sur **Trancher tout** dans le coin supérieur droit de l'écran.  
   ![切片所有.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/%E5%88%87%E7%89%87%E6%89%80%E6%9C%89.png)

Une fois terminé, le logiciel de tranchage vous mènera au panneau d'aperçu qui vous montrera l'apparence du modèle tranché après le traitement du fichier .3mf. L'histogramme sur le côté droit vous montrera également des informations sur les temps d'impression pour chaque paramètre de l'impression.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/sliced.png)

### Envoyer la tâche d'impression

#### Imprimer le plateau

Cliquez sur **Imprimer** en haut à droite. Ceci affichera une fenêtre contextuelle avec un aperçu rapide du modèle et vous demandera également de sélectionner l'imprimante à laquelle vous souhaitez l'envoyer dans la liste déroulante. Vous aurez également la possibilité de choisir si vous souhaitez que l'imprimante exécute certaines fonctions comme le nivellement du plateau, la calibration du flux, etc., avant le début de l'impression. Une fois terminé, cliquez sur « Envoyer » pour envoyer le fichier à l'imprimante et commencer l'impression.

![print_plate-.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/print_plate-.png)

#### Imprimer tout

Veuillez cliquer sur [Guide d'impression multi-plateaux de Bambu Studio](https://wiki.bambulab.com/fr/studio-handy/multi-plate-printing) pour plus d'informations.

> **Remarque :** Vous devrez avoir le plugin réseau Bambu installé pour pouvoir envoyer des fichiers via WLAN, et assurez-vous que Bambu Studio et l'imprimante sont sur le même réseau local (LAN).

#### Envoyer/Tout envoyer

* Cliquez sur la flèche à gauche de **Imprimer plateau** dans le coin supérieur droit de l'écran, puis sélectionnez **Envoyer**.

![send_to_sd.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/send_to_sd.png)

* Si le fichier modèle contient plusieurs disques, cliquez sur la flèche à gauche de **Imprimer plateau** dans le coin supérieur droit de l'écran, et sélectionnez **Tout envoyer**. Une fenêtre **Envoyer vers la carte MicroSD de l'imprimante** apparaîtra à l'écran. Sélectionnez l'imprimante destinataire, et le fichier modèle pourra être envoyé à la carte SD de l'imprimante.

![send_all-.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/send_all-.png)

> **Remarque :** Assurez-vous que Bambu Studio et l'imprimante sont sur le même réseau local (LAN).

#### Exporter le fichier tranché du plateau / tous les fichiers tranchés

* Éjectez la carte SD de l'imprimante et insérez-la dans votre ordinateur. Cliquez sur la flèche à gauche de **Imprimer plateau** dans le coin supérieur droit de l'écran et sélectionnez **Exporter le fichier tranché du plateau**, puis cliquez sur l'option **Exporter le fichier tranché du plateau** sélectionnée pour confirmer.

![export--.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/export--.png)

* Si le fichier modèle contient plusieurs disques, vous pouvez cliquer sur la flèche à gauche de **Imprimer plateau** dans le coin supérieur droit de l'écran et sélectionner **Exporter tous les fichiers tranchés**.

![xport-all.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/xport-all.png)

Une fenêtre d'explorateur de fichiers apparaîtra pour que vous puissiez sélectionner l'emplacement de la carte SD. Ensuite, cliquez sur **Enregistrer** et le fichier sera exporté vers la carte SD.  
 ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/export_to_sdcard.jpg)

Une fois enregistré, prenez la carte SD et insérez-la dans le petit emplacement situé sur le côté droit de l'écran de l'imprimante. Appuyez sur l'icône **Accueil** dans la sélection du menu de gauche sur l'écran, appuyez sur **Fichiers d'impression**, puis sélectionnez l'option **Carte SD** dans le menu supérieur. Cliquez sur le fichier que vous venez d'exporter pour lancer l'impression.

![查看_sd_卡-en.png](https://wiki.bambulab.com/software/bambu-studio/quick-start/%E6%9F%A5%E7%9C%8B_sd_%E5%8D%A1-en.png)

> **Pour un guide détaillé sur l'impression depuis la carte SD pour chaque modèle, consultez :**  
>  [Comment imprimer depuis une carte Micro SD sur Bambu Lab X1](https://wiki.bambulab.com/fr/x1/manual/print-from-sd-card)  
>  [Comment imprimer depuis une carte SD avec une imprimante 3D Bambu Lab série P1](https://wiki.bambulab.com/fr/p1/manual/how-to-print-from-sd-card)  
>  [Comment imprimer depuis une carte SD avec une imprimante 3D Bambu Lab série A1](https://wiki.bambulab.com/zh/a1/manual/how-to-print-from-sd-card)

#### Envoyer vers plusieurs appareils

Veuillez cliquer sur [Gestion multi-appareils](https://wiki.bambulab.com/fr/software/bambu-studio/multi-device-management#Sending-a-Job-to-Multiple-Devices) pour plus d'informations.

## Contrôle à distance

Accéder à la surface **Appareil** de Studio vous permettra de contrôler et de surveiller l'impression à distance en temps réel (Veuillez consulter ce wiki : [télécommande](https://wiki.bambulab.com/fr/software/bambu-studio/remote-control)). Si une caméra est installée dans votre machine (standard sur la X1C), vous pouvez également visionner un flux vidéo en direct de l'impression à distance.

> ***Remarque : Le plugin réseau Bambu doit être installé pour pouvoir accéder à la machine via ce processus***.  
>  ![](https://wiki.bambulab.com/software/bambu-studio/quick-start/remote_control_and_monitor.png)

## Notes finales

> *Nous espérons que ce guide détaillé vous a été utile et instructif.*
>
> \_Pour assurer une exécution sûre et efficace, si vous avez des préoccupations ou des questions concernant le processus décrit dans cet article, nous vous recommandons de soumettre un [ticket d'assistance technique](https://bambulab.com/en/my/support/tickets?from=5) concernant votre problème. Veuillez inclure une image ou une vidéo illustrant le problème, ainsi que toute information supplémentaire relative à votre demande.*

ℹCe contenu a été traduit par IA et peut contenir de légères imprécisions ou des problèmes de formulation. Si vous remarquez un problème, veuillez nous contacter à [wiki@bambulab.com](mailto:wiki@bambulab.com) et nous le corrigerons dans les plus brefs délais.