# PROVIDER

### IRI
[http://schema.inokufu.com/learning-object/provider](http://schema.inokufu.com/learning-object/provider)

### DESCRIPTION
This is the provider (host) of the Learning object such as youtube, coursera, applebooks, etc.
You can create any provider you want or select the major providers.

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
- The provider MUST be the host of the learning object. 
- The provider MUST NOT be mistaken with the publisher which is the organization that produced/funded the learning object. 
- The provider MUST NOT be mistaken with the author who is the physicial person who contributed to make the learning object.

So for example if we have a MOOC from Coursera with professor X from Stanford, then we would have:
- provider is coursera
- publisher is stanford
- author is professor X

On the other hand, if the learning object is an article hosted on stanford website by professor Y, then we would have
- provider is stanford
- publisher is stanford
- author is professor Y
