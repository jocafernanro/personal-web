<template>
  <section class="main-home">
    <h1 class="main-home__title">Jose C. Fernández</h1>
    <p class="main-home__subtitle">Desarrollador multidisciplinar y creativo, persona multipotencia, emprendedor, con un gran
      interés en el desarrollo personal y humano, liderazgo, ética y arte.</p>
    <p class="main-home__text">
      Tengo 7 años de experiencia dentro del desarrollo full-stack (he variado desde el backend hasta el frontend).
      Me ha tocado desempeñar roles de análisis, arquitectura y liderzago dentro de los equipos en los que he trabajado.
    </p>
    <p class="main-home__text">
      Éste último año desempeño el rol de Tech Lead Engineer en un proyecto ágil de desarrollo de videojuegos de casino
      usando tecnologías frontend de vanguardia: ES6, reactividad, mobx, webpack, babel, i18next, etc.
    </p>
    <p class="main-home__text">
      Mis proyectos favoritos son aquellos donde tengo la posibilidad de combinar varias de mis habilidades y
      concimientos donde poder construir y gestionar soluciones inteligentes para problemas complejos.
    </p>
    <p class="main-home__text">
      Mi principal habilidad no es el conocimiento de ninguna tecnología, lenguaje o herramienta concreta. Mi principal
      habilidad es la de aprender. Y es este hambre de conocimiento el que me hace querer aprender cada nueva
      tecnología, herramienta o proceso que aparece y puede aportar algo a mi capacidad de crecer y mi equipo de trabajo.
    </p>
    <p class="main-home__text">
      Es por eso que en estos dos últimos años he podido trabajar en proyectos de desarrollo de RPAs, construido
      una Blockchain desde 0 para una empresa líder del sector aeronáutico, proyectos de análsis y arquitectura,
      una plataforma de aprendizaje de matemáticas y, actualmente, aprendiendo a liderar un equipo a nivel de ingeniería,
      en el mundo del videojuego y el negocio de los juegos de casino.
    </p>
    <p class="main-home__text">
      Actualmente no busco trabajo profesional, pero siempre estoy abierto a propuestas interesantes. Estoy disponible
      para charlar, debatir, aprender o apuntarme a proyectos freelances a través de mi email <u>jocafernanro@gmail.com</u>
    </p>
    <p class="main-home__text">
      Tecnologías clave para desempeñar estos papeles: Python, Django, Django Rest Framework, Falcon, gRPC, Javascript, Vue, Angular, UiPath, MySql, PostgreSQL, MongoDB y muchas por ahí perdidas :P
    </p>
    <p class="main-home__text">
      Tecnologías con las que estoy empezando o me muero por aprender: Unity, rust, machine learning y react.
    </p>
    <p class="main-home__location"><i class="fas fa-map-marker"></i> Establecido en Sevilla, España</p>
  </section>
</template>

<script>
export default {
  name: 'home-main'
}
</script>

<style lang="scss" scoped>
  .main-home {
    width: 80vw;
    max-width: 40em;
    margin: 50px auto 150px auto;

    &__title {
      margin: 0;
      padding: 0.3em 0;
      max-width: var(--text-title-max-width);
      color: var(--grey-light);
      font-size: var(--text-title-size);
      font-weight: var(--weight-bolder);
      line-height: 1em;
    }

    &__subtitle {
      font-size: var(--text-subtitle-size);
      font-weight: var(--weight-bolder);
      padding: 0 0 0.5em 0;
      line-height: var(--text-subtitle-line-height);
    }

    &__text {
      font-size: var(--text-text-size);
      line-height: 1.3em;
      padding: 0 0 1em 0;
    }

    &__location {
      font-size: var(--text-location-size);
      .fas{
        margin: 0 1em 0 0;
      }
    }
  }
</style>
