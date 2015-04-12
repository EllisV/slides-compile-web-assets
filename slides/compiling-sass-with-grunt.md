## Compiling SASS with Grunt

```javascript
// file: Gruntfile.js
// ...
grunt.initConfig({
  // ...
  compass: {
    options: {
      sassDir: '<%= config.in %>/style',
      cssDir: '<%= config.out %>/css'
    },
    dev: { options: { sourcemap: true } },
    prod: { options: { environment: 'production' } }
  },
  // ...

  grunt.loadNpmTasks('grunt-contrib-compass');

  grunt.registerTask('build', [
    // ...
    'compass:prod'
    // ...
  ]);
}),
// ...
```
