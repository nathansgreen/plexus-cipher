plexus-cipher
=============

Cipher component. Utilized by [Maven](http://maven.apache.org/)

Groovy console usage:

```groovy
def c = new org.sonatype.plexus.components.cipher.DefaultPlexusCipher()
c.decryptDecorated('{+HKpHDcLGIIHVDYFZLkp1oyMnlad7FvlXpqFyD7JvEA=}',
    c.decryptDecorated('{tPUZLgbir/MHdmh9B932/cT2YVlEySKkSfum/XTqz5M=}', 'settings.security'))
```
