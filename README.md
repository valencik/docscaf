Paper Scaffolding and Templating Markup
=============

A markup system for templating formal papers, essays, documentation.

Specify the necessary requirements of the work. (i.e. number of topics, arguments, supporting points, evidence, citations, etc)
From this specification a scheme is generated.
This scheme could then be applied to many other markup languages (namely LaTeX and Markdown) as calls to action in comments.

Metadata could be provided in the markup's comments to suggest topical dependencies and relationships. This could allow for UML style diagrams to be generated showing a logical overview of the written work. 

#Benefits
-  easier restructuring of the written work 
-  compartmentalizes thoughts enabling better collaboration
-  provide a measure of work completion

#Example Scheme Idea (unformatted)

```
essay
  introParagraph
    stateThesis
    introduceTopic1
    introduceTopic2
    concludeIntro

  topicParagraphs
    introduceTopic
    argument1
      supportArgument1
    argument2
      supportArgument2
    concludeTopic

  conclusionParagraph
    introConclusion
    summarizeTopic1
    summarizeTopic2
    restateThesis
```
