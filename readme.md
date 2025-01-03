# OpticksMarket

## Requisitos

### Backend (Koa.js)
- Node.js 22
- Archivo `.env`
  ```env
  DB_HOST=
  DB_PORT=
  DB_NAME=
  DB_USER=
  DB_PASS=
  SERVER_PORT=
  ```

  **Nota:** Es necesario tener PostgreSQL para correr localmente.

### Frontend (Next.js)
- Node.js 22
- Archivo `.env`
  ```env
  NEXT_PUBLIC_BACKEND_URL=
  ```

## Instrucciones

### Backend
1. Clonar el repositorio.
2. Navegar al directorio del backend:
  ```bash
  cd backend
  ```
3. Instalar las dependencias:
  ```bash
  npm install
  ```
4. Crear un archivo `.env` en el directorio del backend con las variables de entorno necesarias.
5. Iniciar el servidor:
  ```bash
  npm start
  ```

### Frontend
1. Clonar el repositorio.
2. Navegar al directorio del frontend:
  ```bash
  cd frontend
  ```
3. Instalar las dependencias:
  ```bash
  npm install
  ```
4. Crear un archivo `.env` en el directorio del frontend con las variables de entorno necesarias.
5. Iniciar la aplicación:
  ```bash
  npm run dev
  ```

### Usando Docker
1. Clonar el repositorio.

2. Levantar la aplicación completa:
  ```bash
  docker-compose up
  ```
3. Visitar [http://localhost](http://localhost) en tu navegador.

## Notas
- Asegúrate de tener Docker y Docker Compose instalados en tu sistema.
- Las variables de entorno necesarias deben ser definidas en los archivos `.env` correspondientes.
- Esta app usa el puerto HTTP, ojalá que no haya nada corriendo ahí al momento de levantar el contenedor.
