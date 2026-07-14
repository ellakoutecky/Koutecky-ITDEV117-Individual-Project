## Eevee Evolution Guide

The app begins with displaying a welcome message and a menu containing Eeevee and all of it's evoltuons. The user will enter the number of the pokemon that they want to learn about. 

The app checks the numner entered by the user. It will then display the name, type, evolution method, and description of the selected Pokemon. 

After displaying the information about the pokemon, the application will ask whether the user wants to view another Pokemon. If the user chooses yes, the main menu is displayed again. However, if the user chooses no, then the application displays a goodbye message and ends. 

## Pseudocode 

    Start

      Output "Welcome to the Eevee Evolution Guide! :)" 

      selection = 0 

      While selection does not equal 10 

      Output "Please choose a Pokemon!:" 
      Output "1. Eevee" 
      Output "2. Jolteon"
      Output "3. Vaporeon" 
      Output "4. Espeon" 
      Output "5. Flareon" 
      Output "6. Leafeon" 
      Output "7. Umbreon" 
      Output "8. Sylveon" 
      Output "9. Glaceon" 
      Output "10. Exit" 

    Input selection 

    If selection equals 1 
      Output "Eevee" 
      Output "Type: Normal" 
      Output "Eevee can evolve into several different Pokemon." 

    Else if selection equals 2 
      Output "Jolteon" 
      Output "Type: Eletric" 
      Output "Eevee evolves into Jolteon with a Thunder Stone!" 

    Else if selection equals 3
      Output "Vaporeon" 
      Output "Type: Water" 
      Output "Eevee evolces into Vaporeon with a Water Stone!" 

    Else if Selection equals 4
      Output "Espeon" 
      Output "Type: Psychic" 
      Output "Eevee evolves into Espeon with high friendship during the day!" 

     Else if Selection equals 5 
       Output "Flareon" 
       Output "Type: Fire"
       Output "Eevee evoloves into Flareon with a Fire Stone!" 

      Else if Selection equals 6 
        Output "Leafeon" 
        Output "Type: Grass" 
        Output "Eevee evolves into Leafeon with a Leaf Stone!" 

      Else if Selection equals 7 
        Output "Umbreon" 
        Output "Type: Dark" 
        Output "Eevee evolves into Umbreon with high friendship during night time!" 

        Else if Selection equals 8 
          Output "Sylveon" 
          Output "Type: Fairy" 
          Output "Eevee evolves into Sylveon with high friendship while knowing a Fairy type move!" 

          Else if Selection equals 9
            Output "Glaceon" 
            Output "Type: Ice" 
            Output "Eevee evolves into Glaeon with an Ice Stone!" 

          Else if selection equals 10 
            Output "Thank you for using the Eevee Evolution Guide!"

          Else 
            Output "That is not a valid selection! :(" 

          End if 
          
        End While
        
      Stop 

      

      
