<template>
<div >
     <div id="appointment">
          <div class="container1">
              <div class="suggest">
               
                <span>Do not wait and make an appointment today!</span>
              </div>
              
                  <button class="btnabout">About our clinic</button>
             
              
           </div>
        </div>

      <footer >
          <div class="container">
            
                <h6>© 2020 DentialClinic</h6>

           </div>

       </footer>
       
</div>
</template>

<script>
export default {

}
</script>

<style>


#appointment{
   
    background-color: #2baaec;
    display: flex;
    border-width: 0 0 0.3px 0;
   
  
   
}

#appointment .container1{
    
  
    margin-left: 1rem;
    margin-top: 2rem;
    width:100%;
    padding-bottom: 30px;
    
   

}
.suggest{
    margin-bottom: 0;
}

.suggest span{
  
    color: #FFFFFF;
    font-family: Roboto Slab;
    float: left;
    margin-left: 0;
    padding-left: 0;
  
}

.btnabout{
    background-color: #FFFFFF;
  border: none;
  color: #2baaec;
  padding: 10px 70px;
  border-radius: 8px;
  text-align: center;
  text-decoration: none;
  
  font-size: 18px;
  margin-right: 25px;
font-weight: bold;

   float: right;

}

footer{
    background-color: #2BAAEC;
    display: flex;
    
  
    border-top: solid rgba(255,255,255,0.16);;
}

footer h6{
    color: #FFFFFF;
    text-align: center;
    font-family: Roboto, sans-serif;
    font-weight: normal;
    font-size: 16px;
    margin: 20px;
}
</style>