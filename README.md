angular-location-hash-bug
=========================

## [Demo](http://bschoenfeld.github.io/angular-location-hash-bug/#/foo#bar)

### Most browsers &#10003;

URL: `/#/foo#bar`

Content:

```
Path: foo
Hash: bar
```

### Mercury on iOS &#10003;

URL: `/#/foo%23bar`

Content:

```
Path: foo
Hash: bar
```

### Chrome on iOS &#10007;

URL: `/#/foo%23bar`

Content:

```
Path: foo#bar
Hash:
```
