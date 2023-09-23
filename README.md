# Writing Good Documentation
## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses codeblocks whenever possible because it allows others to copy and paste their code to replicate or to research issues.

- In order to create a create a code block use 3 back ticks(```)
- Not to be confused with quotation (''')
```
using System;

public class Person
{
    // Properties
    public string FirstName { get; set; }
    public string LastName { get; set; }
    public int Age { get; set; }

    // Constructor
    public Person(string firstName, string lastName, int age)
    {
        FirstName = firstName;
        LastName = lastName;
        Age = age;
    }
}
```

- When you can you should attempt to apply syntax highlighting to your code blocks

``` C#
using System;

public class Person
{
    // Properties
    public string FirstName { get; set; }
    public string LastName { get; set; }
    public int Age { get; set; }

    // Constructor
    public Person(string firstName, string lastName, int age)
    {
        FirstName = firstName;
        LastName = lastName;
        Age = age;
    }
}
```
- This is an image
<img width="200px" src="https://github.com/iykeDigit/example/assets/49472273/8ecb6ec6-39af-44d4-9a0a-5e24f70aff6d" />

- Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Unhandled exception. System.IndexOutOfRangeException: Index was outside the bounds of the array.
   at Program.Main() in C:\path\to\your\file\Program.cs:line 9
```
> Here's an example of using a codeblock for an error that appears in bash.


## Step 3 - Use Github Flavoured Markdown Task Lists
Github extends Markdown to have a list where you can check off items[^1]

- [x] Finish Step 1 `:smile:`
- [x] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emoji Cheat Sheet
Github Flavoured Markdown (GFM) supports emoji shortcodes
Here are some examples
- :cloud:
- :partly_sunny:
- :ringed_planet:

| Name | Shortcode | Emoji |
| ---  | --- | --- | 
| Cloud | `:cloud:`  | :cloud:
| Partly Sunny | `:partly_sunny:`  | :partly_sunny:
| Ringed Planet | `:ringed_planet:`  | :ringed_planet:

## Step 5 - how to create a table
You can use the following markdown format to create a table
```md
| Name | Shortcode | Emoji |
| ---  | --- | --- | 
| Cloud | `:cloud:`  | :cloud:
| Partly Sunny | `:partly_sunny:`  | :partly_sunny:
| Ringed Planet | `:ringed_planet:`  | :ringed_planet:
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options [^2].

## Step 6 - How to take screenshots

- A screenshot is when you capture a part of your screen from your laptop, desktop or phone.
- This is not to be confused with taking a photo wtth your phone.
- **Do do this instead**
 <img width="200px" src="https://github.com/iykeDigit/example/assets/49472273/8ecb6ec6-39af-44d4-9a0a-5e24f70aff6d" />







## References
- [Github](https://github.com) 
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [^1]: [GFM - Basic Writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
[^2]: [GFM- Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) 


