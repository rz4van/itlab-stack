# itlab-stack
Infraestructura IT basada en Docker con GLPI, NetBox y Wazuh para gestión, monitoreo y seguridad en entornos productivos.


Este proyecto integra:

- 🧾 **GLPI** – Mesa de ayuda y gestión IT
- 🌐 **NetBox** – Gestión de red e inventario
- 🛡️ **Wazuh** – SIEM / XDR
- 📂 **Samba** – Servidor de archivos
- 🐳 **Docker + Docker Compose** – Orquestación

---

## 📌 Objetivo del Proyecto

Crear una **plataforma unificada de infraestructura IT** reutilizable para:

- Laboratorios de ciberseguridad
- Soporte técnico empresarial
- Entornos de prueba SOC
- Freelance IT / MSP

---


## 🧱 Arquitectura General

               Usuarios
                   v
               Navegador 
                   v
         GLPI | NetBox | Wazuh Dash 
                   v
            Docker Bridge Network |
                   v
    MariaDB | PostgreSQL | OpenSearch | Wazuh MGR 
                   v
              Samba Server 


---

## 🚀 Requisitos

- Ubuntu Server 20.04+
- Docker
- Docker Compose
- 4 GB RAM mínimo (8 GB recomendado)
- 40 GB de disco mínimo

