```php
<?php

namespace DamiaenToussaint;

class About extends Me
{
    /**
     * @todo Update skills when we get more.
     * @return array
     */
    public function getPersonalData(): array
    {
        return [
            'data' => [
                'name' => 'Damiaen Toussaint',
                'education' => 'HBO ICT Software Engineering, NHLStenden University',
                'occupation' => 'App and Web developer at NoardCode',
                'linkedin' => 'www.linkedin.com/in/damiaen-toussaint',
                'personal_site' => 'www.damiaentoussaint.nl',
                'skills' => [
                    'app' => 'Creating Android and iOS apps with the Ionic Framework',
                    'web' => 'Back-end development with the Laravel Framework'
                ]
            ]
        ];
    }
}

?>
```
