# rock-paper-scissors
You may have played rock paper scissors before. Maybe you’ve used it to decide who pays for dinner or who gets first choice of players for a team.

If you’re unfamiliar, rock paper scissors is a hand game for two or more players. Participants say “rock, paper, scissors” and then simultaneously form their hands into the shape of a rock (a fist), a piece of paper (palm facing downward), or a pair of scissors (two fingers extended). The rules are straightforward:

Rock smashes scissors.
Paper covers rock.
Scissors cut paper.

# Game Play:
The players may count aloud to three, or speak the name of the game (e.g. "Rock! Paper! Scissors!"), either raising one hand in a fist and swinging it down with each syllable or holding it behind their back. They then "throw" by extending it towards their opponent. Variations include a version where players throw immediately on the third count (thus throwing on the count of "Scissors!"), or a version where they shake their hands three times before "throwing". We are going to computerize this game play, so that computer will choose some random choice while the player will have the choice to choose one [Rock! Paper! or Scissors! ]

# Rules:
A player who decides to play rock will beat another player who has chosen scissors ("rock crushes scissors" or sometimes "blunts scissors"), but will lose to one who has played paper ("paper covers rock"); a play of paper will lose to a play of scissors ("scissors cuts paper"). If both players choose the same shape, the game is tied and is usually immediately replayed to break the tie.
   

<img width="464" alt="Screenshot 2023-10-13 120700" src="https://github.com/Divyavavilthota/rock-paper-scissors/assets/99669084/b8acaaf1-7012-4109-99bb-74294d13dabc">

# Possibe Cases;

if (player == rock) and (computer == paper); computer wins

if (player == paper) and (computer == paper); tie

if (player == scissors) and (computer == paper); player wins

if (player == rock) and (computer == rock); tie

if (player == paper) and (computer == rock); player wins

if (player == scissors) and (computer == rock); computer wins

if (player == rock) and (computer == scissors); player wins

if (player == paper) and (computer == scissors); computer wins

if (player == scissors) and (computer == scissors); tie

# Dependencies:
python
