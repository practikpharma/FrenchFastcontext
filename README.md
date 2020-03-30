# FrenchFastContext

This project is an extension of the FastContext project [https://github.com/jianlins/FastContext](), created in 2019 for the extension of the FastContext algorithm [1] to French.

### Description
This repository doesn't fork any code from FastContext, but provides the versioned list of rules in the FastContext format generated for the French language, as well as detailed instructions to use FastContext with our French adaptation. 

The list of French lexical is generated by a semi-automatic process, which is documented comprehensively on a dedicated repository: https://github.com/practikpharma/FrenchFastContext-CuesGeneration

### Authors 
Andon Tchechmedjiev (@twktheainur) with supervision of Clement Jonquet (@jonquet)

### Copyright
LIRMM

[1] [https://dx.doi.org/10.1016%2Fj.jbi.2018.08.002]()

## French Lexical Cues 


## Using the French lexical cues with FastContext
For ease of use, we provide a sample maven application that integrates the French lexical cues with FastContext and that includes a few commented usage examples. The project is structured as follows: 
 
 - src/main/
   - java/
     - fr.lirmm.frenchfastcontext.FrenchContextApp
   - resources/
     - french_cues.tsv
 



