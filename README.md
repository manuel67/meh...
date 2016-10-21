<html>
<head>
    <title>rock paper scissors</title>
    </head>
    <body>
    
    <script>
        /* TODO:
              -user
              
              
              */
        // variables to hold our choices
        var choice1 = "rock"
        var chocie2 = "paper"
        var chocie3 = "scissors"
        
        // variables to hold the score
        var humanScore = 0;
        var computerScore = 0;
        
         // variables to hold the choices
        var humanScore = "";
        var computerScore = "";
        
        function doTurn() {
            humanChoice = "rock"; // TODO: allow user input later
            compuerChoice = "paper";
            
            if (humanChoice === compuerChoice) { // Draw
                console.log("Draw!");  
            }
            else if (humanChoice === "rock" && compuerChoice === "scissors" || humanChoice === "scissors" && computer === "paper" || humanChoice === "papaer" && computerChoice === "rock" ) { // Draw
                console.log("win");
            }
            else { // Human}
        }
        </script>
        
    </body>
</html>
