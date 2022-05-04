# PUBLISHER

### IRI
[http://schema.inokufu.com/learning-object/publisher](http://schema.inokufu.com/learning-object/publisher)

### DESCRIPTION
This is the organization which published/produced/funded the learning object. Most of the time it will be an entity such as University, school, company, etc.

### SIMILAR
[https://schema.org/provider](https://schema.org/provider)

### BROADER
[http://schema.inokufu.com/learning-object](http://schema.inokufu.com/learning-object)

### JSON-LD
```json
{
  "@context": "http://schema.inokufu.com",
  "@type": "learning-object",
  "url": "https://www.coursera.org/learn/data-science-methodology",
  "title": "Data Science Methodology",
  "lang": "en",
  "type":"mooc",
  "provider":"coursera",
  "publisher":"ibm",
  "author":["Alex Aklson","Polong Lin"]
}
```

### NOTES
- The publisher MUST be the organization that produced/funded the learning object. 
- The publisher MUST NOT be mistaken with the provider which is the organization hosting the learning object. 
- The publisher MUST NOT be mistaken with the author who is the physicial person who contributed to make the learning object.

So for example if we have a MOOC from Coursera with professor X from Stanford, then we would have:
- provider is coursera
- publisher is stanford
- author is professor X

On the other hand, if the learning object is an article hosted on stanford website by professor Y, then we would have
- provider is stanford
- publisher is stanford
- author is professor Y
