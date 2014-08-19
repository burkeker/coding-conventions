Coding conventions for Java
===========================

###Java with Eclipse IDE###
####Setting up Eclipse with Maven####
Your maven project needs to include the following maven-eclipse-plugin configuration to make use of the gbif coding style:

To setup eclispse, execute

    mvn eclipse:eclipse

in the root of your project.


####Code Formatting Style####
To manually setup the coding style without maven do:

    Window > Preferences > Java > Code Style > Formatter > Import

Then select the downloaded `java-style-config.xml` file.

####Import Organization####
For Eclipse import organization go to

    Window > Preferences > Java > Code Style > Organize Imports > Import

Then select the downloaded `java-style.importorder` file.

####Member Sort Order####
For Eclipse member sort order go to:

    Window > Preferences > Java > Appearance > Members Sort Order and match the following screenshot:

####Save Actions####
Finally, to automate all of this each time you save, configure your Eclipse in

    Window > Preferences > Java > Editor > Save Actions

Then match the following screenshot:

###IntelliJ IDEA###
Download [settings.jar]() and select

    File -> Import Settings