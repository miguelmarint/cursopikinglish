<template>
  <div id="app">
    <div class="row" id="curso">
      <div class="col-sm-12">
        <curso1Leccion1 />
        <curso1Leccion2 />
        <curso1Leccion3 />
        <curso1Leccion4 />        
        <curso1Leccion5 />
      </div>
    </div>
  </div>
</template>

<script>
import curso1Leccion1 from "./components/curso1Leccion1.vue";
import curso1Leccion2 from "./components/curso1Leccion2.vue";
import curso1Leccion3 from "./components/curso1Leccion3.vue";
import curso1Leccion4 from "./components/curso1Leccion4.vue";
import curso1Leccion5 from "./components/curso1Leccion5.vue";

export default {
  name: "App",
  components: {
    curso1Leccion1,
    curso1Leccion2,
    curso1Leccion3,
    curso1Leccion4,
    curso1Leccion5,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#curso {
  padding-left: 1em;
}
.row {
  width: 100%;
  margin: 0;
}
#textPractice {
  text-align: left;
  margin-bottom: 1em;
  font-size: 1.5em;
}
/deep/.labelPregunta {
  font-weight: bold;
}

/deep/ #tabla {
  padding-right: 0px;
  padding-left: 0px;
}
/deep/ .row {
  width: 100%;
  margin: 0;
  margin-bottom: 1em;
  padding: 0;
}

/deep/ #EnglishInput,
#SpanishInput {
  width: 100%;
}

/deep/ .Blue {
  background-color: cornflowerblue;
}
/deep/ .Red {
  background-color: crimson;
}
/deep/ .Yelow {
  background-color: yellow;
}
/deep/ .Green {
  background-color: chartreuse;
}

/deep/ .noHead {
  border-width: 0;
  font-size: 0;
}

/deep/.colorLetraRojo {
  color: red;
  margin-left: 8px;
  margin-right: 8px;
}

#cuadroTexto {
  margin-bottom: 1em;
}

img {
  width: 100%;
}

/deep/ #textRequired {
  width: 200px;
}

/deep/ #inputText {
  margin: 0;
  display: inline-flex;
}

#titulo {
  color: red;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 1.5em;
}

#subTitulo {
  padding: 0;
  margin-right: auto;
  color: darkcyan;
  margin-top: 1.5em;
  text-align: left;
}
.textList {
  font-size: 1.5em;
}

#numeroMagico {
  background-color: salmon;
  margin-right: auto;
  margin-left: auto;
  padding-top: 0.5em;
  padding-bottom: 0.5em;
  border-style: solid;
  border-radius: 1em;
  border-color: black;
  font-size: 2em;
  color: black;
  font-family: "PT Sans";
  font-weight: bold;
  margin-bottom: auto;
}

#text,
#inputText {
  text-align: left;
}

#textoCompromiso {
  text-align: left;
  margin-bottom: 1em;
  font-size: 1.5em;
}
#i {
  padding-right: 0;
  text-align: end;
}
</style>
