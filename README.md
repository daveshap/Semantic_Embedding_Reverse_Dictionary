# Semantic Embedding Reverse Dictionary

A reverse dictionary/thesaurus empowered by vector search. Thesaurus find words by virtue of similarity but these are often only "close" if you are already familiar with the domain. 

Instead, there are also "reverse dictionaries" where you look up by searching the definition first, which then matches to the word, but until semantic search, this was not the best. 

In one example, I saw a video of Jeff Goldblum a while back where he explained that his "verbal affectation" was not stuttering, but a behavior called "fumfer". If you look up this word, most dictionaries do not even have it. You can see the reference here, at this exact timestamp: https://www.youtube.com/watch?v=_l4xtcmrT6g&t=21s

However, Wiktionary does have this word! https://en.wiktionary.org/wiki/fumfer 

It's also got such fun words as vituperative: https://en.wiktionary.org/wiki/vituperative 

PowerThesaurus does have fumfer... technically. But based on the synonyms it seems like it is not correctly defined: https://www.powerthesaurus.org/fumfer/synonyms 

Even the Open Source WordWeb tool did not have it. Heck, I even tried asking GPT-4 but it didn't know until I told it the word directly. Then it magically knew it. So there's something semantically missing here, and there are even limitations in GPT technology.

So let's see if we can use GPT as a perfect reverse dictionary/thesaurus

## Sources

Page: https://dumps.wikimedia.org/enwiktionary/20231020/
File: enwiktionary-20231020-pages-articles-multistream.xml.bz2