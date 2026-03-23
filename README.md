# Aplicacio-Videojocs
Aplicacio Videojocs DIGISOS
Aplicacio de Videojocs que crea, actualitza, llista i elimina jocs afegits a la base de dades.
Creació de taula en la base de dades:
  CREATE TABLE videojuegos(
    id bigint unsigned not null  primary key auto_increment,
    nombre varchar(255),
    descripcion varchar(255)
  );
