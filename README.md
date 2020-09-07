# Peruanos Dev Streamers 

¡Hola!. Estamos creando un directorio de streamers en youtube / twitch o facebook que estén haciendo código en video.

El cual pretende resolver el problema de:

- Quiero ver sobre tema X , pero no se que canales seguir.


### ¿Quieres ser un speaker? 
Envíanos un PR con tus datos para figurar en el listado. 

Pasos: 
1. Crear un archivo con los datos de tu canal en el directorio _streamers
    ```
    $ vi _streamers/CanalYoutube.md
    ```
2. Registrar tus datos

    ```
    ---
    name: Nombre y Apellidos
    topics: Lista las tecnologias que usas
    picture: https://your-picture
    email: micorreo@domain.com
    github: 'https://www.github.com/username'
    twitter: 'https://twitter.com/username'
    linkedin: 'https://www.linkedin.com/in/username' 
    ---
    
    Agrega tu bio y personalizalo usando **markdown**
    ```
    
3. Envia tu Pull Request

### Setup Deveploment
To start this application locally:

1. Make sure you have installed Ruby
2. Install the dependencies: `bundle install`
3. Start the application: `bundle exec jekyll serve`
4. Go to the [app](http://127.0.0.1:4000)
