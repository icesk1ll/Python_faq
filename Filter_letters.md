Find letters in garbage like STRINGS.EXE

text =  our document
```python
import string

filter(lambda x: x in string.letters, text)
```
