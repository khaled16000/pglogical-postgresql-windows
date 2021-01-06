Francais

remarque: ces etapes de fonctionnement de pglogical (plateforme windows)sauf avec postgresql version 10.4 pour 64 bit et pglogical v- 2.3.0
si vous cherchez l'extention pglogical pour une version differente de postgresql n'hesitez pas à nous contacter 
Instructions:
1-arreter le service postgresql
2-copier le fichier executable bin_exe_files_postgresql/postgresql.exe et le faire remplacer dans vos postgres suivant ce chemin:\PostgreSQL\10\bin
3-copier le fichier executable bin_exe_files_pglogical/pglogical_create_subscriber.exe et le faire remplacer dans vos postgres suivant ce chemin:\PostgreSQL\10\bin
4-copier ces deux fichiers DLL "lib_dll_pglogical/pglogical.dll" et "lib_dll_pglogical/pglogical_output.dll" dans le chemin suivant:\PostgreSQL\10\lib
5- copier share_sql_files_pglogical/.* dans le chemin suivant:\PostgreSQL\10\share\extension (PS: .* veut dire tous les fichiers dans le repertoire 'share_sql_files_pglogical')
6- demarrer le service postgresql

apres avoir finir les etapes en dessus, voici le lien de documentation pour compléter l'installation et la configuration final de votre replication


English 

note: these pglogical configuration steps (windows platform) except with postgresql v- 10.4 for 64 bit and pglogical v- 2.3.0
if you are looking for pglogical extension for a different version of postgresql do not hesitate to contact us
Instructions:
1-stop the postgresql service
2-copy the bin_exe_files_postgresql / postgresql.exe executable file and have it replaced in your postgres following this path: \ PostgreSQL \ 10 \ bin
3-copy the bin_exe_files_pglogical / pglogical_create_subscriber.exe executable file and have it replaced in your postgres following this path: \ PostgreSQL \ 10 \ bin
4-copy these two DLL files "lib_dll_pglogical / pglogical.dll" and "lib_dll_pglogical / pglogical_output.dll" in the following path: \ PostgreSQL \ 10 \ lib
5- copy share_sql_files_pglogical /.* in the following path: \ PostgreSQL \ 10 \ share \ extension (PS:. * Means all files in the 'share_sql_files_pglogical' directory)
6- start the postgresql service

after finishing the steps above, here is the documentation link to complete the installation and final configuration of your replication