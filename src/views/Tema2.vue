<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Bioseguridad y manejo de los animales destinados para la reproducción natural

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La bioseguridad es un componente importante en las producciones pecuarias, porque engloba diferentes componentes, tanto estructurales y físicos de las producciones, como componentes sistémicos de los animales, abarcando desde la distancia entre explotaciones, barreras sanitarias, cercos perimetrales, entre otros; hasta lo más propio de la producción, como la eliminación y prevención de enfermedades, pero siempre teniendo como objetivo principal proteger la salud de los animales en la explotación. La bioseguridad va encaminada a evitar la entrada y/o salida de agentes patógenos, por ende, la importancia de su realización y ejecución en los entes productivos pecuarios.
  
    .tarjeta.color-secundario.p-3.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-auto
          ul.lista-ul
            li
              i.fas.fa-check
              | Identificación de entrada de vectores a la producción, ya sea porque está en contacto con otras granjas, plantas de sacrificio, manipuladores de animales.
            li 
              i.fas.fa-check
              | Identificación de zonas limpias, zonas sucias, restricción de personal en ciertas zonas, restricción de flujo de personal.
            li 
              i.fas.fa-check
              | Controlar el ingreso y la salida del personal.
            li 
              i.fas.fa-check
              | Delimitación con cercos perimetrales para evitar la entrada de personas o animales, tanto domésticos como silvestres.
            li 
              i.fas.fa-check
              | Al introducir material genético o animales, aislar animales nuevos; comprar animales en sitios reconocidos; asegurarse de que el animal se encuentra bajo condiciones óptimas de vacunación, desparasitación; no introducir animales enfermos a la explotación.
            li 
              i.fas.fa-check
              | Desinfección de vehículos con arco de desinfección, bomba de aspersión.
            li 
              i.fas.fa-check
              | Protocolos de limpieza y desinfección de cada área.
            li 
              i.fas.fa-check
              | Control de plagas y roedores.
            li 
              i.fas.fa-check
              | Manejo de mortalidad, desechos y residuos.
    
    .row.justify-content-center.mb-5(data-aos="fade-down")
     .col-12
      p(data-aos="fade-down") Ahora, el uso de reproductores representa un mayor reto hablando bajo condiciones de bioseguridad, debido a que se debe tener un cuidado especial, tanto del macho como de la hembra, con respecto a la limpieza y desinfección de las diferentes áreas destinadas para la reproducción y/o monta.
      p(data-aos="fade-down") Para disminuir y controlar el riesgo de enfermedades, es importante seguir las siguientes recomendaciones:

    .row.justify-content-center.mb-5(data-aos="fade-down")
     .col-12
      ol.lista-ol--cuadro.lista-ol--cuadro--separador
        i.fas.fa-atom.p-1(style="color:#3B5620")
          span 
        | Al momento de comprar animales reproductores, es importante solicitar la historia clínica del animal, registros de vacunación, registros de montas, realizar un análisis físico y sanguíneo para descartar cualquier tipo de enfermedad que pueda ser perjudicial para la producción.
      ol.lista-ol--cuadro.lista-ol--cuadro--separador
        i.fas.fa-atom.p-1(style="color:#3B5620")
          span 
        | Realizar una limpieza del órgano reproductor, tanto de la hembra como del macho; importante hacerlo tanto antes como después de la monta.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-9
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta-verde").mb-5(style="background-color=#DBF9BD")
          .row(titulo="Alojamiento del semental")
            .col-12
              ul.lista-ul
                li
                  i.fas.fa-atom.p-1(style="color:#304C8E")
                  |	Asegurarse de que el área de descanso de los sementales esté limpia.
                li
                  i.fas.fa-atom.p-1(style="color:#304C8E")
                  |	Realizar frecuentes cambios de cama.
                li
                  i.fas.fa-atom.p-1(style="color:#304C8E")
                  | Realizar limpieza y desinfección de acuerdo con criterio técnico, teniendo en cuenta los diferentes materiales de la cama, el piso y las paredes.
          .row(titulo="Semental")
            .col-12
              ul.lista-ul
                li
                  i.fas.fa-atom.p-1(style="color:#304C8E")
                  |	Los cuidados de aseo son importantes para el manejo de reproductores, ello incluye la limpieza del abdomen, el corte de los pelos del prepucio y, en algunas especies, la limpieza del esmegma.
                li
                  i.fas.fa-atom.p-1(style="color:#304C8E")
                  |	Se recomienda realizar la limpieza de manera delicada.
          .row(titulo="Área de monta / toril - brete o apretadero")
            .col-12
              p Es importante que la hembra sea trasladada al área de monta.
              p Limpie y desinfecte antes y después de cada monta (usando agua a presión y objetos que ayuden a la remoción física de partículas, detergente, desinfectante y secado si se puede realizar).
              p El piso debe ser ranurado, no debe ser liso para evitar deslizamientos de los animales.
          .row(titulo="Utensilios")
            .col-12
              p Almacenamiento de sogas, cabezales, narigueras, bozales, trancas y demás herramientas usadas para esta práctica, procurar que no salgan a áreas diferentes para evitar contaminación.
      .col-3
        figure
          img(src='@/assets/curso/temas/tema2/img2.png', alt='Imagen Alojamiento del semental')    

    Separador
    .row
      .col-xl-12       
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 2.1	 Elementos de conducción, sujeción e inmovilización para los animales en reproducción

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-12
        p.mb-0 Estos elementos son los encargados de realizar el traslado, la sujeción e inmovilización, y cumplen un papel importante en el manejo animal, facilitando así el trabajo, y lo más importante, sin lastimar al animal.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-10
        .cajon.color-primario.p-4.mb-4(style="background-color:#E9ECE6")
          p Los animales reproductores deben tener un proceso de amansamiento y acostumbramiento a estos utensilios para el mejoramiento de su docilidad, es de consideración resaltar que para una mejor conducción de los animales, los corrales, jaulas, y pesebreras deben crear entre ellas una especie de camino o pasillo, el cual funciona como embudo y guía, evitando que el animal vaya muy suelto, ayudando al manejo y conducción.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-3
        figure
          img(src='@/assets/curso/temas/tema2/img3.svg', alt='Dentro de la sujeción, existen técnicas de sujeción manual y con ayuda de herramientas.')
      .col-7
        p Dentro de la sujeción, existen técnicas de sujeción manual y con ayuda de herramientas. Dentro de las manuales, una muy utilizada en ganadería es el uso de sujeción por la cola, muy común en ganadería bovina, en la cual se toma la cola del bovino, ya sea estando en botalón o apretadero, y se ejerce fuerza contraria hacia la parte de la cabeza del animal, con precaución de no ocasionar fractura de la cola. En algunos casos, cuando los animales son dóciles, simplemente, con la ayuda de los corrales o estructuras aledañas en forma de pasillo, se puede realizar la conducción con un simple arreo.

    .row.justify-content-center.mb-5
      .col-12
        p Algunas herramientas usadas para la conducción, sujeción e inmovilización son:
    
  
    .tarjeta.tarjeta--amarilla.p-4(style="background-color:#FFFAD0")
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Narigueras
            p Aros utilizados para el manejo de animales, los cuales se ubican en las fosas nasales ejerciendo presión y dando así un manejo del animal. Existen narigueras móviles y fijas, ambas cumplen la función de sujeción, conducción e inmovilización, muy común en el manejo de bovinos.
            .row.mb-5
              .col-sm.mb-5.mb-sm-0
                ul
                  li 
                    i.fas.fa-atom.p-1(style="color:#3B5620")
                    | Nariguera fija.
                  li 
                    i.fas.fa-atom.p-1(style="color:#3B5620")
                    | Nariguera manual.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img4.png', alt='Narigueras Aros utilizados para el manejo de animales los cuales se ubican en las fosas nasales ejerciendo presión y dando así un manejo del animal. Existen narigueras móviles y fijas ambas cumplen la función de sujeción, conducción e inmovilización, muy común en el manejo de bovinos.')
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Sogas - lazos
            p Las sogas son esenciales para el manejo de los animales, ya que son versátiles y por medio de ellas se pueden realizar tanto técnicas de sujeción, como herramientas, puesto que por medio de nudos se pueden hacer bózales, cabezales, amarres, y son esenciales para hacer una conducción, sujeción e inmovilización segura tanto para el operario como para el animal.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img5.png', alt='Las sogas son esenciales para el manejo de los animales ya que son versátiles y por medio de ellas se pueden realizar tanto técnicas de sujeción, como herramientas, ya que por medio de nudos se pueden hacer bósales, cabezales, amarres, y son esenciales para hacer una conducción, sujeción e inmovilización segura tanto para el operario como para el animal.')
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Cabezales
            p Los cabezales son las herramientas de conducción animal más comunes en las diferentes producciones tanto en campo como en exposición, ya que son herramientas verdaderamente útiles, sencillas y que al animal no le genera ningún tipo de estrés ni dolor. Requieren de un proceso de amansamiento. Vienen de distintos materiales como sogas, cuero, nailon, y cadenilla.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img6.png', alt='Los cabezales son las herramientas de conducción animal más comunes en las diferentes producciones tanto en campo como en exposición ya que son herramientas verdaderamente útiles sencillas y que al animal no le genera ningún tipo de estrés ni dolor. Requieren de un proceso de amansamiento. Vienen de distintos materiales como sogas, cuero, nailon, y cadenilla.')
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Cepos para monta / apretaderos Toriles de monta
            p Los cepos para monta, apretaderos son herramientas especiales para ayudar a la inmovilización de la hembra y una fácil monta del macho, asegurando así una monta adecuada y sin riesgo de caídas lesiones, movimientos bruscos.
            p Se recomienda dejar que el macho tome su tiempo, reconozca la hembra y realice el ritual de apareamiento.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img7.png', alt='Los cepos para monta, apretaderos son herramientas especiales para la ayudar a la inmovilización de la hembra y una fácil monta del macho, asegurando así una monta adecuada y sin riesgo de caídas lesiones, movimientos bruscos.')
        .row
          .col-md-6.mb-4.mb-md-0
            h3 Botalón bramadero
            p El botalón o bramadero es una herramienta que se utiliza principalmente para la sujeción de animales, útil en diferentes procedimientos donde se requiera una sujeción rápida y trabajo corto.
            p Consta de un madero fuertemente fijado al suelo, que puede ser del corte de un árbol con un enraizamiento fuerte o bien el realizado por el hombre, debe estar lo suficientemente clavado al piso para aguantar la fuerza de los animales con los cuales se va a trabajar.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema2/img8.png', alt='El botalón o bramadero es una herramienta que se utiliza principalmente para la sujeción de animales, útil en diferentes procedimientos donde se requiera una sujeción rápida y trabajo corto.')

    Separador
    .row
      .col-xl-12       
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 2.2	 Principales enfermedades reproductivas por especie animal

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-12
        p Los animales, siendo seres vivos biológicamente activos, están bajo constante riesgo de ser asaltados por diferentes microorganismos que pueden ser causantes de enfermedades, en ocasiones, fatales para el animal.
        p Los causantes de las enfermedades infecciosas pueden ser de tipo bacteriano, virales, parasitarias y hongos, en dichas enfermedades, es de vital importancia identificar, controlar, supervisar, prever y, en caso dado, curar, siempre teniendo como fundamento la bioseguridad y el concepto de que es mejor “prevenir que curar”.
        p Dentro de las diferentes especies pecuarias, se encuentra gran variedad de enfermedades, causando aumento en los costos productivos y grandes pérdidas económicas para la producción pecuaria.
        p Analice algunas de estas enfermedades.

    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Bacterianas
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-12
        h3 Brucelosis (zoonótica)
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-12
        p La brucelosis es una enfermedad que a nivel mundial produce severas pérdidas económicas en las explotaciones pecuarias (Diaz, 2013), presenta una transmisión horizontal y vertical entre los animales, es una de las principales causantes de aborto e infertilidad en las especies, siendo sus principales hospederos naturales:

    .row.justify-content-center.mb-5
      .col-lg-9
        ImagenInfograficaB.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema2/img9.svg', alt='Principales enfermedades reproductivas por especie animal')              

          div(x="19%" y="89%" tooltip="Ver mas..." numero="")
            h5 Bovinos
            p La brucelosis bovina se produce fundamentalmente por la presencia de la bacteria #[i Brucella abortus] (Díaz, 2013) esta enfermedad ingresa al organismo por medio de la vía oral, ya sea por la ingesta de alimentos, agua contaminada o consumo directo de restos de placentas, restos fetales, secreciones vaginales, y en ocasiones el contacto directo de becerros enfermos, el semen puede ser vía de transmisión de la enfermedad.
            p La enfermedad es asintomática en vacas no gestantes, lo cual al momento se convierten en vectores pasivos de la enfermedad, ya que también deber ser objeto de supervisión y acción. Las hembras afectadas generalmente desarrollan una inflamación placentaria, generando abortos entre el quinto y noveno mes de gestación, se presentan signos como la eliminación de mucus vaginal, exudado vaginal con tonalidad y aspecto purulento por la carga de microorganismo bacterianos.         
          div(x="58%" y="89%" tooltip="Ver mas..." numero="")
            h5 Cerdos
            p El ganado porcino doméstico está infectado principalmente por #[i Brucella suis], aunque con menor frecuencia puede resultar infectado por B. abortus y por B. melitensis en regiones en las que la brucelosis es endémica en el ganado bovino o en los pequeños rumiantes (Díaz, 2013). El modo de ingreso es generalmente el mismo enunciado en B abortus, mediante las mucosas: orales, nasales, vaginales y conjuntivales. Los signos clínicos son imperceptibles en animales jóvenes. Se puede presentar en ambos sexos, siendo el macho portador asintomático. En las producciones generalmente causan afecciones importantes, ya que afecta contundentemente la fertilidad, provocando un alto porcentaje de abortos, aumento en la muerte de recién nacidos, ocasionando infertilidad en hembras y así afectando considerablemente la producción.
          div(x="96%" y="89%" tooltip="Ver mas..." numero="")
            h5 Ovejas
            p En el ganado ovino la infección de la #[em brucella militensis] los signos son muy parecidos casi iguales a la #[i brucella abortus] afectando los factores de fertilidad, aumentando el número de abortos y número de mortinatos, la vía de exposición es la misma por medio de líquidos fetales, contacto con abortos, placentas contaminadas con dicha bacteria, el contacto con hembras o machos portadores de la enfermedad. En las producciones ganaderas ovinas es común compartir pasturas entre rebaños diferentes y posteriormente retornar al corral, siendo este un medio de contaminación de rebaños libres de enfermedad. Para el control de la enfermedad es importante seguir las condiciones sanitarias y de bioseguridad estipuladas por el ente regulador y los predios pecuarios, ya que este es un trabajo mancomunado entre el ganadero o productor y el cuidado de animales en condiciones adecuadas para la producción y lograr una rentabilidad y el ente regulador vigilando y supervisando que se realicen bien las actividades.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-12
        p Su peligrosidad radica en que el humano puede llegar a ser un hospedero accidental, generando una problemática zoonótica.
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .cajon.color-secundario.p-4.mb-4
          p Es importante la vacunación oportuna de las hembras para evitar un posterior contagio y seguir los lineamientos de bioseguridad de cada producción.
    
    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Leptospirosis (zoonóticas)
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-3
        figure
          img(src="@/assets/curso/temas/tema2/img12.png", alt="Leptospirosis (zoonóticas)")
      .col-lg-9
        p La leptospirosis es una zoonosis bacteriana de importancia económica en la industria pecuaria, debido a que provoca abortos, mortinatos, infertilidad y disminución en la producción lechera, lo cual genera pérdidas económicas significativas a los productores. (Hernández y Gómez, 2011).
        p La leptospira es una bacteria con características muy complicadas de identificación, ya que posee más de 7 variantes infecciosas, las cuales tienen un hospedador de mantenimiento, que serían los roedores, y unos hospederos accidentales, predominando la variante hardjo, las diferentes especies pecuarias y los humanos (zoonosis); teniendo en cuenta las consideraciones anteriores, es importante su control y vigilancia. La leptospirosis es una enfermedad cuyas manifestaciones clínicas, muy variadas, van desde cuadros subclínicos, abortos, momificaciones y mortalidad al nacimiento, que afecta los ciclos de producción y productividad, hasta provocar complicaciones multiorgánicas que pueden conducir a la muerte. (Hernández y Gómez, 2011).
        p En las especies pecuarias, la principal forma de ingreso del agente al organismo son las mucosas orales nasales y conjuntivales, así como heridas abiertas y/o no sanadas por completo. Con un periodo de incubación de 3 a 12 días, los signos iniciales de la enfermedad son los característicos de una infección bacteriana común, como fiebre, pérdida de apetito, dificultad respiratoria, pérdida de energía, dolor articular, entre otros. Posteriormente, la bacteria viaja a órganos diana u objetivos, donde verdaderamente provoca un daño mucho más severo, como son los órganos reproductores, pulmones, hígado, riñones, siendo este último órgano importante también para la diseminación de la enfermedad, ya que la leptospira tiene una gran capacidad de supervivencia en la orina y así puede contaminar de manera permanente el medio. De allí la importancia de los roedores en su ciclo de propagación, porque estos se encuentran en los diferentes hemisferios terrestres.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .cajon.color-primario.p-4.mb-4(style="background-color:#E9ECE6")
          p La implementación de normas y protocolos de bioseguridad juegan un papel importante en el control de la enfermedad, especialmente los programas para el control de plagas y protocolos de limpieza y desinfección.

    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Campylobacter genital (vibriosis)
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-12
        p Esta enfermedad afecta principalmente al ganado bovino, pero también se puede presentar en pequeños rumiantes. Se caracteriza por la presencia de signos como la infertilidad, repetición de celos y, en ocasiones, abortos; el agente causal generalmente se encuentra en el prepucio de los sementales, trasmitiendo de forma venérea por medio de la monta, o puede ingresar al sistema por medio de ingesta de materiales contaminados con dicha bacteria. En las hembras, se presenta una infección uterina, la cual provoca una inflamación severa, con secreciones de moco y pus. Para su control, es importante el uso de semen certificado y, en caso de manejar reproductores para monta natural, es de valiosa importancia el realizar un cultivo por medio de lavado prepucial antes de incorporar el semental a la producción y manejar exámenes de rutina para evitar complicaciones.
    
    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Protozoos (parásitos) 
    
    .tarjeta.color-secundario.p-3.mb-5(data-aos="fade-down")(style="background-color:#F0FDE3")
      .row.justify-content-around.align-items-center
        .col-5
          figure
            img(src="@/assets/curso/temas/tema2/img13.png", alt="Leptospirosis (zoonóticas)")
        .col-7
          p Es una enfermedad producida por un protozoo llamado trichomonas foetus, el cual produce una afección sexual, siendo una enfermedad transmitida por el coito, en la cual los machos son los principales hospederos. Este protozoo tiende a localizarse en las cavidades sin producir ningún signo de enfermedad o lesión, de esta manera, se convierte en un portador asintomático de la enfermedad. Pueden ser afectados tanto el ganado bovino como ocasionalmente los equinos, cerdos y roedores.
          p En su ciclo de crecimiento y supervivencia, el parásito puede vivir en las secreciones genitales de la hembra de 90 a 190 días, generando una inflamación en la inserción placentaria y provocando abortos y demás problemas reproductivos.
          p Las hembras parasitadas pueden ser identificadas por la presencia de signos como repetición de celos, disminución en tasa de preñez y abortos.
    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .cajon.color-secundario.p-4.mb-4
          p Como método de diagnóstico, es posible usar los cultivos protozoarios y microscopía. Teniendo en cuenta el comportamiento de dicha patología, es indispensable el control sanitario de los reproductores, sea por inseminación artificial o por monta natural, es primordial el examen genital.

    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Virales
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
        h3 Rinotraqueitis infecciosa bovina IBR
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
       p Se caracteriza esencialmente por la aparición de una rinotraqueitis exudativa, que puede afectar los bronquios mayores de los animales infectados. Aunque el aborto es más que una secuela del problema respiratorio, hay reportes de cepas con cierto potencial abortigénico que pueden producir brotes de abortos (Duque et al., 2014). La rinotraqueitis infecciosa posee 2 subtipos, los cuales afectan el organismo de manera diferente, siendo el subtipo 1 el causal de problemas respiratorios y el subtipo 2 el causal de problemas netamente reproductivos.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-lg-10
        .cajon.color-primario.p-4.mb-4(style="background-color:#E9ECE6")
          p La contaminación o entrada del virus es principalmente por mecanismos aerógenos, lo que quiere decir que es por ingreso nasal, generando complicaciones respiratorias en primer momento; en algunas ocasiones, se presenta fiebre, pérdida del apetito, que, a la evolución de la enfermedad, presenta un edema vulvar generalizado con presencia de pústulas, úlceras, y secreciones  mucopurulentas. Es común los abortos, repeticiones de celos, baja tasa de preñez, entre otros problemas reproductivos. En los machos, se presenta un agrandamiento del pene bajo factores inflamatorios con formación pustular.

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12
       p Es importante en la producción contar con un sistema de bioseguridad apto para evitar la llegada de la enfermedad. Frente a los animales afectados, se debe hacer un manejo de signos secundarios, porque los procesos víricos dependen de la respuesta inmune del animal.

    .text-decor.text-white.text-center(data-aos="flip-up").mb-5
      p.mt-3.p-2 Síndrome reproductivo y respiratorio porcino (PRRS)
    
    .tarjeta.color-secundario.p-3.mb-5(data-aos="fade-down")(style="background-color:#F0FDE3")
      .row.justify-content-around.align-items-center
        .col-5
          figure
            img(src="@/assets/curso/temas/tema2/img14.png", alt="Leptospirosis (zoonóticas)")
        .col-7
          p El PRRS se considera una enfermedad endémica, siendo una enfermedad que afecta cerdos en todas sus etapas de crecimiento y desarrollo, con una presentación clínica de dos maneras, la primera es una forma que afecta principalmente los caracteres reproductivos de las cerdas, mostrando partos prematuros, abortos, nacimientos muertos, momias, lechones débiles que posteriormente, en el predestete, son muy propensos a la muerte. Y la segunda siendo una afección principalmente respiratoria, con una sintomatología de inapetencia, una respiración abdominal acelerada, donde uno de los principales signos es la ausencia de tos; se presenta acumulación de líquidos en párpados, conjuntivitis, pero su principal problema es la inmunosupresión, que desencadena la llegada de bacterias secundarias oportunistas, las cuales complican el cuadro de la enfermedad.
    
</template>

<script>
export default {
  name: 'Tema2',
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
