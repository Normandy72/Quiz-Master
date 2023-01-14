# ~ Unity ~
## UI Canvas
* UI = User Interface.
* Text, buttons, sliders, menus, etc.
* UI elements live on the "Canvas".
* The canvas generally exists in "Screen Space" and is mostly separate from the game world.
* You can have multiple canvases.
***
# ~ C# ~ 
## What Is A Scriptable Object?
* It's just a data container.
* Keeps the data out of our scripts.
* Help up save memory by storing data in one place.
* They don't need to be attached to game objects.
* They're lightweight and convenient.
* Act as a template for consistency.

#### Examples
* Weapon stats in an RPG.
* Card data in a CCG.
* We will be using them to store question data:
    * Question text
    * Possible answers.
    * Correct answer.

## Getter Methods
* Gives a script read-only access to a private variable.
* Protects the contents of a private variable.  

***
## Quiz Questions
1. What is a correct syntax to output "Hello World" in C#?
    * `cout << "Hello World";`
    * `print("Hello World");`
    * `Console.WriteLine("Hello World");` (correct)
    * `System.out.println("Hello World");`
2. How do you insert comments in C# code?
    * `// this is a comment` (correct)
    * `# this is a comment`
    * `/* this is a comment`
    * `@ this is a comment`
3. Which data type is used to create a variable that should store text?
    * `myString`
    * `str`
    * `string` (correct)
    * `Txt`
4. How do you create a variable with the numeric value 5?
    * `num x = 5;`
    * `let x = 5;`
    * `x = 5;`
    * `int x = 5;` (correct)
5. Which operator can be used to compare two values?
    * `<>`
    * `==` (correct)
    * `=`
    * `><`