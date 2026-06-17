Voici le contenu au format **README.md** que tu peux copier directement dans un fichier `README.md` :

````markdown
# Commandes Linux les Plus Utilisées

## 📁 Navigation dans le système de fichiers

### Afficher le répertoire courant

```bash
pwd
```

### Lister les fichiers

```bash
ls
ls -l     # format détaillé
ls -a     # afficher les fichiers cachés
ls -lh    # tailles lisibles
```

### Changer de répertoire

```bash
cd /home/user
cd ..
cd ~
```

---

## 📂 Gestion des fichiers et dossiers

### Créer un fichier

```bash
touch fichier.txt
```

### Créer un dossier

```bash
mkdir mon_dossier
```

### Copier des fichiers

```bash
cp fichier.txt sauvegarde.txt
cp -r dossier1 dossier2
```

### Déplacer ou renommer

```bash
mv ancien.txt nouveau.txt
mv fichier.txt /tmp/
```

### Supprimer

```bash
rm fichier.txt
rm -r dossier
rm -rf dossier
```

---

## 📄 Affichage du contenu des fichiers

### Afficher un fichier

```bash
cat fichier.txt
```

### Afficher les premières lignes

```bash
head fichier.txt
```

### Afficher les dernières lignes

```bash
tail fichier.txt
```

### Suivre un fichier de logs

```bash
tail -f application.log
```

### Lecture interactive

```bash
less fichier.txt
```

---

## 🔍 Recherche

### Rechercher un fichier

```bash
find /home -name "*.txt"
```

### Rechercher dans le contenu

```bash
grep "erreur" fichier.log
```

### Recherche récursive

```bash
grep -r "docker" .
```

---

## ⚙️ Gestion des processus

### Afficher les processus

```bash
ps
ps aux
```

### Surveillance temps réel

```bash
top
```

ou

```bash
htop
```

### Arrêter un processus

```bash
kill PID
```

### Forcer l'arrêt

```bash
kill -9 PID
```

---

## 🔐 Gestion des permissions

### Afficher les permissions

```bash
ls -l
```

### Modifier les permissions

```bash
chmod 755 script.sh
chmod +x script.sh
```

### Changer le propriétaire

```bash
chown utilisateur:groupe fichier
```

---

## 👤 Gestion des utilisateurs

### Utilisateur courant

```bash
whoami
```

### Informations utilisateur

```bash
id
```

### Changer d'utilisateur

```bash
su utilisateur
```

### Exécuter avec sudo

```bash
sudo commande
```

---

## 🌐 Réseau

### Afficher les adresses IP

```bash
ip addr
```

### Tester la connectivité

```bash
ping google.com
```

### Voir les ports ouverts

```bash
ss -tulpn
```

### Télécharger un fichier

```bash
wget URL
```

ou

```bash
curl -O URL
```

---

## 💾 Gestion du stockage

### Utilisation des disques

```bash
df -h
```

### Taille d'un dossier

```bash
du -sh dossier
```

---

## 📦 Compression et archivage

### Créer une archive

```bash
tar -cvf archive.tar dossier
```

### Extraire une archive

```bash
tar -xvf archive.tar
```

### Créer une archive compressée

```bash
tar -czvf archive.tar.gz dossier
```

### Extraire une archive compressée

```bash
tar -xzvf archive.tar.gz
```

---

## 🖥️ Historique et terminal

### Historique des commandes

```bash
history
```

### Réexécuter la dernière commande

```bash
!!
```

### Nettoyer l'écran

```bash
clear
```

---

## 📊 Informations système

### Informations sur le noyau

```bash
uname -a
```

### Informations système

```bash
hostnamectl
```

### Mémoire RAM

```bash
free -h
```

### Utilisation CPU

```bash
top
```

---

## 🚀 Gestion des services (Systemd)

### Vérifier l'état d'un service

```bash
systemctl status nginx
```

### Démarrer un service

```bash
systemctl start nginx
```

### Arrêter un service

```bash
systemctl stop nginx
```

### Redémarrer un service

```bash
systemctl restart nginx
```

### Activer au démarrage

```bash
systemctl enable nginx
```

### Désactiver au démarrage

```bash
systemctl disable nginx
```

---

## 📝 Logs système

### Afficher les erreurs récentes

```bash
journalctl -xe
```

### Logs d'un service

```bash
journalctl -u nginx
```

### Suivre les logs en temps réel

```bash
journalctl -f
```

---

## ⭐ Top 20 des commandes indispensables

```bash
ls -la
cd
pwd
cat
grep
find
cp
mv
rm
chmod
chown
ps aux
top
kill
systemctl
journalctl
ip addr
ss -tulpn
df -h
du -sh
sudo
```

---

## 📚 Conseils

- Utilisez `man <commande>` pour consulter la documentation.
- Utilisez `--help` pour obtenir l'aide rapide.

Exemples :

```bash
man grep
ls --help
```

---

**Auteur :** Votre guide Linux  
**Version :** 1.0
````

Ce README est prêt à être utilisé sur GitHub, GitLab ou dans votre documentation de formation Linux.
