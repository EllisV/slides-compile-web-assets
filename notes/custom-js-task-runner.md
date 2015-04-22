## Custom JS task runner

```javascript
#!/usr/bin/env node

var args = process.argv.slice(2);

args.forEach(function (value) {
  switch (value) {
    case 'compile':
      console.log('Compiling SASS');
      break;
    default:
      console.log('Command "' + value + '" not found')
  }
});
```
