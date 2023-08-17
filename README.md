# cdatest-package

Skeleton pour faire un paquet 'deb', avec la commande dpkg-deb

# Compilation du paquet:
```$ sudo dpkg-deb --build nom_du_paquet```

# Installation du paquet:
```$ sudo dpkg -i nom_du_paquet.deb```

# Desinstallation du paquet:
```$ sudo dpkg -r nom_du_paquet```
ou 
```$ sudo apt-get remove nom_du_paquet```



### Ressources: 
- http://sdz.tdct.org/sdz/creer-un-paquet-deb.html
- https://alp.developpez.com/tutoriels/debian/creer-paquet/
