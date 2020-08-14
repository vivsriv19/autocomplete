# autocomplete

Enter john@  

Then the list of available handles will show up as autocomplete suggestion  


Call function autoComplete({  
                            inputId: 'autocompleteInput', // id of input  
                            data: JSON.parse(handles), // json data of handles  
                            callback: function(){ // callback to be trigger on any handle selection  
                                console.log("hey")  
                            }  
                            }).init();    