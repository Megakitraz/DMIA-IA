# DMIA-IA

Set up:
pour la base
Avec brain[5] il est possible de choisir avec quelle type de vaisseau nous souhaitons commencer (On doit commencer avec 7 vaisseaux au total)
brain[5].x = harvester
brain[5].y = missile
brain[5].z = explorer


Turtles contient toutes les informations sur les robots (nombre de bullets, couleur de l'équipe etc...)

ligne 384 de Turtles pour mettre/retirer le cercle de perception

perceiveFafs() et perceiveFafsInCone() pour détecter les FAFS, on peut alors utiliser la liste des missiles pour les esquiver

informAbotTarget : INFORM_ABOUT_TARGET 
      float[] args = new float[4];
      args[0] = target.pos.x;
      args[1] = target.pos.y;
      args[2] = target.breed;
      args[3] = target.who;    
