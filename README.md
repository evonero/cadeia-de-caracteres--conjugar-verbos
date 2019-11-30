# cadeia-de-caracteres--conjugar-verbos
def programa():     
    verbo=input('verbo regular: ')     
    conjugacao=['eu','tu','ele','nos','vos','eles']     
    sufixoAR=['o','as','a','amos','ais','am']     
    sufixoER=['o','es','e','emos','eis','em']     
    radical=verbo[0:-2]     
             
    for c in range(0,6):                        
        if verbo[-2:] == 'ar':            
            print(conjugacao[c]+' '+radical+sufixoAR[c])         
        else:              
            print(conjugacao[c]+' '+radical+sufixoER[c])                                      
programa()



