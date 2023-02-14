using System;

namespace ChooseYourOwnAdventure
{
  class Program
  {
      static void Main(string[] args)
    {
      /* THE MYSTERIOUS NOISE */

      // Start by asking for the user's name:
      Console.Write("What is your name?: ");
      string name = Console.ReadLine();
      Console.WriteLine($"Hello, {name}! Welcome to our story.");

      Console.WriteLine("It begins on a cold rainy night. You're sitting in your room and hear a noise coming from down the hall. Do you go investigate?");
      Console.Write("Pick YES or NO: ");
      string noiseChoice = Console.ReadLine();
      noiseChoice = noiseChoice.ToUpper();

     if (noiseChoice == "NO")
     {
       Console.WriteLine("Not much of an adventure if we don't leave our room!");
       Console.WriteLine("The End");
     }
     else if (noiseChoice == "YES")
     {
       Console.WriteLine("You walk into the hallway and see a light coming from under a door down the hall");
       Console.WriteLine("You walk towards it. Do you open it or knock?");
     }
Console.Write("Pick OPEN or KNOCK: ");
string doorChoice = Console.ReadLine();
doorChoice = doorChoice.ToUpper();

if (doorChoice == "KNOCK")
{
  Console.WriteLine("A voice behind the door speaks. It says, -Answer this riddle:- ");
  Console.WriteLine("-Poor people have it. Rich people need it. If you eat it you die. What is it?-");
  Console.Write("Type your answer: ");
  string riddleAnswer = Console.ReadLine();
  riddleAnswer = riddleAnswer.ToUpper();
if (riddleAnswer == "NOTHING")
{
  Console.WriteLine("The door opens and NOTHING is there");
Console.WriteLine("You turn off the light and run back to your room and lock the door.THE END.");
} 
else 
{
  Console.WriteLine("You answered incorrectly. The door doesn't open. THE END");
}

}
else if (doorChoice == "OPEN")
{
  Console.WriteLine("You answered incorrectly. The door doesn't open. THE END.");
  Console.Write("Enter a number between 1-3: ");
  string keyChoice = Console.ReadLine();
  keyChoice = keyChoice.ToUpper();

  switch (keyChoice)
  {
    case "1":
    Console.WriteLine("You choose the first key. Lucky choice! The door opens and NOTHING is there. Strange... THE END");
    break;
    case "2":
    Console.WriteLine("You choose the second key. The door doesn't open.THE END");
    break;
    case "3":
    Console.WriteLine("You choose the third key. The door doesn't open.THE END.");
    break;
    default:
    Console.WriteLine("we dont have that key. The end");
    break;
  }
  

}
    }
  }
}
