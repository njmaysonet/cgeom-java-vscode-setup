# Setting up Java for VS Code

You will need a JDK of your choice downloaded and installed on your computer.

You can also follow the excellent guide by [VS Code](https://code.visualstudio.com/docs/java/java-tutorial). (I highly recommend reading this first and following these simplified instructions if confused)

# Install Extensions

Download the official Microsoft extensions or click on the [Install the Coding Pack for Java Link (Windows)](https://aka.ms/vscode-java-installer-win) for full Java support in VS Code. You'll need **Project Manager for Java** in order to manage your Java projects and create packages.

![image](https://github.com/njmaysonet/cgeom-java-vscode-setup/assets/13139001/c70169bf-a0c1-4ea1-bcd9-71a312ab6b80)

# Creating a New Project

Once your environment is set up, you can use `Ctrl+Shift+P` and type `Java` to search for the command to create a new Java project. Once you've named the project and set its location, VS Code will create the structure automatically. It should look like this in your `Explorer` tab:

![image](https://github.com/njmaysonet/cgeom-java-vscode-setup/assets/13139001/578180a5-acb8-4525-a3b8-9380df8ab734)

Clicking the `+` button on your `/src` folder should bring up these options:

![image](https://github.com/njmaysonet/cgeom-java-vscode-setup/assets/13139001/b76744e0-e2ea-428f-afc9-cc33921f539c)

Click on the package option to add and name a new package. You can then click on the `+` button that appears next to your new package to add classes into that package. You can also copy your classes into that package via folder structure, just be sure declare 

```Java 
package YourPackage;
``` 

in the class file.

Your project structure should end up looking similar to this:

![image](https://github.com/njmaysonet/cgeom-java-vscode-setup/assets/13139001/99c42e5f-42ba-4a6c-8fa1-b7dc14c896ef)

Once you create a package named GeomLibrary, you can reference all its classes by typing:

```Java
import GeomLibrary.*;
```
