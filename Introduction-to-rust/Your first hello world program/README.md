Before we begin lets have a chat as to how slightly different Rust is.

In Rust,what you know as **libraries/binary** as called **crates.**
A **package** is one or more crates that provide a set of functionality(s)

Rust uses the **Cargo** key to create a package.

Let us create our first package:

Step 1: Open a terminal.

step 2: Navigate to the path where your would want your project to reside e.g Desktop/

step 3: Type **$ cargo new Hello-World**.

Now a package called Hello-world/ has been created.

Step 4: **$ cd Hello-World**

   **$ ls**
          
Step 5: You should see a similar lining of files.

   **Cargo.toml and src/** 
        
   Moving further
   
   **$ ls src/**
        
   We see the Rust source code for our package named **main.rs**



In most programming languages you always start with the main funtion.in rust we start with the fn() funtion.
the print!(); "funtion" in Rust is known as a **macro.**

The "{}" in print!("{}","Hello world"); is known as a placeholder.A single placeholder is needed when one wants to print a single value.
If you want to print several lines of text multiple place holders are needed print!("{}{}", "hello", "world");
