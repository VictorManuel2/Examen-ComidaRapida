<template>
  <Header
    nombreNegocio="La Cocina el Rinconcito"
    nombreAlumno="Víctor Manuel Ortiz Álvarez"
    grupo="10A"
  />
  <div class="container">
    <card
      url="https://www.unileverfoodsolutions.com.mx/tendencias/de-mexico-para-el-mundo/platillos-mexicanos/top10-platillos/jcr:content/parsys/content-aside-footer/columncontrol_copy/columnctrl_parsys_1/textimage_copy/image.transform/jpeg-optimized/image.1592429867593.jpg"
      nombre="Pozole"
      descripcion="El pozole es una sopa tradicional mexicana hecha a base de granos de maíz nixtamalizados, comúnmente de la variedad cacahuazintle, al que se agregan carnes, verduras y especias muy variadas según la región." 
    />
    <card
      url="https://www.cocinacaserayfacil.net/wp-content/uploads/2020/03/Platos-de-comida-que-pides-a-domicilio-y-puedes-hacer-en-casa_2.jpg"
      nombre="Hamburguesas"
      descripcion="Hecho a base de carne molida o de origen vegetal, ​ aglutinada en forma de filete cocinado a la parrilla o a la plancha, aunque también puede freírse u hornearse."
    />
    <card
      url="https://www.gastrolabweb.com/u/fotografias/m/2021/6/17/f850x638-14957_92446_5358.jpg"
      nombre="Mole"
      descripcion="Se refiere a varios tipos de salsas mexicanas muy condimentadas hechas principalmente a base de chiles y especias, y que son espesadas con masa de maíz, tortilla o pan; también se refiere a los mismos guisos a base de carne o vegetal que se suelen preparar con estas salsas espesas.​"
    />
    <card
      url="https://www.recreoviral.com/wp-content/uploads/2015/05/20-comidas-para-preparar-aunque-estes-en-quiebra-6.jpg"
      nombre="Sincronizadas"
      descripcion="La sincronizada es un sándwich con una tortilla.​ Frecuentemente se confunde con las quesadillas mexicanas. Se denominan así por «sincronizarse» las dos tortillas cubriendo el contenido de jamón y queso."
    />
    <card
      url="https://assets.unileversolutions.com/recipes-v2/206095.png"
      nombre="Chilaquiles rojos"
      descripcion="Los chilaquiles están hechos de tortilla frita bañada en una salsa que en su mayoría es roja o verde y van acompañados de crema, queso y cebolla. Pueden o no acompañarse de distintas proteínas como huevo, pollo o bistec."
    />
    <card
      url="https://bpprivilegeclub.com/blog/wp-content/uploads/2020/08/Mexican-Dishes-Featured-1.jpg"
      nombre="Tacos"
      descripcion="El taco es una preparación culinaria muy popular de México que consiste en una tortilla, generalmente de maíz, que se dobla o se enrolla para contener dentro diversos ingredientes y algún tipo de salsa."
    />
  </div>

  <Footer fecha="UTTehucán | Desarrollo Móvil Integral | Clase 22-09-2022" />
</template>

<script>
import Header from "./components/Header.vue";
import Card from "./components/Card.vue";
import Footer from "./components/Footer.vue";
export default {
  components: { Card, Header, Footer },
};
</script>
