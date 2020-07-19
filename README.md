# JLemmagen Lucene

JLemmaGen Lucene is basic lucene filter to support [JLemmaGen](jlemmagen) lemmatizer.

JLemmaGen is java implmentation of [LemmaGen][lemmagen] project.

[LemmaGen][lemmagen] project aims at providing standardized open source multilingual platform for lemmatisation.

### Making release

```bash
mvn clean release:prepare release:perform -Darguments='-Dmaven.javadoc.failOnError=false'
git push --follow-tags
```

### License

All source code is licensed under Apache License 2.0.

[lemmagen]: http://lemmatise.ijs.si/Software/Version3
[jlemmagen]: https://github.com/hlavki/jlemmagen
