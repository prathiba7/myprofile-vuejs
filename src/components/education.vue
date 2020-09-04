<template>
    <div class="a">
        <span class="b">EDUCATION QUALIFICATION</span>
        <table class="table">
            <thead>
                <tr>
                    <th>Course</th>
                    <th>School/College</th>

                    <th>Year OF Passing</th>
                    <th>Percentage</th>

                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>BACHELOR OF ENGINEERING</td>
                    <td>NSS COLLEGE OF ENGINEERING</td>
                    <td>2022</td>
                    <td>cgpa-9.3</td>
                </tr>
              
                 <tr>
                    <td>HIGHER SECONDORY</td>
                    <td>GHSS NEMMARA</td>
                    <td>2018</td>
                    <td>98%</td>
                </tr>
                 <tr>
                    <td>SSLC</td>
                    <td>GGVHSS NEMMARA</td>
                    <td>2016</td>
                    <td>100%</td>
                </tr>
                    
            </tbody>
        </table>
    </div>
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
.table{
    border-collapse: collapse;
    margin:25px;
    font-size:0.7cm;
    min-width:400px;
    
}
.table thead tr{
    background-color: rgb(0, 128, 115);
    color:white;
    text-align:left;
    
}

.table td{
    padding:12px 15px;
    font-size:0.5cm;
    font-family:Roboto;
}
.table th{
    font-size:0.7cm;
    font-family:Roboto;

}
.table tbody tr{
    border-bottom: 1px solid black;
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