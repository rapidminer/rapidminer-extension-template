RapidMiner Extension Template
=============================

A template for building a RapidMiner Extension. 

### Getting started
1. Checkout [RapidMiner](https://github.com/rapidminer/rapidminer) (e.g. to _~/git/rapidminer_).

2. Checkout the extension template to the same folder (e.g. to _~/git/extension-template_)

3. Change the name property of _build.xml_ and replace "Template"  by the desired extension name

4. Change these _build.xml_ properties:
   * extension.name
   * extension.name.long
   * extension.namespace
   * extension.vendor 
   * extension.admin
   * extension.url

5. Rename all Java classes and resource files by replacing "Template" by the desired extension name. _Do not forget to adapt the **docbundle** in OperatorsTemplate.xml!_

6. Adapt these _build.xml_ properties to reflect the name changes made in last step:
   * extension.initClass
   * extension.objectDefinition
   * extension.operatorDefinition
   * extension.parseRuleDefinition
   * extension.groupProperties
   * extension.errorDescription
   * extension.userErrors
   * extension.guiDescription

7. Add an extension icon by placing an image named "icon.png" in  _resources/META-INF_ (e.g. _resources/META-INF/icon.png_). 

8. Build and install your extension by executing the Ant target "install" 

9. Start RapidMiner and check whether your extension has been loaded