# xed (WORK IN PROGRESS)

*xed* is an XML stream editor for the command line

## Example (before a real documentation)

Input *foo.xml* file

```xml
<foo>
  <bar answer="41" />
</foo>
```

We want to change the answer to *42*

```bash
cat foo.xml | xed --selector="foo > bar" --attr answer 42 > foo.xml
```
