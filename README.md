# PROFU2-SERVIDOR
es un serviddor que provee informacion a un chat interactivo

# 🚀 MySQL Docker Setup
Este proyecto utiliza **Docker** para levantar un contenedor de **MySQL** fácilmente, gestionando las credenciales mediante un archivo `.env`.

---

# Levantar el contenedor
docker-compose up -d

# Entrar al contenedor (opcional)
docker exec -it mysql_container mysql -u usuario_app -p clave_app mi_basededatos