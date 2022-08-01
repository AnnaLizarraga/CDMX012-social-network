- [Español](#-Red-Social-Solovino.)
- [English](#-Social-Network-Solovino.)

 # <h1 align="center"> Red Social Solovino. 🐾</h1>

![Show Mockups](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20CV/Projects/RedSocial.jpg)

<p align="center">Despliegue del proyecto:</p>
<p align="center">En proceso...</p>

***

## Índice

- [1. Resumen del proyecto](#1.-Resumen-del-proyecto)
- [2. Tech Skills del Proyecto](#2.-Tech-Skills-del-Proyecto)
- [3. Planeación](#3-Planeación)
- [4. Investigación UX](#4.-Investigación-UX)
- [5. Bocetaje + Prototipo + Feedback ](5.-Bocetaje-+-Prototipo-+-Feedback-de-iteración)

---

## 1. Resumen del proyecto

- DESCRIPCIÓN

Las redes sociales están conectando al mundo entero, es por ello que se llevó a cabo la implementación de una Red Social, la cual lleva por nombre: "Solovino.

Fue diseñada para fomentar la adopción responsable de perritos, así como compartir sus vivencias con sus compañeros perrunos.

- RESUMEN TÉCNICO

Su implementación es un SPA (single-page application) optimizada para móviles. permite a cualquier usuario crear una cuenta de acceso mediante correo y contraseña o loguearse mediante Google, Facebook y Twiter. Es así como el usuario tendrá acceso al timeline en donde podrá crear posts y podrá ver posts de otros usuarios e interactuar con ellos mediante un botón de like. Únicamente el usuario que crea el post podrá editarlo y eliminarlo.

<br></br>

---

## 2. Tech Skills del Proyecto

### HTML 5

- Semántico

### CSS 3

- Selectores de CSS
- Box Model
- Flexbox
- Grid Layout

### Web APIs

- Uso de selectores del DOM
- Manejo de eventos del DOM
- Manipulación dinámica del DOM
- Ruteado

### JavaScript ES6 Vanilla

- Datos primitivos
- Strings
- Variables
- Funciones
- Condicionales
- Bucles/ciclos
- Arrays
- Objetos
- Callbacks
- Promesas
- Pruebas unitarias (unit tests)
- Pruebas asíncronas
- Uso de mocks y espías
- Módulos de ECMAScript.
- Uso de linter (ESLINT)

### Firebase

- Firebase Auth
- Firestore

### Control de versiones Git- Github

- Git: Init, clone, add, commit, status, push, pull, remote, checkout
- Git: Integración de los cambios entre ramas (branch, checkout, fetch, merge, reset, rebase, tag)
- GitHub: Despliegue con Netlify.

### User-centricity

- Diseñar un producto o servicio poniendo a la usuaria en el centro

### Product-design

- Crear prototipos de alta fidelidad que incluyan interacciones
- Seguir los principios básicos de diseño visual

### Research

- Planear y ejecutar testeos de usabilidad de prototipos en distintos niveles de fidelidad (Maze)

<br></br>

---

## 3. Planeación

Este proyecto se realizó con metodologías agiles SCRUM en 5 sprints de 1 semana en la cual se trabajaron historias de usuario.

Puedes ver la planeación [aquí](https://trello.com/b/k289jcSl/social-network)

<br></br>

- HISTORIAS DE USUARIO

### Historia de Usuario 1: ACCEDER A LA APP CON PROVEDORES

Yo como usuario quiero poder ingresar a mi cuenta a través de Gmail o Facebook para que sea más práctico y fácil el acceso

CRITERIOS DE ACEPTACIÓN

- Que el usuario pueda visualizar los iconos para su acceso.
- El usuario podrá elegir cualquiera de las dos opciones para accesar.
- Que el usuario visualice y acepte los términos y condiciones
- Que el usuario pueda quedar registrado y se guarde su cuenta.
- Tener acceso a la página de crear perfil o ingresar al timeline mediante un botón

DEFINICIÓN DE TERMINADO

- Conectar con Firebase
- Función de guardado de información
- Poder aceptar términos y condiciones como requisito
- El botón te redirija a la sección de crear perfil de usuario
- Diseño sea similar al prototipo
- Ser responsive
- Test unitarios
- Code Review
- Debe ser SPA
- Prueba de usabilidad

### Historia de Usuario 2: LOG IN CON CUENTA REGISTRADA

Yo como usuario quiero poder ingresar mis datos de correo electrónico y contraseña para entrar a la app

CRITERIOS DE ACEPTACIÓN

- Que el usuario pueda visualizar los campos para su acceso.
- El usuario podrá ingresar contraseña para accesar.
- La contraseña estará encriptada.
- Que el usuario pueda verificar si está registrado.
- Tener acceso al timeline mediante un botón

DEFINICIÓN DE TERMINADO

- Conectar con Firebase
- Función de autentificación de información de la información ingresada
- Crear una SPA para el Acceso
- Diseño sea similar al prototipo
- Code Review
- Debe ser SPA
- Prueba de usabilidad

### Historia de Usuario 3: CREAR TIMELINE

Yo como usuario quisiera entrar al muro para ver las publicaciones más recientes.

CRITERIOS DE ACEPTACIÓN

- El usuario ya registrado, podrá acceder al muro
- Que el usuario pueda visualizar una caja de texto para escribir publicación (mínimo 1 carácter máximo 300 caracteres)
- Visualizar un botón que te redirija a la sección de adopciones
- Visualizar un botón que te redirija a la sección de parejas
- Visualizar un botón que te redirija a la sección de memes
- Visualizar un botón que te redirija a la sección de adiestramiento
- Poder visualizar el feed de publicaciones
- Poder visualizar un footer que contenga la navegación a home, crear comentario, guardar y perfil

DEFINICIÓN DE TERMINADO

- Debe ser SPA
- Diseño similar al prototipo
- Code review
- Prueba de usabilidad
- Que los botones te redirijan a una página vacía
- Que sea responsive
- Test unitarios

### Historia de Usuario 4: CREAR POSTS

Yo como usuario quiero poder crear tu post para publicarlo

CRITERIOS DE ACEPTACIÓN

- Crear un apartado para poder escribir el post
- Poder visualizar el nombre de usuario que crea el post
- El usuario visualizará un botón para poder adjuntar fotografías
- Visualizar un botón para publicar

DEFINICIÓN DE TERMINADO

- Conectar con firestore
- función de crear post
- El botón ejecute la función de publicar post
- Debe ser SPA
- Revisión de código
- Ser responsive
- Test unitarios
- Diseño sea similar al prototipo
- Prueba de usabilidad

### Historia de Usuario 5: POSTS PUBLICADOS EN TIMELINE

Yo como usuario quiero poder ver todos los post publicados.

CRITERIOS DE ACEPTACIÓN

- Crear un apartado para poder visualizar el post
- Poder visualizar el nombre de usuario que creo el post
- El usuario visualizará fotografías
- Visualizar un botón para editar el post
- Poder tener un apartado para dar like
- Poder tener un apartado para contar los likes
- Poder tener un apartado para eliminar el post

DEFINICIÓN DE TERMINADO

- Conectar con firestore
- Función de visualizar post fetch firebase
- Debe ser spa
- Revisión de código
- Ser responsive
- Test unitarios
- Diseño sea similar al prototipo
- Prueba de usabilidad

### Historia de Usuario 6: BORRAR POST

Yo como usuario quiero poder eliminar los post que he publicado.
CRITERIOS DE ACEPTACIÓN

- Crear un apartado para poder visualizar el post
- Visualizar un botón para borrar el post
- Quiero poder confirmar el post a eliminar

DEFINICIÓN DE TERMINADO

- Conectar con firestore
- Función de eliminar post fetch firebase
- Debe ser spa
- Revisión de código
- Ser responsive
- Test unitarios
- Diseño sea similar al prototipo
- Prueba de usabilidad

### Historia de Usuario 7: EDITAR POST

Yo como usuario quiero poder editar los post que he publicado.
CRITERIOS DE ACEPTACIÓN

- Crear un apartado para poder visualizar el post
- Visualizar un botón para editar el post
- Quiero poder ver mi post anterior para saber que voy a editar
- Visualizar un botón para guardar los cambios

DEFINICIÓN DE TERMINADO

- Conectar con firestore
- Función de editar post fetch firebase
- Debe ser spa
- Revisión de código
- Ser responsive
- Test unitarios
- Diseño sea similar al prototipo
- Prueba de usabilidad

### Historia de Usuario 8: LIKES

Yo como usuario quiero poder likear los post que veo.
CRITERIOS DE ACEPTACIÓN

- Crear un apartado para poder likear los post
- Visualizar el conteo de likes en los post
- Visualizar un botón para dar like a el post
- Solo admitir un like por usuario

DEFINICIÓN DE TERMINADO

- Conectar con firestore
- Función contar likes en post fetch firebase
- Debe ser spa
- Revisión de código
- Ser responsive
- Test unitarios
- Diseño sea similar al prototipo
- Prueba de usabilidad

### Historia de Usuario 9: Crear perfil usuario

Yo como usuario quiero poder crear un perfil de usuario para poder ingresar mis datos.

CRITERIOS DE ACEPTACIÓN

- Que el usuario pueda agregar una imagen de perfil
- El usuario podrá ingresar su nombre
- Que el usuario pueda ingresar su ciudad
- Que el usuario pueda elegir su genero
- Que el usuario pueda pasar a la sección de crear el perfil de su mascota mediante un botón

DEFINICIÓN DE TERMINADO

- Conectar con Firebase
- Caja de texto para poder ingresar nombre del usuario
- Opción múltiple para guardar datos de ciudad
- Opción múltiple para guardar datos de genero
- Función de guardado de información
- Diseño sea similar al prototipo
- Test unitarios
- Revisión de código
- Prueba de usabilidad
- Debe ser SPA

<br></br>

---

## 4. Investigación UX

- ¿Quiénes son los usuarios de este producto?

Los usuarios de esta herramienta son principalmente jóvenes – adultos que aman a sus mascotas o tienen interés de dar en adopción a mascotas de manera responsable aparte de tener el gusto por compartir anécdotas, recuerdos o el día a día de sus mascotas para formar una comunidad.

- ¿Cómo soluciona los problemas de los usuarios este producto?

Actualmente nos enfrentamos a un gran problema de superpoblación de cachorros en la calle o dueños que tienen cachorros con cachorros que no son capaces de mantener, a su vez, cada vez son más las personas que se dan a la tarea de encontrar un hogar para estos maravillosos cachorros, ya sea para darlos en adopción o para adoptar un nuevo miembro en la familia, Solovino soluciona el problema de contacto entre estas dos personas, ya que a través de esta app se evalúa que tan apto es un usuario para adoptar.

Asimismo, cada vez son más los usuarios que crean redes sociales para sus mascotas ya sea para crear lazos de amistad con otros amantes de las mascotas o simplemente para mostrar el día a día de sus mascotas y esta es la red social perfecta porque está enfocada a los perros y cachorros.

<br></br>

---

## 5. Prototipos + Feedback de iteración

- Resumen del feedback

Se realizaron diferentes pruebas de usabilidad a través de la plataforma de maze para poder corroborar que la aplicación estaba siendo intuitiva y amigable con los usuarios. Se observaron puntos de mejora en la adaptabilidad al usuario con cada una de ellas.

<br></br>

![Shows VIiews](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20Solovino/prototipes/prototipo%20baja.jpg)

<p align="center"> Fig 1. Prototipo baja fidelidad </p>

![Shows VIiews](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20Solovino/prototipes/prototipo%20alta.jpg)

<p align="center"> Fig 1. Prototipo alta fidelidad </p>

---

## 6. Creadoras

| Desarrolladoras | Contacto |
| ------------------- | ------------------- |
| Atenas Villalba| [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atenas-villalba-764bb8235/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtenasVillalba) |
| Anna Lizarraga | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anna-lizarraga/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnnaLizarraga) |

***

<br></br>

# <h1 align="center">Social Network Solovino. 🐾</h1>

![Shows Mockups](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20CV/Projects/RedSocial.jpg)

<!-- <div align="center"></div> -->

<p align="center">Project Deploy:</p>
<p align="center">In process...</p>

---

## Index

- [1. Summary of the project](#1.-Summary-of-the-project)
- [2. Technical project skills](#2.-Project-Tech-Skills)
- [3. Planning](#3.-Planning)
- [4. UX Research](#4.-UX-Research)
- [5. Sketches + Prototypes + Feedback](#5-Sketching-+-Prototyping-+-Iteration-Feedback)

<br></br>

---


## 1. Summary of the project

- DESCRIPTION

Social networks are connecting the whole world, that is why the implementation of a Social Network was carried out, which is called: "Solovino".

It was designed to promote the responsible adoption of puppies as well as to share their experiences with their doggy companions.

- TECHNICAL SUMMARY

Its implementation is a SPA (single-page application) optimized for cell phones. It allows any user to create an access account through email and password or log in through Google, Facebook and Twitter. This is how the user will have access to the timeline where he/she can create posts and will be able to see posts from other users and interact with them through a like button. Only the user who creates the post will be able to edit and delete it.

<br></br>

---

## 2. Project Tech Skills

### HTML 5

- Semantics

### CSS 3

- CSS Selectors
- Box Model
- Flexbox
- Grid Layout

### Web APIs

- Using DOM selectors
- DOM Event Handling
- Dynamic DOM Manipulation
- Routing

### JavaScript ES6 Vanilla

- Primitive data
- Strings
- Variables
- Functions
- Conditionals
- Loops/cycles
- Arrays
- Objects
- Callbacks
- Promises
- Unit tests
- Asynchronous tests
- Use of mocks and spy
- ECMAScript modules.
- Use of linter (ESLINT)

### Firebase

- Firebase Auth
- Firestore

### Git- Github version control

- Git: Version control with git (init, clone, add, commit, status, push, pull, remote)
- Git: Integration of changes between branches (branch, checkout, fetch, merge, reset, rebase, tag)
- GitHub: Deployment with Netlify.

### User-centricity

- Designing a product or service with the user at the center.

### Product-design

- Create high-fidelity prototypes that include interactions.
- Follow basic visual design principles

### Research

- Plan and execute usability testing of prototypes at different levels of fidelity (Maze)

<br></br>

---

## 3. Planning

This project was done with agile SCRUM methodologies in 5 sprints of 1 week in which user stories were worked.

You can see the planning [here](https://trello.com/b/k289jcSl/social-network)

<br></br>

- HISTORIAS DE USUARIO

### User Story 1: ACCESSING THE APP WITH PROVIDERS

As a user, I want to be able to access my account through Gmail or Facebook to make access easier and more practical.

ACCEPTANCE REQUIREMENTS:

- That the user can visualize the icons for access.
- The user will be able to choose any of the two options to access.
- That the user visualizes and accepts the terms and conditions.
- The user can register and save his/her account.
- Have access to the create profile page or enter the timeline via a button.

FINISHED DEFINITION

- Connect to Firebase
- Save information function
- Be able to accept terms and conditions as a requirement
- Button redirects you to create user profile section
- Design similar to the prototype
- Be responsive
- Unit tests
- Code Review
- Must be SPA
- Usability test

### User Story 2: LOG IN WITH REGISTERED ACCOUNT

I as a user want to be able to enter my email address and password to log in to the app.

ACCEPTANCE REQUIREMENTS:

- The user can visualize the fields for access.
- The user will be able to enter a password to access.
- The password will be encrypted.
- The user must be able to verify if he/she is registered.
- Access to the timeline through a button

FINISHED DEFINITION

- Connect to Firebase
- Information authentication function of the entered information
- Create a SPA for Access
- Design to be similar to prototype
- Code Review
- Must be SPA
- Usability test

### User Story 3: CREATE TIMELINE

I as a user would like to enter the wall to see the most recent posts.

ACCEPTANCE REQUIREMENTS:

- The already registered user will be able to access the wall
- The user can display a text box to write a post (minimum 1 character, maximum 300 characters).
- Display a button that redirects to the adoption section.
- Display a button that redirects you to the couples section.
- Display a button that redirects you to the memes section
- Display a button that redirects you to the training section
- To be able to display the publications feed
- Display a footer containing the navigation to home, create comment, save and profile

FINISHED DEFINITION

- Must be SPA
- Design similar to the prototype
- Code review
- Usability test
- Buttons redirect to an empty page
- It must be responsive
- Unit tests

### User Story 4: CREATE POSTS

I as a user want to be able to create your post for publication.

ACCEPTANCE REQUIREMENTS:

- Create a section to be able to write the post
- To be able to see the name of the user who creates the post
- The user will see a button to be able to attach photos
- Display a button to publish

FINISHED DEFINITION

- Connect to firestore
- Create post function
- The button executes the publish post function
- Must be SPA
- Code review
- Be responsive
- Unit tests

### User Story 5: VIEW ALL POSTS IN TIMELINE

I as a user want to be able to see all the posts published.

ACCEPTANCE REQUIREMENTS:

- Create a section to be able to view the post
- To be able to see the name of the user who created the post.
- The user will see pictures
- Display a button to edit the post
- To be able to have a section to give likes
- To be able to have a section to count likes
- To be able to have a section to delete the post

FINISHED DEFINITION

- Connect with firestore
- Function to display post fetch firebase
- Must be spa
- Code review
- Must be responsive
- Unit tests
- Design is similar to prototype
- Usability test

### User Story 6: DELETE POST

I as a user want to be able to delete the posts I have published.

ACCEPTANCE REQUIREMENTS:

- Create a section to display the post
- Display a button to delete the post
- I want to be able to confirm the post to be deleted

FINISHED DEFINITION

- Connect to firestore
- Delete post fetch firebase function
- Must be spa
- Code review
- Be responsive
- Unit tests
- Design is similar to prototype
- Usability test

### User Story 7: EDITING POSTS

I as a user want to be able to edit the posts I have published.

ACCEPTANCE REQUIREMENTS:

- Create a section to display the post
- Display a button to edit the post
- I want to be able to see my previous post so I know what I am going to edit.
- Display a button to save changes

FINISHED DEFINITION

- Connect to firestore
- Edit post fetch firebase function
- Must be spa
- Code review
- Must be responsive
- Unit tests
- Design is similar to prototype
- Usability test

### User Story 8: LIKES

I as a user want to be able to like the posts I see.

ACCEPTANCE REQUIREMENTS:

- Create a section to be able to like the posts
- Display the count of likes on the posts
- Display a button to give like to the post
- Only allow one like per user

FINISHED DEFINITION

- Connect with firestore
- Function to count likes on post fetch firebase
- Must be spa
- Code review
- Be responsive
- Unit tests
- Design is similar to prototype
- Usability test

### User Story 9: CREATE USER PROFILE

I as a user would like to create a user profile in order to enter my data.

ACCEPTANCE REQUIREMENTS:

- The user can add a profile picture
- The user can enter his/her name
- The user can enter his city
- The user can choose his gender
- The user can go to the section to create a pet profile using a button.
- Add an element

FINISHED DEFINITION

- Must be SPA
- Connect to Firebase
- Text box to be able to enter user name
- Multiple choice to save city data
- Multiple choice to save gender data
- Save information function
- Design similar to prototype
- Unit tests
- Code review
- Usability test

<br></br>

---

## 4. UX Research

- Who are the users of this product?

The users of this tool are mainly young people - adults who love their pets or are interested in adopting pets in a responsible way, besides having the pleasure of sharing anecdotes, memories or the day to day life of their pets to form a community.

- How does this product solve user's problems?

Currently we face a big problem of overpopulation of puppies on the street or owners who have puppies with puppies that are not able to maintain, in turn, more and more people are given the task of finding a home for these wonderful puppies, either to give up for adoption or to adopt a new member in the family, Solovino solves the problem of contact between these two people, as through this app is the evaluation of how suitable a user is to adopt.

Likewise, there are more and more users who create social networks for their pets either to create bonds of friendship with other pet lovers or simply to show the day to day life of their pets and this is the perfect social network because it is focused on dogs and puppies.

<br></br>

---

## 5. Sketching + Prototyping + Iteration Feedback

- Summary of feedback

Different usability tests were performed through the maze platform in order to corroborate that the application was being intuitive and user friendly. Points of improvement in user adaptability were observed with each one of them.

<br></br>

![Shows VIiews](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20Solovino/prototipes/prototype%20low.jpg)

<p align="center"> Fig 1. Low fidelity prototype </p>

![Shows VIiews](https://raw.githubusercontent.com/AnnaLizarraga/Assets/main/Assets%20Solovino/prototipes/prototype%20high.jpg)

<p align="center"> Fig 1. High fidelity prototype </p>

<br></br>


## 6. Creators

| Developers | Contact |
| ------------------- | ------------------- |
| Atenas Villalba| [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atenas-villalba-764bb8235/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtenasVillalba) |
| Anna Lizarraga | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anna-lizarraga/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnnaLizarraga) |
