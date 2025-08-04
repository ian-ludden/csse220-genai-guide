---
tags:
  - teaching
  - csse220
date: 2025-07-02
selfnote: Adapted from POGIL Act01, gen-ai.tex model.
---
# Using GenAI to transfer programming skills to Java 
GenAI tools can help you switch from another programming language (Python, C++, etc.) to Java. 
## Step 1: Set up template file
Copy/paste the Java code below into a file named `ConvertToJava.java`. 
```java
/**
 * Template for converting from another language to Java.
 *
 * @author Ian Ludden
 */

public class ConvertToJava {
    public static void main(String[] args) {
        // Create myFunction as a static function in this same class, adding/modifying parameters/arguments as needed.

        // Example:
        myFunction(25.0); // Modify this to test your function.

        // or, if you want to return and print some value:
        // [datatype] result = myFunction([arguments]);
        // System.out.println(result);
    }

    // TODO: Add your converted function here.

    // === EXAMPLE ===

    // Python version:
    // def celsiusToFahrenheit(celsius: float) -> None:
    //   fahr = celsius * 9.0 / 5 + 32
    //   print("{0:.1f} C = {1:.1f} F".format(celsius, fahr))
    //
    // Java version:
    
    /**
      * Convert Celsius to Fahrenheit and print result
      * @param celsius - temperature in Celsius
      */
    public static void myFunction(double celsius) {
        double fahr; // temp in fahrenheit
        String str;
        fahr = celsius * 9.0 / 5 + 32;
        str = String.format("%.1f C = %.1f F\n", celsius, fahr);
        System.out.println(str);
    }
}
```
## Step 2: Select a familiar non-Java code snippet
Find a short function or code snippet (ideally, one you wrote) in a non-Java language with which you are familiar. 
## Step 3: Prompt GenAI for a Java version
Have a GenAI tool (e.g., [Claude](https://claude.ai/), [ChatGPT](https://chatgpt.com/), [Gemini](https://gemini.google.com)) convert your code into Java. See [this example](https://claude.ai/share/d02ca4fd-35c3-47de-aac1-e7fa8204fe26). 
## Step 4: Test the GenAI-produced Java version
Test the Java version: copy/paste into `ConvertToJava.java` and modify the method call. If the response doesn't explain the changes between the Java version and the other-language version you gave it, ask. 
## Step 5: Reflect and Repeat
What similarities and differences do you notice between the Java and non-Java solutions? Take some notes in a way to help you remember how to write code "the Java way" in the future. Repeat with other non-Java code to help you adapt to Java syntax and features. Also, consider prompting the GenAI tool to give you several different Java implementations of the same function and explain each. 
## Why not just translate forever? 
In theory, you *could* avoid learning Java syntax and features for as long as possible and just write all code in your favorite other language, then have GenAI translate it to Java. But that would be like studying abroad in Spain and just using a translation app instead of actually learning Spanish. Sure, you could get by in many situations, but you would miss out on many nuances and would not know when your app gave you a bad translation. More importantly, you would not experience the growth and satisfaction of learning a new language. 
