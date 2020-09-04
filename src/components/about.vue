<template>
    <div class="a"><span class="b">ABOUT ME</span>
    <p size="0.3cm">
        I am taking computer science and engineering graduation from Nss college of engineering,Palakkad.
        Flair to learn new Things.passionate about front end development.Basic knowledge of the creation of graphic design software and programming languages relevant to the web. </p></div>
</template>
<script>
export default {
  name: 'about',
  props: {
    msg: String
  }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
.h1
{
    text-align:left;

}
.p{
    font-size:0.3cm;
}
.b
{
  height:20px;
  width:500px;
  border-top:2px solid black;
  border-bottom:2px solid black;
  color:rgb(0, 128, 115);
  font-size:.8cm;
  border-radius:3px solid black;
  font-weight: bold;
  font-family:Roboto;
}

</style>