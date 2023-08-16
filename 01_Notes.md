## Structure of C Sharp Program

- **Namespace declaration:** A namespace is used to organize your code and to provide a way to create globally unique types. The using keyword is used to include the namespaces in your program.
- **Class:** A class is a blueprint for an object. It defines the data and behavior of the object.
- **Class methods:** Methods define the behavior of the class. They are blocks of code that perform specific tasks.
- **Class attributes:** Attributes provide additional information about the class or its members. They are used to add metadata to your code.
- **Main method:** The Main method is the entry point of your program. It is where the execution of your program begins.
- **Statements and expressions:** Statements and expressions are used to perform actions or calculations in your program.
- **Comments:** Comments are used to add notes or explanations to your code. They are ignored by the compiler.


```
using System;

namespace HelloWorldApplication {
   class HelloWorld {
      static void Main(string[] args) {
         /* my first program in C# */
         Console.WriteLine("Hello World");
         Console.ReadKey();
      }
   }
}

```



- The first line of the program, using System;, uses the using keyword to include the System namespace in the program. This allows the program to access classes and other members defined in the System namespace without having to fully qualify their names. A program can have multiple using statements to include multiple namespaces.
- The next line, namespace HelloWorldApplication, declares a new namespace called HelloWorldApplication. A namespace is used to organize code and to prevent naming conflicts. It can contain classes, interfaces, structs, enums, and other namespaces.
- Inside the HelloWorldApplication namespace, a new class called HelloWorld is declared using the class keyword. A class is a blueprint for creating objects and defines the data and behavior of those objects. Classes can contain fields, properties, methods, events, and other members.
- The HelloWorld class contains a single method called Main. This method is declared as static, which means that it belongs to the class itself rather than to any specific instance of the class. The Main method is also the entry point of the program, which means that it is the first method that is called when the program starts.
- Inside the Main method, there is a comment that begins with /* and ends with */. Comments are used to add notes or explanations to your code and are ignored by the compiler.
- The next line of code inside the Main method uses the WriteLine method of the Console class to print “Hello World” to the console. The Console class is defined in the System namespace and provides methods for interacting with the console.
- The final line of code inside the Main method uses the ReadKey method of the Console class to wait for user input before exiting. This prevents the console window from closing immediately after displaying “Hello World”.

- ## Rules for Writing the Good/Clean Code

- **Keep everything simple and clean:** Avoid complex coding and try to break down complex programs into smaller, more manageable subtasks.
- **Be consistent:** Follow a consistent coding style and adhere to your coding standards.
- **Have a coding standard:** Define a set of rules for how you write your code, such as using PascalCasing for class, function, and property names, and camelCasing for member variables, parameters, and local variables.
- **Comment and document your code:** Use comments to explain what your code does and how it works. You can use // or /*...*/ for regular comments, or /// for XML documentation comments that can be used by Visual Studio and other tools to generate documentation.
- **Test your code:** Use unit testing tools to test your code and ensure that it works as expected.

### There are several notations that can be used when naming variables and other identifiers in code.

- **Hungarian Notation:** This notation involves prefixing the name of a variable with a short sequence of characters that indicates its data type. For example, an integer variable representing a person’s age might be named intAge, and a string variable representing a person’s name might be named strName.
- **CamelCasing Notation:** This notation involves capitalizing the first letter of each word in a multi-word identifier, except for the first word, which is written in lowercase. For example, variables representing a person’s last name, first name, forename, and surname might be named lastName, firstName, foreName, and surName, respectively.
- **PascalCasing Notation:** This notation is similar to CamelCasing, but the first letter of the first word is also capitalized. For example, variables representing a person’s first name, last name, forename, and surname might be named FirstName, LastName, ForeName, and SurName, respectively.
- **Snake Notation:** This notation involves writing each word in an identifier in lowercase and separating them with underscores. For example, variables representing a person’s last name, first name, forename, and surname might be named last_name, first_name, fore_name, and sur_name, respectively.



### Writing the code in the Notepad and running it using the command propt steps:

- Open a new Notepad file by pressing Ctrl+N or by searching for Notepad in the Windows search box.
- Write your C# code in the Notepad file.
- Save the file with a .cs extension to indicate that it is a C# source code file. You can do this by pressing Ctrl+S or by going to the File menu and selecting Save.
- Choose a location to save the file and give it a name.
- Once you have saved your C# code in a text file, you can compile it using the Developer Command Prompt for Visual Studio. Here are the steps to do so:

#### Open the Developer Command Prompt for Visual Studio.

- Navigate to the directory where you saved your C# source code file.
- Use the csc command to compile your code. For example, if your source code file is named demo.cs, you would enter the command csc demo.cs.
- If your code compiles successfully, an executable file with the same name as your source code file (but with a .exe extension) will be created in the same directory.
