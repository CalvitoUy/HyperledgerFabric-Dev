En esta carpeta estan los bash para pre-instalación e instalación de componentes cuando estamos detras de un proxy.
Es importante haber configurado las variables de hambiente para el proxy con el comando EXPORT

export http_proxy="http://<user name>:<password>@<proxy name/IP>:<proxy port>/"
export https_proxy="http://<user name>:<password>@<proxy name/IP>:<proxy port>/"

Nota 1: cada vez que uses el sudo para instalar recuerda agregar le -E para que use las variables de ambiente del usuario.
Nota 2: si tu password tienen caracteres especiales recuerda cambiarlos por le UNICODE respectivo ej: $ serial %24
