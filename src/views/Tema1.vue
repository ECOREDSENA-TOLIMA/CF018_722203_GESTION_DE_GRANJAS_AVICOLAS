<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Estadística

    p.mb-4(data-aos="flip-down") La recolección de información y su posterior análisis, es una práctica necesaria en la toma de decisiones. La estadística es la ciencia encargada de abordar la gestión de datos a través de metodologías y sistemas, ya sea para ordenarlos, clasificarlos y obtener conclusiones, o para proyectar eventos futuros en base a su interpretación.   

    p.mb-2(data-aos="flip-down") Su aplicación es transversal a una inmensa variedad de disciplinas, ciencias o ámbitos. Esto se debe a que su razón de ser se enfoca a la gestión de datos, y prácticamente todas las áreas sociales y económicas hacen uso de la información para la producción de nuevo contenido.

    Separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Objetivos

    p.mb-5(data-aos="flip-down") El propósito de la estadística es, en principio, comprender los hechos a través de los datos recolectados de estos, sin embargo, se puede mencionar otra serie de objetivos derivados del anterior:

    SlyderF.mb-5(columnas="col-lg-6 col-xl-4 d-flex align-items-stretch" data-aos="flip-down")
      .row.justify-content-center.mb-3
        .col-12
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/tema1-1.svg' alt='')
            .tarjeta.color-primario.p-4
              p.text-center Conocer las características de una población objetivo y alcanzar conclusiones o elaborar proyecciones a partir de la información disponible. Tal es el caso de los estudios de mercado en los que se identifican aspectos demográficos para predecir la aceptación que tendrá un producto, previo lanzamiento al mercado.

      .row.justify-content-center.mb-3
        .col-12
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/tema1-2.svg' alt='')
            .tarjeta.color-acento-contenido.p-4
              p.text-center.texto-negro Estudiar un fenómeno a través de la identificación de las relaciones entre dos o más variables. Por ejemplo, asociar la caída en ventas de un producto, con la publicación en medios de una noticia que no recomienda consumirlo.

      .row.justify-content-center.mb-3
        .col-12
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/tema1-3.svg' alt='')
            .tarjeta.color-acento-botones.p-4
              p.text-center Tomar decisiones en cualquier campo, a partir de los datos recolectados. El sector público suele aplicar estudios estadísticos que repercuten en el presupuesto público, por ejemplo, a través de un censo poblacional, identificar el número de personas en cierto rango de edad, y a partir de esto, designar un número de subsidios.

      .row.justify-content-center.mb-3
        .col-12
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/tema1-4.svg' alt='')
            .tarjeta.color-primario.p-4
              p.text-center Hacer interpretaciones a partir de la recolección de datos de una muestra, para hacerlas extensivas a un grupo de población mayor. Tal es el caso de las encuestas previas a las elecciones presidenciales, donde con unos cuantos miles de personas, se proyecta el comportamiento de millones de votos.

      .row.justify-content-center.mb-3
        .col-12
          .tarjeta-avatar
            img(src='@/assets/curso/temas/tema1/tema1-5.svg' alt='')
            .tarjeta.color-acento-contenido.p-4
              p.text-center.texto-negro Apoyar a otras disciplinas a través de las técnicas de recolección de datos, análisis y proyecciones para anticipar comportamientos futuros. Por ejemplo, para estimar la extinción de una especie en riesgo, a partir de una comparativa entre sus niveles de natalidad y mortalidad.

    Separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Tipos

    p.mb-5(data-aos="fade-down") La estadística puede dividirse en dos grandes ramas, según el enfoque y los objetivos que se esperen alcanzar a través de ella:

    .bloque-texto-g.bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-6.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 #[b Estadística descriptiva]
          br
          br
          | Es la rama de la estadística que busca describir los fenómenos objeto de estudio. Para ello, aborda las metodologías de recolección, medición y análisis de los datos. Esta rama se apoya en el uso de tablas y gráficos para extraer las características fundamentales de un conjunto de datos.
        
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-7.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 #[b Estadística inferencial]
          br
          br
          | Se encarga de analizar la información y los parámetros dados por un conjunto de datos y a partir de ellos deducir comportamientos. Es decir, busca modelar patrones a partir de un conjunto de datos tomados de una muestra que serán extrapolados a la población; esto no solo implica definir patrones de comportamiento vigentes, sino hacer predicciones apoyadas en la evidencia.
      
    Separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Codificación de la información

    p.mb-4(data-aos="fade-down") Una vez se ha recolectado la información es necesario someterla a criterios de sistematización para facilitar su recuento e interpretación. La codificación consiste en la edición de los datos para prepararlos para su análisis, usualmente a través de la asignación de números a las variables cualitativas registradas, así como a aquellos datos faltantes como preguntas sin responder.

    p.mb-4(data-aos="fade-down") Cuando la recolección de información se efectúa a través de preguntas cerradas, la codificación suele presentarse directamente en el formulario y, por ende, previa a la recolección de datos, por ejemplo, con las opciones de verdadero (v) o falso (f), o con los literales o numerales que preceden cada opción de respuesta (a, b, c… o 1, 2, 3…).

    p.mb-4(data-aos="fade-down") En el caso de las preguntas abiertas, es necesario recolectar los datos para luego asignarles un código a los tipos de respuesta dadas por cada persona consultada. Debido a la posible pluralidad de respuestas, es recomendable diseñar categorías y asignarles códigos a estas para lograr compactarlas.

    p.mb-4(data-aos="fade-down") El objetivo de la codificación es facilitar la comprensión y análisis de los datos, es por ello que no se recomienda codificar la información con más de 10 códigos por cada variable, también es posible desestimar aquellas respuestas que tengan muy baja participación (menos del 5%) y que, por lo tanto, no influyen de forma significativa en el análisis.

    Separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Tabulación de datos

    p.mb-4(data-aos="fade-down") Una vez han sido recolectados los datos por cualquiera de las metodologías contempladas en la estadística (observación, encuestas, entrevistas, entre otros), es recomendable que se organicen y representen de una forma consolidada para facilitar el análisis. La tabulación consiste en el uso de tablas para disponer de la información de forma más ágil y amigable al usuario, permitiendo la visualización de las características más relevantes identificadas en el estudio. 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h4 Tabulación de carácter cualitativo

    p.mb-4(data-aos="fade-down") Consiste en la consolidación de información no cuantificable, debido a su carácter descriptivo, la tabulación suele limitarse al conteo de respuestas coincidentes y a su participación en relación con la totalidad de respuestas brindadas. Su estructura suele contar con las variables, su frecuencia absoluta y su frecuencia relativa. 

    p.mb-4(data-aos="fade-down") La frecuencia absoluta es el número de veces que se recolecta un dato, es decir, la cantidad de veces que se obtiene una misma respuesta, y la relativa la porción que representa sobre el total de datos recolectados. Se presenta el siguiente ejemplo para ilustrar con el formato sugerido para este tipo de información:

    p.mb-4(data-aos="fade-down") Preguntaron a 10 personas cual fue su materia favorita durante su paso por la secundaria, las respuestas recolectadas se presentan a continuación, ver tabla 1:

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-11.col-lg-9(data-aos="fade-right")
        .titulo-sexto.color-primario.mb-1
          p.titulo.pb-0.mb-0 #[b Tabla 1.] #[i Tabulación de datos cualitativos] 
      .col-12.col-md-11.col-lg-9(data-aos="fade-right")
        .tabla-b.color-acento-contenido
          table(style="min-width:auto")
            thead
              tr.cabecera-a.text-center
                th Variable 
                th Frecuencia absoluta
                th Frecuencia relativa
            tbody
              tr.text-center
                th Matemáticas
                td 2
                td 20 %
              tr.text-center
                th Inglés
                td 3
                td 30 %
              tr.text-center
                th Educación Física
                td 5
                td 50 %
              tr.text-center
                th Total encuestados
                td 10
                td 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h4 Tabulación de variables cuantitativas 
    
    p.mb-4(data-aos="fade-down") En este caso, la información es cuantificable y por lo tanto medible, usualmente se subclasifican según el número de variables que puedan presentarse. Cuando son pocas (menos de 30 según la mayoría de los autores) se listan de manera similar a la tabulación cualitativa, ubicando las frecuencias absolutas y relativas.

    p.mb-4(data-aos="fade-down") Cuando el número de variables puede ascender a cifras poco prácticas para analizar de forma individualizada, se pueden agrupar en intervalos para reducir el número de registros a presentar en la tabulación. La definición de los intervalos dependerá del investigador, pero deberá cumplir con dos condiciones esenciales: que los intervalos sean excluyentes entre sí, es decir, que una misma variable no pueda pertenecer a 2 intervalos a la vez, y que todos los datos encajan, de tal forma que no queden datos sin pertenecer a ninguno.

    p.mb-4(data-aos="fade-down") Si bien la definición de los intervalos es arbitraria, por norma general se recomienda que tengan la misma amplitud (cantidad de datos que contienen). Sin embargo, hay situaciones en las que puede ser más conveniente clasificar en función de otro parámetro, por ejemplo, los rangos de edades, para identificar los menores y los integrantes de la tercera edad.  A continuación, se presenta un formato de tabulación aplicable a un grupo de 100 personas a las que se les consultó por este dato, ver tabla 2:

    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-md-11.col-lg-9(data-aos="fade-right")
        .titulo-sexto.color-primario.mb-1
          p.titulo.pb-0.mb-0 #[b Tabla 2.] #[i Tabulación de datos cuantitativos] 
      .col-12.col-md-11.col-lg-9(data-aos="fade-right")
        .tabla-b.color-acento-contenido
          table(style="min-width:auto")
            thead
              tr.cabecera-a.text-center
                th Variable 
                th Frecuencia absoluta
                th Frecuencia relativa
            tbody
              tr.text-center
                th Menores de 18 años
                td 27
                td 27 %
              tr.text-center
                th Mayores de 18 y menores de 60 años
                td 53
                td 53 %
              tr.text-center
                th Mayores de 60 años
                td 20
                td 20 %
              tr.text-center
                th Total encuestados
                td 100
                td 

    p.mb-4(data-aos="fade-down") Como sistema de comprobación, la totalidad de encuestados o datos recolectados debe ser equivalente a la sumatoria de las frecuencias absolutas, de la misma forma que la sumatoria de las frecuencias relativas debe ser del 100 %.

    Separador
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Planificación estadística

    p.mb-4(data-aos="fade-down") La planificación estadística está comprendida dentro de los apartados principales de la planificación estratégica, puesto que se hace necesario comprender las necesidades de información de la empresa en función de los objetivos generales y específicos que la empresa se haya propuesto. Su implementación aporta gran valor, debido a que el uso de la estadística es transversal a todas las áreas organizacionales, ya sea generando información para una debida planeación, o para la evaluación posterior.

    p.mb-4(data-aos="fade-down") Llevar a cabo la planificación estadística puede traer consigo varios beneficios, entre los cuales destacan los siguientes:
   
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Beneficio uno")
        .col-md-3.col-lg-2.col-10.mb-4.mb-md-0
          img(src='@/assets/curso/temas/tema1/tema1-8.svg', alt='')
        .col-md-9.col-lg-10.col-12
          p Permite identificar la información que se espera recolectar, lo que minimiza costos, enfocando su destinación únicamente a los medios necesarios para conseguir dichos datos.
      .row(titulo="Beneficio dos")
        .col-md-3.col-lg-2.col-10.mb-4.mb-md-0
          img(src='@/assets/curso/temas/tema1/tema1-9.svg', alt='')
        .col-md-9.col-lg-10.col-12
          p Facilita la integración entre las diversas áreas de la empresa, puesto que fortalece su comunicación y coordinación en lo que respecta al manejo de la información estadística.
      .row(titulo="Beneficio tres")
        .col-md-3.col-lg-2.col-10.mb-4.mb-md-0
          img(src='@/assets/curso/temas/tema1/tema1-10.svg', alt='')
        .col-md-9.col-lg-10.col-12
          p Existen requerimientos de información comunes a varias áreas organizaciones, la correcta planificación estadística identifica estos elementos para que su recolección se haga una sola vez y les sea útil a todas ellas. 
      .row(titulo="Beneficio cuatro")
        .col-md-3.col-lg-2.col-10.mb-4.mb-md-0
          img(src='@/assets/curso/temas/tema1/tema1-11.svg', alt='')
        .col-md-9.col-lg-10.col-12
          p Facilita la toma de decisiones y su evaluación o monitoreo posterior, puesto que la definición de parámetros dirigirá el trabajo a unos requerimientos específicos. 
      .row(titulo="Beneficio cinco")
        .col-md-3.col-lg-2.col-10.mb-4.mb-md-0
          img(src='@/assets/curso/temas/tema1/tema1-12.svg', alt='')
        .col-md-9.col-lg-10.col-12
          p Depura el proceso estadístico en la empresa, puesto que una correcta planeación permitirá su evaluación a través de criterios definidos, de la misma forma que trazará una hoja de ruta para la ejecución de planes de mejora. 
      
    .bloque-texto-g.bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-13.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 #[b Importante]
          br
          br
          | El plan estadístico se convierte en la herramienta a través de la cual se consignan los objetivos, acciones y estrategias planteadas durante la planificación. Su formulación requiere de la integración de todas las áreas involucradas en la recolección e interpretación de la información, para que las estrategias definidas converjan en la consecución de objetivos individuales y comunes.

    p.mb-4(data-aos="fade-down") Las siguientes son las fases por las que debe ejecutarse una debida planificación estadística:

    .tarjeta.color-primario.p-4.mb-5(data-aos="fade-down")
      SlyderA(tipo="b")
        .row
          .col-md-5.mb-4.mb-md-0
            h4.texto-negro Formulación
            p Se determina el alcance de la planificación, así como los participantes a los cuales se les asignarán las tareas. Se identifican los requerimientos de información globales y específicos, así como las fuentes de información disponibles.
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-14.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            h4.texto-negro Implementación
            p Se socializa el diseño del plan estadístico, de tal forma que todas las áreas se hagan partícipes del proceso; posteriormente se ejecutan las tareas planteadas en su formulación y se hacen las entregas según un cronograma. Finalmente se consolidan los resultados obtenidos.
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-15.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            h4.texto-negro Seguimiento
            p Corresponde al monitoreo continuo y permanente a la ejecución de las tareas asignadas durante la formulación. Esta labor se lleva a cabo de manera paralela a la implementación, de tal forma que las problemáticas se puedan identificar a tiempo para ser corregidas. A partir de esto, se calculan los indicadores de gestión y se clasifican las áreas según el nivel de cumplimiento en relación con las proyecciones iniciales.
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-16.png', alt='')
        .row
          .col-md-5.mb-4.mb-md-0
            h4.texto-negro Evaluación
            p Como última fase, se contrastan los objetivos planteados con su nivel de cumplimiento, para establecer el grado de efectividad de las estrategias propuestas. Es recomendable que la evaluación de esta métrica no solo se lleve a cabo al final de la ejecución, sino también a mitad del proceso, para implementar estrategias de mejora de forma inmediata. 
          .col-md-7
            figure
              img(src='@/assets/curso/temas/tema1/tema1-17.png', alt='')



    .bloque-texto-g.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/tema1-13.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 #[b Importante]
          br
          br
          | Como resultado de las fases anteriores, deben obtenerse un informe de ejecución y uno de evaluación, el primero consolidando e interpretando los datos recolectados, y el segundo midiendo la efectividad del proceso con respecto a las estimaciones iniciales.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
