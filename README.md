# 📦 ldap_ldapphpadmin

Stack de autenticación y administración LDAP listo para producción.  
Incluye **OpenLDAP**, **phpLDAPadmin** y un servicio de **backups automáticos**.

---

## 🔧 Componentes

### OpenLDAP Server
- Backend robusto: **MDB**
- Soporte para **SSL/TLS**
- **Healthchecks** configurados
- Variables de entorno organizadas
- Estructura de OUs preconfigurada

### 🌐 phpLDAPadmin
- Interfaz web moderna
- Configuración optimizada
- Dependencia correcta del servidor LDAP

### 💾 Servicio de Backup
- Backups automáticos diarios
- Retención configurable
- Activación opcional con profiles

---

## ⚙️ Funcionalidades Avanzadas
✅ Persistencia de datos con volúmenes nombrados  
✅ Red aislada para los servicios  
✅ Healthchecks para monitoreo  
✅ Scripts de gestión completos  
✅ Configuración SSL lista  
✅ Sistema de backup automatizado  
✅ Variables de entorno centralizadas  

---

## 🚀 Uso en Producción
Antes de desplegar el stack en producción:

1. Cambia las contraseñas en el archivo **`.env`**  
2. Personaliza el dominio según tu organización  
3. Genera certificados SSL reales  
4. Configura el **firewall** apropiado  
5. Activa el servicio de backup  

---

## 📂 Estructura
ldap_ldapphpadmin/
├── docker-compose.yml
├── .env
├── backup/
│ ├── scripts/
│ └── data/
└── certs/


---

## 🛠️ Requisitos
- Docker >= 20.x  
- Docker Compose >= 2.x  

---


