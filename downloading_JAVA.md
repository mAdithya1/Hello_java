# Download Java for Windows 10

Download the latest Java Development Kit installation file for Windows 10 to have the latest features and bug fixes.

1. Using your preferred web browser, navigate to the [Oracle Java Downloads page](https://www.oracle.com/java/technologies/downloads/#jdk17-windows)
1. On the Downloads page, click the x64 Installer download link under the Windows category  

## Install Java on Windows 10  

After downloading the installation file, proceed with installing Java on your Windows system.  
Follow the steps below:  
**Step 1: Run the Downloaded File**  
Double-click the downloaded file to start the installation.  
**Step 2: Configure the Installation Wizard**   
After running the installation file, the installation wizard welcome screen appears.

1. Click Next to proceed to the *next* step.  
![image](https://user-images.githubusercontent.com/104252631/172865139-f38c6da0-6303-4296-bcd8-4c8726ad3415.png)
2. Choose the destination folder for the Java installation files or stick to the default path. Click *Next* to proceed.
 ![image](https://user-images.githubusercontent.com/104252631/172865563-8ca5ef1a-2d58-4970-8564-53ae53c967da.png)
3. Wait for the wizard to finish the installation process until the Successfully Installed message appears. Click Close to exit the wizard.
![image](https://user-images.githubusercontent.com/104252631/172866060-36e63762-5898-4236-8057-f3b35a6dbb48.png)

## Set Environmental Variables in Java
Set Java [environment variables](https://phoenixnap.com/kb/windows-set-environment-variable) to enable program compiling from any directory. To do so, follow the steps below:

**Step 1: Add Java to System Variables**
1. Open the Start menu and search for environment variables.

2. Select the Edit the system environment variables result.

![image](https://user-images.githubusercontent.com/104252631/172866464-3444353a-1bfd-424e-8829-cbd5c3248393.png)

3. In the System Properties window, under the Advanced tab, click Environment Variables…

![image](https://user-images.githubusercontent.com/104252631/172866571-ec62c483-0a6f-4b56-b8d5-686598af7132.png)

4. Under the System variables category, select the Path variable and click Edit:

![image](https://user-images.githubusercontent.com/104252631/172866684-60713997-b878-4ce3-a34a-4ebf6bbece3d.png)

5. Click the New button and enter the path to the Java bin directory:

![image](https://user-images.githubusercontent.com/104252631/172866833-5da19c87-662b-4fd8-9a7b-892ceba5a0ef.png)

6. Click OK to save the changes and exit the variable editing window.

**Step 2: Add JAVA_HOME Variable**
Some applications require the JAVA_HOME variable. Follow the steps below to create the variable:

1. In the Environment Variables window, under the System variables category, click the New… button to create a new variable.

![image](https://user-images.githubusercontent.com/104252631/172867343-c7e00ff5-fd81-454a-9b92-98bcb1814cb9.png)

2. Name the variable as JAVA_HOME.

3. In the variable value field, paste the path to your Java jdk directory and click OK.

![image](https://user-images.githubusercontent.com/104252631/172867499-5e61c21c-47c2-4f15-b3e0-7636f1e01579.png)

5. Confirm the changes by clicking OK in the Environment Variables and System properties windows.

## Test the Java Installation

Run the `java -version` command in the command prompt to make sure Java installed correctly:

![image](https://user-images.githubusercontent.com/104252631/172867761-4bba9b89-f2ba-4e91-9929-7719dbc1bf14.png)

If installed correctly, the command outputs the Java version. Make sure everything works by writing a simple program and compiling it. Follow the steps below:

**Step 1: Write a Test Java Script**
1. Open a text editor such as Notepad++ and create a new file.

2. Enter the following lines of code and click *Save*:

```java
Class HelloWorld{
  public static void main(String[] args){
    system.out.println("Hello World!")
  }
}
```
![image](https://user-images.githubusercontent.com/104252631/172868372-a370394a-20db-4241-a0e6-54bd4edb7dcd.png)

3. Name the file and save it as a Java source file (*.java).  
![image](https://user-images.githubusercontent.com/104252631/172868465-e424192e-e440-4dc0-8a82-961200e6fe6c.png)

`
Note: When using Notepad, select All files for the Save as type option and add the .java extension to the file name.
`
