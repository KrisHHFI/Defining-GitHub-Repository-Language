# Defining a GitHub Repository's Language

## Projects with code files

1. Create a file named **.gitattributes**
2. Inside the file paste the following: __*__  __linguist-language=Java__ 
   - This method makes GitHub recognise all the files as your stated language. In the example above, the whole repository would become "Java 100%".

### Examples
\* linguist-language=C <br />
\* linguist-language=HTML <br />
\* linguist-language=Java <br />
\* linguist-language=JavaScript <br />
\* linguist-language=Python <br />
\* linguist-language=RobotFramework 

## Projects without any code files

- Create an empty file with the desired language's file extension. For example, **Project-Language.html** will define the repository's language as HTML.
- GitHub only recognises certain languages, for example **Project-Language.madeuplanguage** does not work. <br />

### Examples

Repository-Language.c <br />
Repository-Language.html <br />
Repository-Language.java <br />
Repository-Language.js <br />
Repository-Language.py <br />
Repository-Language.robot <br />
