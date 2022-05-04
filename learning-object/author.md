# AUTHOR

### IRI
[http://schema.inokufu.com/learning-object/author](http://schema.inokufu.com/learning-object/author)

### DESCRIPTION
This is a person (or list) who contributed to make/write the learning object.

### SIMILAR
[https://schema.org/author](https://schema.org/author)

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
- The author MUST be the physicial person who contributed to make the learning object.
- The author MUST NOT be mistaken with the provider which is the organization hosting the learning object. 
- The author MUST NOT be mistaken with the publisher which is the organization that produced/funded the learning object.

So for example if we have a MOOC from Coursera with professor X from Stanford, then we would have:
- provider is coursera
- publisher is stanford
- author is professor X

On the other hand, if the learning object is an article hosted on stanford website by professor Y, then we would have
- provider is stanford
- publisher is stanford
- author is professor Y
