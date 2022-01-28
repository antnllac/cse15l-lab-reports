# Lab Report 2 - Week 4
Over the past two weeks, as we worked on labs 3 and 4 we encountered several bugs, which turned into several solutions in  order to create a running program. In Lab Report 2, we will go over 3 different code changes we did in order to fix a bug.

# Bug 1
Code Change:
<br/><br/>
Link to test file:
<br/><br/>
Symptom of Failure Inducing Input:
```
antonella_crawley@Antonellas-MacBook-Air-2 markdown-parse % java MarkdownParse Testing.md
Exception in thread "main" java.lang.StringIndexOutOfBoundsException: String index out of range: -2
        at java.base/java.lang.StringLatin1.charAt(StringLatin1.java:48)
        at java.base/java.lang.String.charAt(String.java:1512)
        at MarkdownParse.getLinks(MarkdownParse.java:22)
        at MarkdownParse.main(MarkdownParse.java:35)

```
2-3 sentences regarding code.

# Bug 2
Code Change:
<br/><br/>
Link to test file:
<br/><br/>
Symptom of Failure Inducing Input:
```
antonella_crawley@Antonellas-MacBook-Air-2 markdown-parse % javac MarkdownParse.java     
antonella_crawley@Antonellas-MacBook-Air-2 markdown-parse % java MarkdownParse Testing3.md
[]
```
2-3 sentences regarding code.

# Bug 3
Code Change:
<br/><br/>
Link to test file:
<br/><br/>
Symptom of Failure Inducing Input:
```
antonella_crawley@Antonellas-MacBook-Air-2 markdown-parse % javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar MarkdownParseTest.java
MarkdownParseTest.java:22: error: cannot find symbol
        ArrayList<String> links = MarkdownParse.getLinks(contents);
                                                         ^
  symbol:   variable contents
  location: class MarkdownParseTest
1 error

```
2-3 sentences regarding code.