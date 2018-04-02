#---------------------------
README.txt
ReadTachebak
tacheron
tacherontab
#---------------------------

ReadTachebak: script pour lire et si possible executer la tache ecrit dans
tacherontab.

           tout d'abord on change la date pour l'instant sous format:
              sec min heure jour moi jinsemaine
           

           preTraite() ----- traiter les champs comme |- 1
                                                      |- 1,3,4,7
                                                      |- 1-12
                                                      |- 1-12~3

           check_champ() --- traiter les champs comme |- *
                                                      |- */5
                             si ce n'est pas le cas, il fait l'appel à preTraite

           enfin, on lit chaque champ dans tacherontab et on le transféfè au
 format chiffre et on compare.
           

tacherontab: script pour traiter la commande:
           tacherontab [-u user] {-l | -r | -e}
             on le met dans /usr/local/bin
             

                                                      
           

tacheron: script general qu'on met dans /etc/init.d
          
