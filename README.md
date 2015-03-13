RapidMiner Extension Template
=============================

A template project for creating a RapidMiner Studio extension. 

### Prerequisite
* Requires Gradle 2.3+ (get it [here](http://gradle.org/installation))

### Getting started
1. Checkout the extension template

2. Change the extension configuration in _build.gradle_ (e.g. replace 'Template' by the desired extension name)

3. Rename all Java classes and resource file names by replacing 'Template' by the desired extension name.
 _Do not forget to adapt the **docbundle** attribute in the **operators** element of OperatorsTemplate.xml!_

4. Add an extension icon by placing an image named "icon.png" in  _src/main/resources/META-INF/_. 

5. Build and install your extension by executing the _installExtension_ Gradle task 

6. Start RapidMiner Studio and check whether your extension has been loaded
