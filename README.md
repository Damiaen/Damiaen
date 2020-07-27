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
            'personal' => [
                'name' => 'Damiaen Toussaint',
                'current_education' => 'HBO ICT Software Engineering, NHLStenden University',
                'current_occupation' => 'App and Web developer at NoardCode',
                'linkedin' => 'www.linkedin.com/in/damiaen-toussaint',
                'personal_site' => 'www.damiaentoussaint.nl'
            ]
        ];
    }
    
    /**
     * @todo Try to get some more skills
     * @return array
     */
    public function getSkills(): array
    {
        return [
            'skills' => [
                'app_development' => 'Creating Android and IOS apps with the Ionic Framework',
                'web_development' => 'Back-end development with the Laravel Framework'
            ]
        ];
    }
}

?>
```
