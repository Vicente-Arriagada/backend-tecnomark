#Backend Strapi CMS 

El proyecto utiliza la siguiente arquitectura:

* **Cms:** [Strapi](https://strapi.io/) (Headless CMS v5).
* **Base de Datos:** [Neon](https://neon.tech/) (Serverless Postgres).
* **Almacenamiento de imagenes:** [Cloudinary](https://cloudinary.com/) (Imágenes).
* **Hosting** [Render](https://render.com/) (Web Service).
* **Lenguaje:** Node.js.
---
##  Pre-requisitos
Antes de iniciar, asegúrate de tener instalado:

* **Node.js** (v22.21.1).
* **npm**.
---

## instalacion de proyecto
1. clonar repositorio git
2.  Crea un archivo `.env` en la raíz del proyecto.
3.  Copia el siguiente contenido en archivo `.env`:

```env

# Server
HOST=0.0.0.0
PORT=1337

# Secrets
APP_KEYS=ye7IW4zBknktUaVmdgh3ww==,rRqakxjZunQ8eJ7AkEPRLA==,rz982bYhAG/WFy+L/fKT4w==,052nLAFYfqmgwy3LATWXNg==
API_TOKEN_SALT=OtHzmNX+kGpRGPv9aV3jNA==
ADMIN_JWT_SECRET=CU2Fm38p3+/2nxIxsY42Kw==
TRANSFER_TOKEN_SALT=lthHJEQCBM/maXT39wRdhA==
ENCRYPTION_KEY=e3T0MzCNOJQZRSOFaUStjg==

# Database
DATABASE_CLIENT=postgres
DATABASE_HOST=ep-sparkling-sky-a4ahc6mf-pooler.us-east-1.aws.neon.tech
DATABASE_PORT=5432
DATABASE_NAME=strapibackend
DATABASE_USERNAME=neondb_owner
DATABASE_PASSWORD=npg_dXxVasIu4R2t
DATABASE_SSL=true
DATABASE_FILENAME=
JWT_SECRET=IcpCKGr9NLYXvHMZbvz9zA==

CLOUDINARY_NAME=dmr55rwxg
CLOUDINARY_KEY=824387694166623
CLOUDINARY_SECRET=eYSzFMBI5xTfs4uHHZvE4481kGg
