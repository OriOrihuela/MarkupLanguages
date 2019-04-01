## Exercise 1:

    result = Aplicaciones web
    code command = //modulo[ciclo="SMR"]/nombre/text()

## Exercise 2:
    
    result = Administración de Sistemas Informáticos en Red
             Desarrollo de Aplicaciones Web
    code command = //ciclo[@id="ASIR"]/nombre/text()
                   //ciclo[@id="DAW"]/nombre/text()

## Exercise 3:

    result = Gestión de bases de datos
             Lenguajes de marcas y sistemas de gestión de información
             Implantación de aplicaciones web
    code command = //modulo[ciclo="ASIR"]/nombre/text() 

## Exercise 4:

    result = Aplicaciones web
    code command = //modulo[ciclo="SMR"]/nombre/text()

## Exercise 5:

    result = Superior
             Superior
    code command = //ciclo[@id="ASIR"]/grado/text()
                   //ciclo[@id="DAW"]/grado/text()