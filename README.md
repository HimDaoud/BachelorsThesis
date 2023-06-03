# BachelorsThesis
 Optimering ved simulering av glidende objekt
 Dette prosjektet går ut på å bruke et fysisk system til å finne et globalt minimum ved å sende et glidende objekt med avtagende friksjon inn i et landskap og undersøke hvor det stopper. Hvor vi ønsker å approksimere den globale minimalverdien til en funksjon. Problemstillingen er høyst aktuell innen mange sammenhenger der optimering inngår ikke minst innen maskinlæring. Tradisjonelle metoder som "gradient descent" har ofte problemer med at algoritmen "setter seg fast" i et lokalt minimum i stedet for det globale vi er interessert i.
Metoden som brukes for å finne det globale minimumet er ved å bestemme stopp-punktet til det bevegelige objektet ved hjelp av friksjonskraften, og deretter periodisk halverer friksjonen til det laveste punktet er nådd. Denne metoden inneholder to faktorer, startpunktet og starthastigheten, så metoden er nærmere til Simulering i annealing, slik at et objekt på et startpunkt kan havne i et annet geografisk område. Den forblir i den lokale nær den i «gradient descent». Når det gjelder metoden som brukes av oss, er den effektiv slik at det er mulig å nå den globale i henhold til inngangsverdiene for startpunktet og starthastigheten, og det vil bli forklart i detalj i prosjektstadier ved å kjøre ulike simuleringer vil vi forsøke å finne fremgangsmåter som, med stor sannsynlighet, finner globale minimum i stedet for lokale. Videre vil vi legge vekt på å utvikle et grafisk brukergrensesnitt (GUI/Front End) som gjør det enkelt å kjøre simuleringene for alle brukere.
