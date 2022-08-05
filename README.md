```php
<?php

namespace DamiaenToussaint;

class About extends Me
{
    /**
     * @return array
     */
    public function getPersonalData(): array
    {
        return [
            'data' => [
                'name' => 'Damiaen Toussaint',
                'education' => 'Bachelor\'s degree in Software engineering',
                'occupation' => 'Softwaredeveloper at NoardCode',
                'linkedin' => 'www.linkedin.com/in/damiaen-toussaint',
                'personal_site' => 'www.damiaen.nl',
                'skills' => [
                    'app' => 'Developing Android and iOS apps with Ionic',
                    'web' => 'Developing back-end applications with Laravel'
                ]
            ]
        ];
    }
}

?>
```
