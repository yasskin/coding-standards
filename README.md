# Coding Standards
### coding-standards
### https://github.com/yasskin/coding-standards/

### Naming conventions for the code base.
 
## .NET

Models.

* Model file names should be singular
```
Models/VideoGame.cs
```

To get the underlying value from a nullable type, 

A. you must use the Value property.

var player = _playerRepository.GetPlayer(id.Value);

B. use the cast type 

var player = _playerRepository.GetPlayer((int)id);

## C#

#### Common C# Naming Conventions
* https://en.wikibooks.org/wiki/C_Sharp_Programming/Naming

#### Private Fields. Use _ to prefix and lower case for the first letter.

```
_easterEggs for private fields 
```

Properties. User Upper CamelCase Capitalize the first letter of property names.
```
ViewBag.HighScore
```

Variables. Use Lower CamelCase, lower the first letter of variables then upper case for additional words.  
```
var highScore
```

## JavaScript

```

```

## jQuery

```

```
