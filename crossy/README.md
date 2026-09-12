# Crossy Chicken: NYC Street Edition

## About the Game
Crossy Chicken: NYC Street Edition is an urban based setting of Crossy Road. It differs from the standard Crossy Road with its barriers being hot dog stands, buildings, trash cans, and subway entrances instead of trees and logs. In addition, this NYC Street Edition of Crossy Road has subway tunnel that can be entered and transported to the closes subway exit tunnel.

## How to Play
### Controls
* **▲ / W**: Hop forward
* **▼ / S**: Hop backward
* **◄ / A**: Hop left
* **► / D**: Hop right
* **Spacebar / Enter**: Restart game after Game Over

### Scoring & Losing
* **Scoring:** 
  * Each new forward row reached awards **+1 point**.
  * Collecting a floating gold coin awards **+1 point** and increments your coin counter.
  * Taking a subway entrance teleports you forward to the next available exit station (located in the middle 8 tiles) and instantly credits you with all the distance points skipped during the ride.
  * Your all-time highest distance is saved locally across sessions.
* **Game Over Conditions:**
  * Getting struck by oncoming traffic (sedans or yellow cabs).
  * Falling behind the bottom edge of the creeping camera ("TOO SLOW!").

## Tools and Strategy
* **AI Model & Tools Used:** Google Gemini
* **Strategy:** The strategy used was to build a basic functioning Crossy Road game from an initial AI prompt summarizing key functionalities of Crossy Road. Then bugs were analyzed and questions/adjustments were entered into Gemini to be fixed. After the structure and functionality of the game was bug free, AI was prompted to change the design to match an urban city design. The same chicken character was kept because it is cute.

## Known Issues & Unfinished Items
* **Buildings Block:** The height of the buildings block the view of the open tiles behind the buildings. This could make subway exits or the chicken concealed from the view of the game player.