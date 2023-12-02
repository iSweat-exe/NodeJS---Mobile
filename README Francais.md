# Server NodeJS - Mobile setup

## 0. Prerequis
**Telephone Android** ( **Android 11 ou superieur**) <br />
Installer l'application "**Termux**" [Ici](https://github.com/termux/termux-app/releases) <br />
Essayez d'installer les deux, puis testez lequel des deux fonctionne. :

   ![Image Installation](Imports/image1.png)<br />
   ![Image Installation](Imports/image2.png)

# Ouvrir Termux


## 1. Installer les Packages
**Etape 1 :** : Réponds avec "Y" à toutes les requêtes
```bash
pkg update -y
```
**Etape 2 :**
```bash
pkg upgrade -y
```

**Etape 3 :** : Réponds avec "Y" à toutes les requêtes.
```bash
pkg install nodejs -y
```

**Etape 4 :** *Vérification*
```bash
node -v
```
**resultat :**
```
vXX.XX.X
```

### Now you are ready to start your server with NodeJS

**Etape 1 :**
- Maintenant, placez les fichiers/dossiers dans le dossier Téléchargements de votre téléphone, à l'aide d'un gestionnaire de fichiers trouvé sur le Play Store (par exemple, Gestionnaire de fichiers, ZArchiver).

**Etape 2 :**
- Allez sur **Termux** et taper : 
```bash
termux-setup-storage
```

### **Maintenant redémarre complètement Termux. (Voir notification du telephone)** <br />

**Etape 3 :**
- Allez sur **Termux** et taper:
```bash
cd /storage/shared/Download
```

**Etape 4 :**
```bash
cd <Your files>
```

et c'est terminé !
Vous pouvez utiliser NodeJS pour votre projet (bots Discord et bien plus encore).