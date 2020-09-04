<template>
    <div clas="a"><span class="b">TECHNICAL SKILLS</span>
    <ul>
        <li class="z">JAVA</li>
        <li class="z">C</li>
        <li class="z">PYTHON</li>
        <li class="z">HTML</li>

        <li class="z">CSS</li>
        <li class="z">JAVASCRIPT</li>
        <li class="z">SQL</li>
        </ul></div>
        
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
.z
{
  background-color: rgb(0, 128, 115);
  color:white;
  font-family:Roboto;
  width:100px;
  
  border:1px solid black;
  border-radius:8px;
  margin-top:5px;
  padding:8px 12px;
}
</style>