
    var pin: Int   = 1234
    var intentos: Int = 0
    var contraseña: Int = 1235
    
    do{
       println("Digite su pin de google")
       
       println("Digite su contraseña para ingresar : ${contraseña++}")
       intentos++
    }while(intentos < 3 && contraseña !=	pin)
    if(intentos ==3)
        
        println("Por el numero de intentos su targeta fue bloqueada")
    
  // validacion de intentos de contraseña //
