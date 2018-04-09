# ArqWeb

Integrantes:

- Gaston Grobas
- Ernesto De Lisi

Descripcion: El negocio elegido es una concesionaria de autos usados donde cada usuario puede cargar usados de la lista a su cuenta, como agregar autos en seguimiento, además de buscarlos por marca y modelo. 
Ademas cada usuario puede solicitar test drives y sacar turnos para ello.

Host --> http://concesionaria.com

/users --> create, login, logout, updateUser, deleteUser

/cars --> addCar, updateCar, findByModel, findByMark, findById

Entonces los endpoints que manejamos hasta el momento son:

/users --> create user
/users/login ---> login user
/users/logout --> logout user
/user/{username} --> user especifico

/cars/list --> listado de autos
/cars/model/X --> listado de autos de un modelo particular
/cars/mark/x --> listado de autos de una marca en particular
/cars/{carId} --> auto por id
/user/{username}/cars/myList --> lista de autos seleccionados por un usuario particular
