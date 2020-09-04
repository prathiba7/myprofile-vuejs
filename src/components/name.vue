<template>
    <div class="a">
         <span class="q">My Portfolio</span>
         <div class="c">.</div>
         <div class="d">
             
              <span class="z">
            PRATHIBA M
            </span>
            <span class="y">
            Address:Prathiba house,kanimangalam,nemmara</span>
            


            <div class="b"></div>
                        <span class="x">email:mprathiba4@gmail.com</span>

        
                      
            
        
       
        
            
        
      
    </div>
    <div class="wrapper">
      <div class="e"></div>
      <div class="f"></div>
      <div class="g"></div>

    </div>
      
    </div>

</template>
<script>
export default {
  name: 'name',
  props: {
    msg: String
  }
}
</script>
<style scoped>
.q
{
  color:rgb(0, 128, 115);
  margin-left:550px;
  font-family:Roboto;
  font-weight:bold;
  font-size:0.9cm;

}
.h1
{
  color:rgb(0, 128, 115)

}
.z
{
  color: rgb(0, 128, 115);
  font-family:Roboto;
  font-size:0.9cm;
  font-weight:bold;
  text-align:right;
  
  margin-top:10px;
}
.y{
  margin-left:600px;
  font-family:Roboto;
  text-align:right;
}
.x{
  margin-left:550px;
  font-family:Roboto;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
span.c
{
    text-align: center;
    font-size: 30px;
    margin-left: 560px;
    
}
span.d
{
    
    font-size: 20px;
    text-align:left;
    margin-left:500px;
    
}
span.e
{
    font-family:Arial, sans-serif;
    font-weight: 30px;
    margin-left: 500px;
}

span.a
{
    font-family:Arial, sans-serif;
    font-weight: 100px;
}
div.b
{
    height:200px;
    width:200px;
    background-image: url("./prathu.jpg");
    margin-left: 550px;
    border-radius: 200px;

}
div.c
{
    background-color: rgb(0, 128, 115);
}
div.d
{
    height:300px;
    width:100%;

}
.wrapper{
    
    display: flex;
    
    flex-wrap: wrap;
    height: 10vh;
    background-color:white;
    margin-left:0px;

}
div.e{
    padding: 30px;
    background-image:url(./github.png);
    margin-left:550px;

    border-radius: 15px;
    cursor: pointer;
}
div.e:hover{
    padding: 30px;
    background-image:url(./github.png);
    margin-left:550px;
  border: 5px rgb(255, 196, 0) solid;
    border-radius: 15px;
    cursor: pointer;
}

div.f{
    padding: 30px;
    background-image:url(./facebook.png);
    margin-left:4px;
    
    border-radius: 15px;
    cursor: pointer;
}
div.f:hover{
    padding: 30px;
    background-image:url(./facebook.png);
    margin-left:4px;
      border: 5px rgb(255, 196, 0) solid;
    border-radius: 15px;
    cursor: pointer;
}
div.g{
    padding: 30px;
    background-image:url(./linkedin.png);
    margin-left:4px;
    
    border-radius: 15px;
    cursor: pointer;
}
div.g:hover{
    padding: 30px;
    background-image:url(./linkedin.png);
    margin-left:4px;
    border: 5px rgb(255, 196, 0) solid;
    border-radius: 15px;
    cursor: pointer;
}
</style>
