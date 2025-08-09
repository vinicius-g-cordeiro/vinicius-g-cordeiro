## Meu nome é Vinícius Gonçalves Cordeiro e bem vindo ao meu mundo! ## 


[<img src="file.png" width="256" height="256"> ](https://github.com/vinicius-g-cordeiro)

### Apaixonado por programação desde 2014 (11 anos e alguns meses de programação 😝) ### 
```php
<?php
/**
 * Class to represent a person, which is me :´) 
 * @author Vinícius Gonçalves Cordeiro <vinicius-g-cordeiro>
 * @version 0.0.1
 * @since 2013 
 * @link https://github.com/vinicius-g-cordeiro
 */
namespace App;

class Pessoa {
    /** @var string - The name of this person */
    private string $nome;
    /** @var int - The age of this person */
    private int $idade;
    /** @var string - The email of this person */
    private string $email;
    /** @var string - The whatsapp of this person */
    private string $whatsapp;
    /** @var array - The favorite languages of this person */
    private array $favoriteLanguages;
    /** @var string - The favorite food of this person */
    private string $favoriteFood;
    /** @var array - The favorite games of this person */
    private array $favoriteGames;


    /**
     * Constructor of this person class, here we initialiaze all properties to be able 
     * to access it later 
     * @return void
     */
    public function __construct(string $nome, int $idade, string $email, string $whatsapp, array $favoriteLanguages, string $favoriteFood, array $favoriteGames) {
        $this->nome = $nome;
        $this->idade = $idade;
        $this->email = $email;
        $this->whatsapp = $whatsapp;
        $this->favoriteLanguages = $favoriteLanguages;
        $this->favoriteFood = $favoriteFood;
        $this->favoriteGames = $favoriteGames;
    }

    /**
     * @return Pessoa - The person itself 
     */
    public function getPessoa() : Pessoa {
        return $this;
    }

    /**
     * @return string - The name of this person 
     */
    public function getNome() : string {
        return $this->nome;
    }

    /**
     * @return int - The age of this person 
     */
    public function getIdade() : int {
        return $this->idade;
    }

    /**
     * @return string - The email of this person 
     */
    public function getEmail() : string {
        return $this->email;
    }

    /**
     * @return string - The whatsapp of this person 
     */
    public function getWhatsapp() : string {
        return $this->whatsapp;
    }

    /**
     * @return array - The favorite languages of this person 
     */
    public function getFavoriteLanguages() : array {
        return $this->favoriteLanguages;
    }

    /**
     * @return string - The favorite food of this person 
     */
    public function getFavoriteFood() : string {
        return $this->favoriteFood;
    }

    /**
     * @return array - All properties of this person class 
     */
    public function getAllProperties() : array {
        return get_object_vars($this);
    }
}
<?php
/**
 * Somewhere in other class... 
 */

namespace App;

// Import the person class so we can use it and store on a super secret database :D
use App\Pessoa;

$pessoa = new Pessoa(
    'Vinícius Gonçalves Cordeiro',
    26,
    'vinicordeirogo@gmail.com',
    '+55 61 * ****-****',
    ['PHP', 'C++', 'Javascript', 'Phyton'],
    'Lasagna',
    [
        'Grand Theft Auto: San Andreas', 'Grand Theft Auto IV', 'Fallout New Vegas',
        'Stalker', 'Counter Strike: Global Offensive', 'Skyrim', 'Dark Souls I',
        'Mafia I, II, III', 'Resident Evil 2 : Remake', 'Resident Evil 4 : Remake' 
    ];

)

```

### Contact Info ###

| Link | Description |
| --- | --- |
| https://github.com/vinicius-g-cordeiro | GitHub |
| https://instagram.com/vinicordeirox | Instagram |
| https://www.linkedin.com/in/vinicordeirox/ | LinkedIn |

<i style="font-size: 12px;">&copy; Copyright, All rights reserved  (2025 Vinícius Gonçalves Cordeiro)</i>


