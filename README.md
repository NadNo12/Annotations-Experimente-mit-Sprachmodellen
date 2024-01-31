# Annotations-Experimente-mit-Sprachmodellen
Verschiedene Experimente mit Sprachmodellen werden durchgeführt, wobei unterschiedliche Annotationstechniken angewendet und die daraus resultierenden Daten ausgewertet werden. Hauptziel ist es, die Leistungsfähigkeit und Genauigkeit der Modelle anhand dieser Annotationsexperimente zu bewerten. 

# Annotationsaufgabe


Überprüfung auf die Konstruktivität von Kritiken zur Identifizierung von gefälschten oder voreingenommenen negativen Rezensionen von Videospielen, die auf Vorurteilen oder anderen basierenden Gründen beruhen.



# Datenbasis

Negative Spielrezensionen von den Plattformen Metacriitic und IMDB, die möglicherweise Anzeichen von gefälschten oder voreingenommenen Bewertungen aufweisen. Die Rezensionen werden in eine CSV-Tabelle exportiert.

# Sprachmodell / Interface


ChatGPT4 und Claude werden verwendet, die auf Voreingenommenheit/Hate speech oder gefälschten Bewertungen fokussieren sollen. 
Die Sprachmodellle sollen nach persönlichen Beleidigungen, Diskriminierung und Belästigung suchen, insbesondere nach Rassismus, Sexismus, Ableismus, religiösem Hass, Homophobie und Transphobie, Klassismus, Bodyshaming sowie Drohungen und Gewalt. Sie sollen jede einzelne Rezension durchgehen und diese in einer neuen Spalte mit 
"Hate speech" markieren, wobei der Wert 1 für eine Rezension steht, die Hassrede enthält, und 0, wenn der negative Kommentar nichts Auffälliges enthält. Zudem sollen sie ihre Begründungen für jede Bewertung in einer neuen Spalte hinzufügen. Die Sprachmodelle sollen dabei so detailliert wie möglich sein und die markierten Schlüsselwörter hervorheben. 
Es ist wichtig, zu beachten, dass eine persönliche Unzufriedenheit mit dem Spiel akzeptabel ist. Die Ergebnisse sollen in einer CSV Tabelle ausgegeben werden.

# Experimentdesign

Negative Rezensionen vom Videospiel "The Last of Us Part II" sammeln und potenzielle Verdachtsfälle für gefälschte oder voreingenommene Bewertungen anhand von bestimmten Anhaltspunkten im Text identifizieren. Das Sprachmodell soll diese Bewertungen identifizieren und markieren und in eine Tabelle ausgeben. Eine manuelle Überprüfung wird dann durchgeführt, um die Genauigkeit der automatisierten Erkennung zu bewerten. Anschließend werden die Ergebnisse der automatisierten Erkennung mit den manuell überprüften Bewertungen miteinander verglichen, um die Zuverlässigkeit und Genauigkeit zu evaluieren.
