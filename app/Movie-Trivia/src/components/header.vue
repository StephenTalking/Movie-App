<template>
  <header>
    <h2>CAJ2 Movie-App</h2>
  </header>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>
<style scoped>

* {
    background-color: grey;
    font-family: 'Raleway', sans-serif;
    text-align: center;
   }

header {
padding: 15px;
}

h2 {
font-size: 50px;
}

.colContainer{
display: flex;
flex-flow: row;
align-items: center;
justify-content: space-around;
padding: 20px;
}

.col {
border: 1px black solid;
}

div {
border: 1px black dotted;
}

.div1 {
padding: 10px;
margin: 10px;
height: 100px;
width: 300px;
}

.div2 {
padding: 10px;
margin: 10px;
height: 600px;
width: 300px;
}

.navbar {
display: flex;
justify-content: space-around;
}

.aboutContainer {
display: flex;
flex-flow: row;
justify-content: space-around;
}

.staffInfo {
display: flex;
flex-flow: column;
align-items: center;
padding: 20px;
}

.staffTag {
padding: 10px;
font-family: 'Fjalla One', sans-serif;
}

.subtitle {
font-style: italic;
}

.infoContainer {
display: flex;
flex-flow: column;
}

ol {
list-style-type: none;
}

li {
padding: 20px;
}

.footerBox {
float: right;
padding: 20px;
}

i {
padding: 4px;
margin: 0px 5px;
}

i:hover {
color: yellow;
}

.fa {
font-size: 40px;
}

.staffInfo img {
    width: 200px;
}

.gameScreenshot {
    display: flex;
    justify-content: space-around;
    margin: 40px;
}


.brochureTxt {
    display: flex;
    justify-content: center;
    padding: 80px;
    margin: 40px;
}

.statsTxt {
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
}
</style>
