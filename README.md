# actividadClaseCondiciones


# (double or string) -> string
# si a > 0 entonces "es mayor que cero"
# si a < 0 entonces "es menor que cero"
# si no " es otra cosa"
# si a <-"hello.world" -> "otra cosa"


a <- "hello.world"
x <- 5


if(grepl("[A-Za-z,. 0]",a)){
  if(grepl("[A-Za-z,. ]",a)){
    print("Amarillo")
   }else{
    print("cat")
  }
}else if(a>0){
  print("magenta")
}else{
  print("calipso")
}


#Profesores, este es mi resultado despu�s de volver a intentar
#que las condiciones funcionaran, �est� correcto?