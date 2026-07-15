# Démarrage rapide avec les imprimantes 3D
##Téléchargement du model 3D

Pour commencer, vous aurez besoin d'un model 3D.  
Vous pouvez telecharger ce fichier: [Flexagon.stl](flexagon.stl)  
Ou sur l'un des sites de partage de models 3D: [Où trouver des models 3D ?](ou_trouver_des_models_3d.md) 
 
---
 
##Installation et configuration de Bambu Studio

#### 1. Télécharger et intsaller  <a href="https://bambulab.com/download" target="_blank" rel="noopener noreferrer"> Bambu Studio </a>  
A la première ouverture de Bambu Studio, vous serez invité à sélectionner diffèrent paramètres. 
Laisser les paramètres par défaut et cliquer sur suivant jusqu'à arriver sur l'interface si dessous.  
 
   <!--#### 2. Sélectionner de la région

   ![Sélection de la région](images/bambu/region.jpeg)
   
   ---
   

   #### 3.Sélection des l'imprimantes

   Cliquez sur **Tout effacer** puis selectioner l'imprimante **X1 Carbon**.

   ![](images/bambu/imprimantes.jpeg)
   
   ---
   

   #### 4.Sélection du filament

   Les filaments les plus courants sont déjà présélectionné cliquer sur suivant.

   ![](images/bambu/filaments.jpeg)
   
   ---
   

   #### 5. Ne pas installer le plugin réseau Bambu

   Décocher l'installation du plugin réseau et cliquer sur terminer. 

   ![](images/bambu/reseau.jpeg)
   
   ---

   ## Praparation de votre impression  -->

#### 2. Créer un nouveau projet

![](images/bambu/new_project.jpeg)

---

#### 3. Selectioner la bonne imprimante 3D

Cliquer sur l'icone de l'imprimante 3D et selectioner l'imprimante **X1 Carbon**.  

![](images/bambu/select_X1C.jpeg)

---
 
#### 4. Ajouter le modèle précédemment télécharger 
Si ce n'est pas fait : [Téléchargement du model 3D](#telechargement-du-model-3d)

Dans la barre d'outils supérieure, cliquez sur l'icône **ajouter** pour importer le modèle 3D.  
Vous pouvez également  faire un glisser-déposer.  
Les fichiers pris en charge sont .3mf .stl .stp .step .amf .obj.   

![](images/bambu/insertion.jpeg)

---
 
#### 5. Positionner le modèle sur le plateau

Le modèle n'est pas forcement bien orienté sur le plateau.  
**Cliquer sur la fonction orientation automatique.**  
Il calcule l’orientation qui semble la plus pertinente.  
Si besoin, d'autre outilles sont disponible pour modifier manuellement, la position, l'échelle ou l'orientation du model.  


![](images/bambu/position.jpeg)

---

#### 6. Paramétrage de l'impression

Verifier que le filament (matière), est bien du **PLA**  
Sélectionner le profile de paramétrage **0.28mm Extra Draft**

![](images/bambu/parametrage.jpeg)

Cliquer sur **Supports** et cocher la case **Activer les supports**  
Puis cliquer sur **Trancher le plateau**

![](images/bambu/supports.jpeg)

---

#### 7. Aperçu du tranchage
Le slicer vient de calculer les trajectoires d'impression, le temps d'impression et la quantité de filament nécessaire.  
Vous dévirez avoir à peu près le même temps d’impression et quantité de matières que ci-dessous.  

![](images/bambu/apercu.jpeg)

---

#### 8.Exporter le fichier tranché (.3mf)

Cliquer sur la fleche  et sélectionner **Exporter le fichier tranché du plateau**.    
Puis cliquez sur le bouton **Exporter le fichier tranché du plateau**  
Enregistrer le fichier .3mf sur votre ordinateur. 

![](images/bambu/export.jpeg)

---

## 3D Printer OS

L'envoie du fichier à l'imprimante 3D se fait via le serveur 3D Printer OS.

### 1. Création du compte

Créer votre compte sur le site <a href="https://cloud.3dprinteros.com" target="_blank" rel="noopener noreferrer"> 3D Printer OS </a>.  
Utiliser votre adresse mail etudiante. 

### 2. Ajouter les imprimantes (WorkGroup)

Dans 3D Printer OS cliquer sur **Printers** puis sur ![](images/3dprinteros/points.jpeg){ align=center width="30" class="off-glb"} et sur **Add workgroup Printers**  
Demander le code d'accès au responsable.

![](images/3dprinteros/workgroup.jpeg)

---
### 3. Ajout du fichier d'impression à 3D Printer OS

### 4. L'ancement de l'impression

### 5. Préparation de l'imprimante 3D

Vérifier sur l'imprimante 3D :  
- Que le plateau d'impression est vide est sans résidu  
- Que le plateau soit bien positionner  
- Que rien ne gènes les axes  
- Que la quantité de filaments est suffisante pour votre impression (voir onglet aperçu de Bambu Studio)  

### 6. Previnir 
**Apres le démarrage de l'impression il faut impérativement rester pour vérifier les premières couches d'impression.**  
C'est souvent à ce moment que l'on détecté les problèmes d'impression.

