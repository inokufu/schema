# LEARNING OBJECT

### IRI
[http://schema.inokufu.com/learning-object](http://schema.inokufu.com/learning-object)

### DESCRIPTION
Learning objects (LO) are defined as any entity, digital or non-digital, that may be used for learning, education or training (see [here](https://en.wikipedia.org/wiki/Learning_object_metadata)). It could be any object that help learner achieve one or more learning goals.

Here are the concepts we use to describes a learning object:
- [bloom](http://schema.inokufu.com/learning-object/bloom)
- [type](http://schema.inokufu.com/learning-object/type)
- [author](http://schema.inokufu.com/learning-object/author)
- [description](http://schema.inokufu.com/learning-object/description)
- [lang](http://schema.inokufu.com/learning-object/lang)
- [picture](http://schema.inokufu.com/learning-object/picture)
- [provider](http://schema.inokufu.com/learning-object/provider)
- [publisher](http://schema.inokufu.com/learning-object/publisher)
- [title](http://schema.inokufu.com/learning-object/title)
- [URL](http://schema.inokufu.com/learning-object/url)

### SIMILAR
[https://schema.org/LearningResource](https://schema.org/LearningResource)

### BROADER
None provided

### JSON-LD
```json
{
  "@context": "http://schema.inokufu.com",
  "@type": "learning-object"
}
```

### NOTES
- A learning object MUST have an active URL. If the learning object is a non-digital (physical) activity or resource, its URL must be the URL describing it (curricula page for example).
- Learning object MAY be made of several other learning objects.
