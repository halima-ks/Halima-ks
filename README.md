# Halima-ks
window.addEventListener("load", event => main());

const main = () => {
	
	console.log("MAIN");
         test_voiture();

let user = {  
firstName: "ksal",
lastName: "halima",
addresse: "56 rue volve",
eMail: "halima95140@outlook.fr",
phoneNumber: "0766666666",




  };
//console.log{"bonjour, "+ " "+ user.firstName, + "" + user.lastName + "!"};
console.log("bonjour,", user.firstName, user.lastName, "!");

//let capFirstName =user.firstName.charAt(0).toUpperCase();  // charAt()-> sort moi le premier caractere et toUpperCase() -> met en majuscule

console.log(capFirstName);   //affiche le premier caractere
  
let capFirstName =user.firstName.slice(0).toUpperCase(); //supp la premier lettre 

let laCleDynamique = "firstName";
user[laCleDynamique]
//testPileOuFace(250000);


//console.log(testPileOuFace(250000);

//on declare un nouveau tableau
let tab = []; // let tab = new array(); nouveau tableau 
for (let i =0; i < 500; i++) tab.push(1);                //500 nombre aleatoirs dans le tableau 
//for.forEach(element => console.log(element));         //afficher les elements du tableau un par un 
//autre methode pour afficher 
let by2 = tab.push(element => element *2 );
console.log(by2);                                     //afficher le tableau 

let sum = tab.reduce((acc,element)=> {
   return acc + element;
  

}, 0)



}

const testPileOuFace = amount => {
   let result = {pile : 0, face : 0 }; //declaration d'un dc result 
   for(let i = 0 ; i < amount; i++ ) result[pileOuFace()]++;
   return result;
  
}
   console.log(result);
}

const capFirstLetter = value => value.charAt(0).toUpperCase() + value.slice(1);

const pileOuFace =() => Math.random() > 0,5 ? "face" ; "pile" ;     //renvoie vrai ou faux 


  }
