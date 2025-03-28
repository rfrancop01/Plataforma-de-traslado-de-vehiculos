# Plataforma de Traslado de Vehículos

Este proyecto es una aplicación diseñada para conectar a clientes que necesitan trasladar sus vehículos con proveedores especializados de transporte. La plataforma calcula automáticamente la distancia entre el origen y el destino para generar una cotización, optimiza la logística del traslado y permite a los transportistas gestionar solicitudes de manera eficiente.

## Características

- **Conexión Cliente-Transportista**: Facilita la comunicación entre clientes y proveedores de transporte especializados.
- **Cálculo Automático de Distancias**: Utiliza herramientas de geolocalización para determinar la distancia entre el punto de recogida y el destino.
- **Generación de Cotizaciones**: Basado en la distancia calculada, la plataforma proporciona una estimación del costo del traslado.
- **Gestión de Solicitudes**: Los transportistas pueden aceptar, rechazar y gestionar las solicitudes de traslado de manera eficiente.
- **Optimización Logística**: Ayuda a planificar rutas y horarios para maximizar la eficiencia en los traslados.

## Tecnologías Utilizadas

- **Frontend**: React.js
- **Backend**: Python con Flask
- **Base de Datos**: SQLAlchemy
- **Estilización**: Bootstrap
- **Autenticación**: Flask-JWT-Extended
- **Geolocalización**: APIs de mapas para cálculo de distancias

## Instalación

1. **Clona este repositorio** en tu máquina local:

   ```bash
   git clone https://github.com/rfrancop01/Plataforma-de-traslado-de-vehiculos.git
   ```

2. **Navega al directorio del proyecto**:

   ```bash
   cd Plataforma-de-traslado-de-vehiculos
   ```

3. **Configura el entorno virtual** (opcional pero recomendado):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

4. **Instala las dependencias del backend**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Configura las variables de entorno**. Crea un archivo `.env` en la raíz del proyecto y añade las variables necesarias según el archivo `.env.example` proporcionado.

6. **Inicializa la base de datos**:

   ```bash
   flask db upgrade
   ```

7. **Inicia el servidor backend**:

   ```bash
   flask run
   ```

8. **Instala las dependencias del frontend**:

   ```bash
   npm install
   ```

9. **Inicia el servidor frontend**:

   ```bash
   npm start
   ```

## Uso

- **Registro e Inicio de Sesión**: Los clientes y transportistas pueden registrarse e iniciar sesión para acceder a las funcionalidades de la plataforma.
- **Solicitud de Traslado**: Los clientes pueden ingresar detalles del vehículo y las direcciones de origen y destino para solicitar un traslado.
- **Gestión de Solicitudes**: Los transportistas pueden ver las solicitudes disponibles y aceptar aquellas que deseen gestionar.
- **Seguimiento**: Los clientes pueden rastrear el estado de su solicitud y recibir actualizaciones en tiempo real.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto:

1. **Haz un fork** del repositorio.
2. **Crea una nueva rama** para tu característica o mejora:

   ```bash
   git checkout -b nombre-de-tu-rama
   ```

3. **Realiza tus cambios** y confirma los commits:

   ```bash
   git commit -m "Descripción de los cambios"
   ```

4. **Empuja tus cambios** a tu fork:

   ```bash
   git push origin nombre-de-tu-rama
   ```

5. **Abre un Pull Request** en este repositorio describiendo tus modificaciones.

## Licencia

Este proyecto se encuentra bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Créditos

Desarrollado por Marcos Sevilla, Natalia Manzano y Ricardo Franco Pérez.

---

*Este proyecto fue desarrollado como parte del curso de Full Stack Developer en [4Geeks Academy](https://4geeksacademy.com).*
