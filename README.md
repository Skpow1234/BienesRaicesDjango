# Real-Estate-Django-Postgres

**IMPORTANTE:** El logo mostrado, es un logo de ejemplo, dado que aún no ha sido determinado por el cliente final, dado que esto es una aplicación con fin educativo, pero que se está llegando a un acuerdo para la posterior venta y apropiación del mismo.

## Desarrollado por Juan Felipe Hurtado

## Propósito

Aplicación de consulta de propiedad raíz, para poder ponerse en contacto con agentes de bienes raíces, donde puede consultar por la casa o apartamento vista, poner a la venta su propia propiedad si la tiene en Estados Unidos, e inclusive ponerlo en renta, mediante el cliente final que hace todas estas operaciones.

## Instalación e instrucciones

### Instalación

1. Clona el repositorio:

```bash
git clone 
```

2.Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
```

3.Activa el entorno virtual:

- En Windows:

```bash
venv\Scripts\activate
```

4.Instala las dependencias del proyecto:

```bash
pip install -r requirements.txt
```

5.Aplica las migraciones de la base de datos:

```bash
python manage.py migrate
```

6.Crea un superusuario para acceder al panel de administración de Django:

```bash
python manage.py createsuperuser
```

7.Inicia el servidor de desarrollo:

```bash
python manage.py runserver
```

8.Accede al servidor de desarrollo en <http://localhost:8000/>, regístrate como un nuevo usuario e inicia sesión en la aplicación.

9.El panel de administración se puede acceder con las credenciales de superusuario en <http://localhost:8000/admin/>

### Instrucciones

1.Desde el panel de administrador, deben ser ingresados datos de ejemplo, para el buen funcionamiento de la aplicación
2.Crear un superusuario primero, antes de crear un usuario fuera de lo común, sino, la autenticación de la aplicación, denegara el ingreso

## Datos a tener en cuenta

MVP significa: Market Value Pricing
La aplicación es diseñada para que desde Colombia se puedan consultar precios y características de casas o apartamentos en Estados Unidos, ponerse en contacto con agentes de bienes raíces, y que ellos los informen sobre todo, y puedan sacar citas
