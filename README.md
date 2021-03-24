# lab5-Android-ver2
Inledande beskrivning
Att handla är som vi alla vet, en av de jobbigare sysslorna vi som människor behöver ta oss an på
daglig basis. Kökshjälpen vill underlätta vardagen genom att alltid erbjuda sina användare en up to
date lista på vad som finns i ditt kök, vad börjar bli gammalt samt vad behöver handlas för att kunna
lösa en av de andra extrema frågorna i vardagen “vad blir det för mat”.
Det finns många lösningar på marknaden redan men idéen är att ta det ett steg längre och med hjälp
av modern teknik införa en ny fysiskenhet i användarens hem. En “dosa” som kan scanna streckkoder
på matvaror. Detta så när man handlat kan ha en uppdaterad lista på vad man har hemma. I
framtiden skall även idéen säljas in hos till exempel Ica för att kunna få information om köpta varor
direkt ifrån butiken.
Fysiskenhet / server
Den fysiska enheten samt en server är redan byggd och testanvändare
har nu en sträckkodsavläsare monterad vid sitt kylskåp.
http://kitchen-help.herokuapp.com/ är servern vi kan vända oss till för
att få information över vad som finns i systemet för närvarande.
End-pointen /kitchen (http://kitchen-help.herokuapp.com/kitchen) ger
oss en lista i JSON format över inskannade varor. För dig som siktar på
betyget Godkänd så är detta den enda adressen du behöver göra anrop
emot i din applikation.
Din uppgift
Företaget behöver nu din hjälp att skapa en mobil Android applikation att sätta i händerna på riktiga
användare för att testa idéen ytterligare samt att ha något att visa upp för att hitta intressenter som
är villiga att investera i vidareutveckling av idéen. Din applikation kommer alltså i första hand visas på
mässor tillsammans med de övriga delarna i systemet.
Funktionalitet
Minsta funktionalitet som skall finnas i applikationen vid inlämning:
1. Lista alla matvaror som för närvarande finns i köket (inskannade i systemet, läses ifrån
http://kitchen-help.herokuapp.com/kitchen).
2. Ta bort en vald vara ifrån systemet (görs genom en DELETE request till http://kitchenhelp.herokuapp.com/kitchen/<varans-id>)
3. I applikationen så skall det finnas en webview som navigerar användaren till sidan
https://www.tasteline.com/
4. Det skall finnas en välkomst vy i applikationen.
Du är självklart välkommen att utöka funktionaliteten i applikationen men börja med att säkerställa
att dessa efterfrågade punkter finns med.
Hjälpmedel
Du hittar server med dokumentation via: https://kitchen-help.herokuapp.com/ Ifall det inte finns
varor i systemet så kan det läggas till via adressen.
