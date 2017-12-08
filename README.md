# Coding Standards
### coding-standards
### https://github.com/yasskin/coding-standards/

* .Net
* C#
* JavaScript
* jQuery
* SQL

### Naming conventions for the code base.
 
# .NET

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

# C#

#### Common C# Naming Conventions
* https://en.wikibooks.org/wiki/C_Sharp_Programming/Naming

# Naming Conventions in C language family
* Camel Case: firstName
* Pascal Case: FirstName 
* Hungarian Notation: strFirstName (not used in C#)

#### Characters

use single quotes for characters
```
char characterA = 'A';
```
#### Comments
for multiline comments, use // two-slashes rather than /* */
```
/*
Here is a multi-line comment
That runs to two lines
*/
```

more common today in C#
```
// Here is a multi-line comment
// That runs to two lines
```
* Use Comments to explain the whys, hows, constraints, etc but not the whats (the code should explain the what)

#### Constants

* For local variables: Camel Case int numberOne;
* For constants use: Pascal Case int MaxZoom = 5;

#### Private Fields. Use _ to prefix and lower case for the first letter.

```
_easterEggs for private fields 
```

#### Properties. Use Upper CamelCase Capitalize the first letter of property names.
```
ViewBag.HighScore
```

##### Boolean properties. Use "Is" or "Has" when relevant.
```
public bool IsActive => !( IsNeutralized || HasScored );
```

#### Strings

use double quotes for strings
```
string firstName = 'Noah';
```

#### Variables

##### Local Variables. 
Use Lower CamelCase, lower the first letter of variables then upper case for additional words.  
```
var highScore
```

#### Verbatim Strings 
For URLs, use verbatium strings @ sympbol rather than double backslach

```
string path = "c:\\projects\\project1\\folder1";

string path = @"c:\projects\project1\folder1";
```


# JavaScript

```

```

# jQuery

```

```
# SQL

Keywords. Use ALL CAPS for SQL Keywords
```
SELECT
```
