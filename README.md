# Limite-de-caracteres
Limite de caracteres na página

        // Limite de caracteres
        $.each($("Classe que sera modificada com ..."), function(){
           alt=$(this).text().length;
           if( alt>quantidade de caracteres aqui ){
             $(this).text($(this).text().substr(0,60)+' ...');
           }
       }); // Final caracteres
