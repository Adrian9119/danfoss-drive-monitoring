# danfoss-drive-monitoring

## 🇬🇧 English

Web application for technicians and clients to **monitor, log, and control** Danfoss drives over **Modbus TCP**. **Real-time** visualization, **custom alerts**, and full control over displayed parameters.

**Oriented for**: clients who want to supervise all their drives, or technicians for maintenance purposes.

### Features
- 🧠 Real-time monitoring of Danfoss drive parameters  
- 📝 Read and write to drive settings via Modbus TCP  
- ⚠️ Fault code logging and customizable alerts with email notifications  
- 📊 Analog input scaling and configurable real-time data  
- 🗂️ Organize equipment into different zones within an installation  
- 🌐 Secure remote access through OpenVPN  

### Tech Stack
- **Frontend**: React, TypeScript, ECharts, Socket.IO (client)  
- **Backend**: Flask (Python), PyModbus, Flask-SocketIO, SQLAlchemy  
- **Database**: MySQL  
- **Connectivity**: Modbus TCP over OpenVPN  
- **Communication**: WebSocket with Socket.IO  

---

## 📸 Screenshots

### 1) Installations Dashboard
Dashboard to control all zones within each installation.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/cc59797b-4857-47f7-a99e-919f465cdcab" alt="Installations dashboard" width="90%" />
</p>

### 2) Zone Dashboard
Configure each zone independently by assigning groups of variables and displaying its key data.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/c577e189-7304-443c-8bd1-d34ea6caa650" alt="Zone dashboard" width="90%" />
</p>

### 3) Drive Access
Access each drive to view its parameters or favorites.  
<div align="center">
  <img src="https://github.com/user-attachments/assets/e2f9fed7-62c2-4387-bbfc-343f26b4a718" alt="Access parameters and favorites" width="49%" />
  <img src="https://github.com/user-attachments/assets/b715af4d-24d8-4414-b419-99804507ac88" alt="Edit parameters easily" width="49%" />
</div>

### 4) Favorites
Add key variables to favorites and link parametrization parameters to visualization parameters using color codes.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/fd0bae97-159f-4a1d-967f-87521f2008a6" alt="Favorites with parameter linking" width="90%" />
</p>

### 5) Variable Logging
Log variables to improve maintenance, prevent breakdowns, and generate reports.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4dc545b-4ff5-411f-8688-f64798c1fda7" alt="Variable logging" width="90%" />
</p>

### 6) Fault History & Instant Alerts
Access the fault history and get notified by email when one occurs.  
<div align="center">
  <img src="https://github.com/user-attachments/assets/9958817d-b6a8-4c7e-8f86-641d7a600215" alt="Fault history" width="65%" />
</div>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f50a428a-4fe8-4573-9832-88a5a4f86d14" alt="Email alert example" width="65%" />
</p>



## 🇪🇸 Español

Aplicación web para técnicos y clientes para **monitorizar, registrar y controlar** variadores Danfoss vía **Modbus TCP**. Visualización en **tiempo real**, **alertas personalizadas** y control total sobre los parámetros mostrados.

**Orientado a**: clientes que quieran supervisar todos sus variadores, o técnicos para funciones de mantenimiento.

### Características
- 🧠 Monitorización en tiempo real de parámetros de variadores Danfoss  
- 📝 Lectura y escritura de ajustes del variador vía Modbus TCP  
- ⚠️ Registro de códigos de fallo y alertas personalizables con envío de email  
- 📊 Escalado de entradas analógicas y datos en tiempo real configurables  
- 🗂️ Organización de equipos por zonas dentro de una instalación  
- 🌐 Acceso remoto seguro a través de OpenVPN  

### Stack Tecnológico
- **Frontend**: React, TypeScript, ECharts, Socket.IO (cliente)  
- **Backend**: Flask (Python), PyModbus, Flask-SocketIO, SQLAlchemy  
- **Base de Datos**: MySQL  
- **Conectividad**: Modbus TCP sobre OpenVPN  
- **Comunicación**: WebSocket con Socket.IO  

---

## 📸 Capturas de pantalla

### 1) Dashboard de las instalaciones
Dashboard para tener un control de todas las zonas de cada instalación.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/cc59797b-4857-47f7-a99e-919f465cdcab" alt="Dashboard de instalaciones" width="90%" />
</p>

### 2) Dashboard de la zona
Configura cada zona de manera independiente asignando grupos de variables y mostrando los datos más importantes.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/c577e189-7304-443c-8bd1-d34ea6caa650" alt="Dashboard de zona" width="90%" />
</p>

### 3) Acceso a cada variador
Accede a cada variador para ver sus parámetros o favoritos.  
<div align="center">
  <img src="https://github.com/user-attachments/assets/e2f9fed7-62c2-4387-bbfc-343f26b4a718" alt="Acceso a parámetros y favoritos" width="49%" />
  <img src="https://github.com/user-attachments/assets/b715af4d-24d8-4414-b419-99804507ac88" alt="Modificación de parámetros" width="49%" />
</div>

### 4) Favoritos
Añade variables clave a favoritos y vincula parámetros de parametrización a visualización con códigos de color.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/fd0bae97-159f-4a1d-967f-87521f2008a6" alt="Favoritos con vinculación de parámetros" width="90%" />
</p>

### 5) Registro de variables
Registra variables para mejorar el mantenimiento, evitar averías y generar informes.  
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4dc545b-4ff5-411f-8688-f64798c1fda7" alt="Registro de variables" width="90%" />
</p>

### 6) Historial de fallos y alertas instantáneas
Accede al historial de fallos y recibe notificaciones por email al producirse uno.  
<div align="center">
  <img src="https://github.com/user-attachments/assets/9958817d-b6a8-4c7e-8f86-641d7a600215" alt="Historial de fallos" width="65%" />
</div>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f50a428a-4fe8-4573-9832-88a5a4f86d14" alt="Ejemplo de email de alerta" width="65%" />
</p>

