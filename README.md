# MethodScript support
This repository contains several components that together form an [Eclipse IDE](https://www.eclipse.org/ide/) plugin for the [MethodScript](https://methodscript.com/) programming language. These components are:
 - [MethodScript syntax definition](MethodScript/syntax) (SDF3)
 - [Editor support](MethodScript/editor) (ESV)
 - [Transformations (Desugaring, outline generation and more)](MethodScript/trans) (Stratego)
 - [Static analysis: Name resolution and type checking](MethodScript/trans/analysis) (NaBL2)
 - [Static analysis: Control flow definition and data flow analysis](MethodScript/trans/analysis/flow) (FlowSpec)
 - Eclipse IDE plugin generation modules: [MethodScript.eclipse](MethodScript.eclipse), [MethodScript.eclipse.feature](MethodScript.eclipse.feature) and [MethodScript.eclipse.site](MethodScript.eclipse.site)  
 Building [MethodScript](MethodScript) followed by these modules in this order results in an Eclipse site jar that can be installed in the Eclipse IDE.
 - [Example module](MethodScript.examples)  
 Used to put MethodScript `.ms` and `.msa` files in for manual tests during development.
 - [Test module](MethodScript.test)  
 Container for semi-automated implementation tests.
