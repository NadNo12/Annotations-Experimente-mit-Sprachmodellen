# Annotations-Experimente-mit-Sprachmodellen
Verschiedene Experimente mit Sprachmodellen werden durchgeführt, wobei unterschiedliche Annotationstechniken angewendet und die daraus resultierenden Daten ausgewertet werden. Hauptziel ist es, die Leistungsfähigkeit und Genauigkeit der Modelle anhand dieser Annotationsexperimente zu bewerten. 

# Annotationsaufgabe
Identifizierung von gefälschten oder voreingenommenen negativen Rezensionen von Videospielen, die auf Vorurteilen oder anderen Gründen basieren und nicht auf tatsächlicher Spielerfahrung.

# Datenbasis

Negative Spielrezensionen (wahrscheinlich in deutscher Sprache) von Plattformen wie Steam, Metacritic oder anderen Gaming-Communities, die möglicherweise Anzeichen von gefälschten oder voreingenommenen Bewertungen aufweisen. Entweder in einer JSON-file oder CSV-Tabelle.

# Sprachmodell / Interface


Ein Sprachmodell muss verwendet werden, das auf Erkennung von Voreingenommenheit/Hate speech oder gefälschten Bewertungen trainiert ist. Das Modell sollte auf Aspekte wie Wortwahl, Widersprüchen etc. im Text basieren.

# Experimentdesign

Negative Rezensionen von Videospielen verschiedener Genres sammeln und potenzielle Verdachtsfälle für gefälschte oder voreingenommene Bewertungen anhand von bestimmten Anhaltspunkten im Text identifizieren. Das Sprachmodell soll diese Bewertungen identifizieren und markieren. Eine manuelle Überprüfung (Stichprobe) wird dann durchgeführt, um die Genauigkeit der automatisierten Erkennung zu bewerten. Anschließend werden die Ergebnisse der automatisierten Erkennung mit den manuell überprüften Bewertungen miteinander verglichen, um die Zuverlässigkeit und Genauigkeit zu evaluieren.
