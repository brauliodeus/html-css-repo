Comidas Típicas Chilenas
Descripción general
Página web estática que presenta una selección de comidas típicas de la gastronomía chilena. Muestra tres platos representativos: Completos, Pastel de choclo y Pantrucas, cada uno acompañado de una imagen ilustrativa.
La estructura de la página incluye:

Un encabezado con título y barra de navegación con enlaces a secciones internas.
Un artículo principal compuesto por bloques <aside>, uno por cada plato, separados visualmente con líneas horizontales (<hr>).


Gestión de imágenes mediante CSS
Cada imagen del sitio tiene asignada una clase CSS individual (.img, .img2, .img3) que permite controlar su tamaño de forma independiente:
css.img {
    height: 250px;
    width: 410px;
}

.img2 {
    height: 200px;
    width: 400px;
}

.img3 {
    height: 230px;
    width: 430px;
}
Puntos importantes a considerar:

Los valores de height y width siempre deben incluir unidad (por ejemplo px). Sin unidad, el navegador ignora la propiedad y la imagen mantiene su tamaño original.
Cada clase permite ajustar el tamaño de cada imagen de forma independiente sin afectar a las demás.
Las imágenes se encuentran en la carpeta assets/img/ y se referencian desde el HTML con rutas relativas.
