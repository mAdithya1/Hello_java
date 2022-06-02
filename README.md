# Hello world
## how to write hello world in Java

[Code](https://github.com/mAdithya1/Hello_java/blob/main/Hello.java)

Hello World Java – [Your First Java Program Video](https://www.youtube.com/watch?v=BIUr6UNROgU)

```java
System.out.println("Hello world");
```

## Steps to Compile and Run first Java program
Here is a step by step process on how to run Java program:

1. Open Notepad from Start menu by selecting Programs > Accessories > Notepad.
2. Create a Source Code for your Hello World program in Java
```java
class name{
  public static void main(String[] arge){
    System.out.println("Hello World");
  }
}
```
3. Save the file for Java Hello World program as `name.java` make sure to select file type as all files while saving the file in our working folder `C:\workspace`
4.  Open the command prompt. Go to Directory `C:\workspace.` Compile the code of your Hello world Java program using command,
```
cd workspace
javac name.java
```
5. If you look in your working folder, you can see that a file named `name.class` has been created.
6. To execute the code, enter the command java followed by the class name, as expected output Hello World is displayed now.

```
java name
```
***Note:*** Java is case sensitive Programming language. All code, commands, and file names should is used in consistent casing. **Name** is not same as **name**
