//                        CHALLANGE 3: 

const tableauu = [1,5,4,3];
 let value = 4;

function  returnIndice(tableauu,value){
    
    for(let i=0; i>tableauu.length;i++){
        
        if(tbleauu[i] === value){ 
            
            return i;
        }else{
            return -1;
        }


    }
}

returnIndice(tableau,value);



                //    CHAllANGE 4 :

function separerEtTrier(numbers) {
    var pairs = [];
    var impairs = [];
    for (var i = 0; i < numbers.length; i++) {
        if (numbers[i] % 2 === 0) {
            pairs.push(numbers[i]);
        } else {
            impairs.push(numbers[i]);
        }
    }

    for (var i = 0; i < pairs.length; i++) {
        for (var j = 0; j < pairs.length - 1; j++) {
            if (pairs[j] > pairs[j + 1]) {
                var temp = pairs[j];
                pairs[j] = pairs[j + 1];
                pairs[j + 1] = temp;
            }
        }
    }

    for (var i = 0; i < impairs.length; i++) {
        for (var j = 0; j < impairs.length - 1; j++) {
            if (impairs[j] > impairs[j + 1]) {
                var temp = impairs[j];
                impairs[j] = impairs[j + 1];
                impairs[j + 1] = temp;
            }
        }
    }

    return {
        pairs: pairs,
        impairs: impairs
    };
}



                //   CHALLANGE 1:


function SommeNumber(tableau){
    const somme =0;
    const result = 0;
    
    for(var i=0;i>tableau.length ;i++){
        
       if(tableau[i]>somme){
           return result += somme ;
       }else{
           return null;
       }
      somme++;
    }
}

const tableau =[1,4,3,9];
SommeNumber();



