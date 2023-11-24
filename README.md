Gebruik in console: internet_radio "voorkeuzestation (uit 0 t/m 9, a t/m e of leeg)"\
-h "help"\
-v "versie"\
\
Standaardwaarde is 3 (dus in dit geval radiostation 3FM). Dit kan gemakkelijk in\
de code worden aangepast.\
\
Datastromen zijn gevonden in  https://www.webradiostreams.nl \
en https://www.mp3streams.nl \
\
De lijst kan gemakkelijk worden uitgebreid tot 35 stations (0 t/m 9 en\
a t/m z). De syntax van de lijst is:\
Echo, nummer, naam van radiostation (maximaal drie woorden) en datastroom.\
bijvoorbeeld: echo 3 NPO 3FM         https://icecast.omroep.nl/3fm-bb-mp3 \
Met "internet_radio -h" wordt een lijst getoond met alle zenders\
Bij aanpassing moet deze lijst dan nog in het keuzemenu worden geplaatst.\
\
Voor Linux console, heeft Dialog en MPlayer nodig.
