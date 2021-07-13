<template>
   <div id="section1">
            <div class="service1">
                <div class="note1"><h6>Our services</h6> </div>
            </div>


            <div class="notes1">

            <div id="note2" class="noteCard" >  
                   
                       <div><img class="iconCard" src="@/components/ourServiceSection/Group2.svg" ></div>
                    
                    <div class="text1">
                    <span>Tooth inspection</span> 
                    <p>Comprehensive review of the mouth
                    and detection of broken teeth
                    and other threats.</p>
                    </div>
                   
                </div>


                <div id="note3" class="noteCard">
                    
                    <div><img class="iconCard"  src="@/components/ourServiceSection/Group3.svg" ></div>
                  
                <div class="text1">
                <span>Tooth removal</span> 
                <p>Any broken tooth is a threat to the body,
                    so this danger should be removed
                    from the mouth.</p>
                </div>
            </div>



                <div id="note4" class="noteCard">
                      <div>
                          <img class="iconCard" src="@/components/ourServiceSection/Group4.svg" ></div>
                  
                <div class="text1">
                <span>Removal of tartar</span> 
                <p>Tartar is the enemy of every human being, because through his presence we have unpleasant breath.</p>
                </div>
            </div>
                
                <div id="note5" class="noteCard">
                    <div>
                        <img class="iconCard" src="@/components/ourServiceSection/Group5.svg" >
                    </div>
                  
                <div class="text1">
                <span>Polishing and cleaning</span> 
                <p>A simple and safe polishing treatment improves the health of teeth that
                    will get a better look.</p>
                </div>
            </div>



                <div id="note6" class="noteCard">
                    <div>
                    <img class="iconCard" src="@/components/ourServiceSection/Group6.svg" >
                </div>
              
            <div class="text1">
            <span>Dental implants </span> 
            <p>The best solution when you can not save
                a healthy tooth and you need to apply artificial solutions.</p>
            </div>
        </div>
                <div id="note7" class="noteCard"><div>
                    <img class="iconCard" src="@/components/ourServiceSection/Group7.svg" >
                </div>
              
            <div class="text1">
            <span>Effective protection </span> 
            <p>The cheapest tooth protection
                is their cleaning and a regular
                visit to the dentist.</p>
            </div></div>
                 
            </div>
     
        </div>

</template>

<script>

 
export default {

}
</script>

<style>
  
#section1{
    background-color: #F7F7F7;
   padding-bottom: 10%;
   

}
.service1{
    display: grid;
    grid-template-columns: 30% ;
    height: auto;
    justify-content: center;  
  
   margin-bottom: 0;
    
}


.note1 {
    text-align: center;
    border-bottom: solid #25E6C8;
        
    height: 190px;
       
    padding-top: 10px;
    
    
    margin-bottom: 50px;
    margin-top: 25px;
    
}
.note1 h6{
    font-family: Roboto Slab;
    font-weight: normal;
    font-size: 2.5rem;
    padding-top: 110px;

}





/* notes*/

.notes1{
  display: grid;
  grid-gap: 15px ;
  grid-template-columns: 30% 30% 30%;
  
  font-size: 22px;
    font-family: Roboto Slab;
    justify-content: center;  
}




.noteCard{
    
    background-color: #FFFFFF;
   
    height: 320px;
   border-radius: 10px;
    padding-top: 10%;
    text-align: center;
     font-size: 30px;
}
.noteCard:hover{
    
    
    box-shadow: 5px 10px 10px rgb(0, 0, 0, 0.16);
}
.iconCard {
    
  background-color: #25E6C8;
    padding: 15px;
    width: 90px;
    height: 90px;
    border-radius: 50%;
   
}
.iconCard:hover{
    background-color:#2BAAEC;
}

.text1{
    margin-top: 5%;
   
}
.text1 span{
    font-size: 22px;
   
}
.noteCard p{
      font-size: 12px;
    padding-left: 30%;
    padding-right: 30%;
    padding-top: 0;
    margin-top: 0;
 
} 
</style>