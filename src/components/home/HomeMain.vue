<template>
  <section class="main-home">
    <h1 class="main-home__title">Jose C. Fernández</h1>
    <p class="main-home__subtitle">Desarrollador multidisciplinar y creativo, persona multipotencial, emprendedor, con un gran
      interés en el desarrollo personal y humano, así como en el liderazgo, la ética y el arte.</p>
    <p class="main-home__text">
      Tengo 9 años de experiencia dentro del desarrollo full-stack.
      Me ha tocado desempeñar roles de análisis, arquitectura y liderazgo dentro de los equipos en los que he trabajado.
    </p>
    <p class="main-home__text">
      Éste último año vengo ejerciendo el rol de Tech Lead Engineer en un proyecto ágil de desarrollo de videojuegos de casino
      usando tecnologías frontend de vanguardia: ES6, reactividad, mobx, webpack, babel, i18next, etc.
    </p>
    <p class="main-home__text">
      Mis proyectos favoritos son aquellos donde tengo la posibilidad de combinar varias de mis habilidades y
      conocimientos con el fin de poder construir y gestionar soluciones inteligentes para problemas complejos.
    </p>
    <p class="main-home__text">
      Mi principal habilidad no es el conocimiento de ninguna tecnología, lenguaje o herramienta particular. Mi principal
      habilidad y lo que más me motiva es aprender. Es esto lo que me hace crecer y evolucionar
      constantemente ya no solo en el mundo del desarrollo, sino en otro tipo de competencias como lo son el diseño
      gráfico, el marketing, el desarrollo personal, las finanzas. la fotografía, la música y una serie de habilidades complementarias que
      me permiten tener un mejor contexto a la hora de abordar diferentes problemas.
    </p>
    <p class="main-home__text">
      A esto se le llama multipotencialidad y tiene dos claras ventajas: Aprendizaje acelerado y síntesis de ideas.
      Esas cualidades me permiten conectar diferentes disciplinas conocidas para suplementar el periodo de aprendizaje
      y acelerar el proceso debido al uso de otra característica, los conocimientos transversales o transferibles.
      Es por eso que se dice que los multipotenciales no comienzan a aprender desde 0, sino que nos centramos en los
      huecos libres que dejan las otras habilidades ya conocidas.
    </p>
    <p class="main-home__text">
      Es por eso que en estos dos últimos años he podido trabajar en proyectos muy diferentes entre sí, como proyectos
      de desarrollo de RPAs, construir una Blockchain desde 0 para una empresa líder del sector aeroespacial,
      proyectos de análisis y arquitectura y creado una plataforma de aprendizaje de matemáticas a nivel de negocio y
      desarrollo. Actualmente lidero  un equipo a nivel de ingeniería en el mundo del videojuego y el negocio de los
      juegos de casino.
    </p>
    <p class="main-home__text">
      Aunque en estos momentos no me encuentro en una búsqueda activa de trabajo, siempre estoy abierto a propuestas interesantes. Estoy disponible
      para charlar, debatir, aprender o colaborar en proyectos freelance a través de mi email <u>jocafernanro@gmail.com</u>
    </p>
    <p class="main-home__text">
      Tecnologías clave para desempeñar estos papeles: Python, Django, Django Rest Framework, Falcon, gRPC, Javascript,
      Vue, Angular, UiPath, MySql, PostgreSQL, MongoDB y muchas más por ahí perdidas.
    </p>
    <p class="main-home__text">
      Tecnologías con las que estoy empezando o me muero por aprender: Unity, rust, machine learning y react.
    </p>
    <p class="main-home__location"><i class="fas fa-map-marker"></i> Establecido en Sevilla, España</p>
    <p class="main-home__location">Última actualización: 29 Abril 2022</p>
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
