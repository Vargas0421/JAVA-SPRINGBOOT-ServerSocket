# JAVA-ServerSocket

# ClienteServidor  

## 📌 Proyecto Cliente-Servidor Concurrente en Java  

Este proyecto implementa una aplicación **cliente-servidor concurrente** en **Java**, con un front-end sencillo desarrollado en **Swing**.  
El sistema permite la gestión de usuarios, inventario y compras, utilizando **sockets** para la comunicación y **Gson** para la serialización de objetos.  

---

## ✅ Logros alcanzados
- Uso de **Gson** para serializar y deserializar información (usuarios, artículos, etc.).  
- Conexión cliente-servidor mediante **sockets**.  
- Vista de invitados con Swing.  
- Implementación de **login** de usuarios.  
- Verificación básica de credenciales.  

---

## 🕒 Funcionalidades pendientes
- Carrito de compras.  
- Manejo de fondos para clientes.  

---

## 📝 Descripción general
El proyecto permite:  
- Registrar nuevos clientes.  
- Registrar artículos en inventario.  
- Visualizar inventario (con filtrado por tipo de producto).  
- Realizar compras (en desarrollo).  

El sistema se organiza bajo una arquitectura **MVC**, donde:  
- El **servidor** gestiona la lógica de negocio y mantiene los objetos de sesión.  
- El **cliente** es la interfaz Swing desde donde los usuarios interactúan.  
- La **comunicación** se da por medio de **sockets TCP**.  

---

## 🛠️ Tecnologías utilizadas
- **Java** (Sockets, Threads, Swing)  
- **Gson** (serialización JSON)  
- **MySQL** (persistencia de datos, en desarrollo)  

---

## 👨‍💻 Autor
Proyecto desarrollado por:  
**Brandon Vargas** 😊  
