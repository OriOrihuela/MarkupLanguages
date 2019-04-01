Exercise 1:
    result: <nombre>IES Abastos</nombre>
    code command: //ies/nombre

Exercise 2:
    result: http://www.iesabastos.org
    code command: //ies/web/text()

Exercise 3:
    result: Administración de Sistemas Informáticos en Red
            Desarrollo de Aplicaciones Web
            Sistemas Microinformáticos y Redes
    code command: //ciclos/ciclo/nombre

Exercise 4:
    result: id="ASIR"
            id="DAW"
            id="SMR"
    code command://ciclos/ciclo/@id

Exercise 5:
    result: año="2009"
            año="2010"
            año="2008"
    code command://ciclos//@año

Exercise 6:
    result: <ciclo id="SMR">
                <nombre>Sistemas Microinformáticos y Redes</nombre>
                <grado>Medio</grado>
                <decretoTitulo año="2008"/>
            </ciclo>
    code command: //ciclos/ciclo[1]
    code command 2Steps: //grado[.="Medio"]/..

Exercise 7:
    result: <nombre>Administración de Sistemas Informáticos en Red</nombre>
            <nombre>Desarrollo de Aplicaciones Web</nombre>
    code command: //nombre[../grado="Superior"]
    code command twoSteps: //ciclo[grado="Superior"]/nombre

Exercise 8:
    result = Administración de Sistemas Informáticos en Red
            Sistemas Microinformáticos y Redes
    code command: //nombre[../decretoTitulo/@año<2010]/text()
    code command twoSteps: //@año[.<2010]/../../nombre/text()

Exercise 9:
    result = Desarrollo de Aplicaciones Web
            Sistemas Microinformáticos y Redes
    code command: //nombre[../decretoTitulo/@año=2008 or ../decretoTitulo/@año=2010]/text()
    code command twoSteps: //decretoTitulo[@año=2008 or @año=2010]/../nombre/text()