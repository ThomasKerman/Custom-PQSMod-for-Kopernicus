This is an example for adding custom PQSMods to the Kopernicus Mod-Loader.

What you have to do:

* Create a new C#-Project and add the KSP libraries and Kopernicus as a reference
* Create a new class and write your own PQSMod/-s
* Create another class with the name of the future config node. If you want a node called **VertexOblate { }**, the name of your class has to be **VertexOblate**. This class will be used as wrapper.
* Write the Loader for the class. (For references, look at the namespace Kopernicus.Configuration.ModLoader)
* Put the wrapper class into the namespace Kopernicus.Configuration.ModLoader
* Open Properties/AssemblyInfo.cs and add the following: `[assembly: KSPAssemblyDependency("Kopernicus", 0, 0)]`
* Compile and put the .dll somewhere in GameData/
* Enjoy!

P.S. If you don't understand a part of this guide, just write me a PN (Forum name: Thomas P.) or ask per mail. :)
P.P.S Oh, and: Credit for the example PQSMod goes to Kragrathea ;)