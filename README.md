function marketingLetter(firstname){
var customerNum=0
    return function (season, dogname){
    customerNum++;
if(season=="Winter"){
    console.log("Hi, " + firstname+ " it's time to schedule the " + season+ " cleanup.  At your earliest convenience please contact me at (510)828-4854 to schedule a day. Thanks. Btw, how is your dog "+ dogname+" You are customer #"+ customerNum);}
    
else if(season=="Spring"){
    console.log("Hi, "+firstname + " it's " + season+ " and it time to discuss your landscape plans for the year.  At your earliest convenience please contact me at (510)828-4854 to schedule a day. Thanks.Btw, how is your dog "+ dogname +" You are customer #"+ customerNum);}  
    
   
    }

}    


var jWright=marketingLetter("Judy")
jWright("Winter","Ruff")
var rGreene = marketingLetter("Rick");
jWright("Spring", "Patsy");
for (var i=0;i<8;i++){
    rGreene("Spring","Whoyodaddy")
}
console.log(i)
