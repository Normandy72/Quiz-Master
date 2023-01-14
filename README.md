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

## What is an Array?
* A grouping of multiple variables of the same type.
* Each item stored in an array is called an 'element'.
* Each element can b accessed by its index number.
* Counting starts at zero.

`int[] oddNumbers = {1,3,5,7,9};`

`int[] oddNumbers = new int[5];`

## What is a Loop?
* Repeat an event until some condition is met.
* Very powerful for counting or iterating.
* One type of loop is called a 'For Loop'.
* Loop a set number of times.

#### For Loop
```
for(int i = 0; i < n; i++)
{
    // do stuff
}
```

`int i = 0` - runs once before the code block is executed; sets up the iterator.

`i < n` - defines the loop condition; tells the loop when to stop. Be careful of infinite loops!

`i++` - executes at the end of every loop; used to increment or decrement the iterator.

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