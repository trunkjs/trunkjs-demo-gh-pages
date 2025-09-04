# leuffen-med
Website med.leuffen.de

Implementiere eine Funktion in PHP8, die aus einer beliebigen Klasse anhand der annotations entsprechende typescript types
erzeugt. Sollte ein Typ undefiniert sein, soll eine Exception geworfen werden.

Beispiel Eingabedaten:

```php
class UserGroup {
    public string $groupName;
}

class User {
    /**
     * @type string
    */  
    public string $name;
    
    /**
    * @var UserGroup[]
    */
    public $userGroups;
}
```
