<template>
  <div class="main">
   <div class="topnav">
      <ul>
        <li><a href="#home">Koduleht</a></li>
        <li><a href="#news">Kuulutused</a></li>
        <li><a href="#contact">Oksjonid</a></li>
        <li style="float:right"><a href="#about">Login</a></li>
      </ul>
      <div class="margin">
        <div class="border">
          <div class="padding">
            <div class="content">
                 <div class="row">
                  <div class="column">
                    <div class="card">BMW M5</div>
                  </div>
                  <div class="column">
                    <div class="card">530i</div>
                  </div>
                  <div class="column">
                    <div class="card">Lexus is450</div>
                  </div>

                  <div class="row">
                  <div class="column">
                    <div class="card">BMW M5</div>
                  </div>
                  <div class="column">
                    <div class="card">530i</div>
                  </div>
                  <div class="column">
                    <div class="card">Lexus is450</div>
                  </div>

                  <div class="row">
                  <div class="column">
                    <div class="card">BMW M5</div>
                  </div>
                  <div class="column">
                    <div class="card">530i</div>
                  </div>
                  <div class="column">
                    <div class="card">Lexus is450</div>
                  </div>

                  
            </div>
          </div>
        </div>
      </div>
    </div> 
  </div>
  </div>
   </div>
  </div>
</template>

<script>

</script>

<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgb(51, 51, 51);
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: rgb(39, 136, 0);
}

* {
  box-sizing: border-box;
}

.main {
  Text-align: center;
}
      
.margin {
  border: 10px solid #009900;
  text-align: center;
  padding: 50px;
  
}
      
.padding {
  color: #009900;
  background-color: #c5c5db;
}
   
.column {
  float: left;
  width: 33.33%;
  padding: 0 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
}

</style>
