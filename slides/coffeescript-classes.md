## Coffeescript

```coffeescript
class Animal
  constructor: (name) ->
    @name = name

  getName: ->
    @name

dog = new Animal('Puffy')

console.log "My dogs name is #{dog.getName()}"
```

```javascript
(function() {
  var Animal, dog;

  Animal = (function() {
    function Animal(name) {
      this.name = name;
    }

    Animal.prototype.getName = function() {
      return this.name;
    };

    return Animal;

  })();

  dog = new Animal('Puffy');

  console.log("My dogs name is " + (dog.getName()));

}).call(this);
```
