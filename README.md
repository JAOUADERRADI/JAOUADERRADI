```php
<?php

namespace JaouadErRadi;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'FreeLance',
                'position' => 'FULLSTACK Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            JAVASCRIPT::class,
            VUE::class,
            NUXT::class,
            PHP::class,
            SYMFONY::class,
            SQL::class,
            MYSQL::class,
            GSAP::class,
            HTML::class,
            CSS::class,
            SASS::class,
            TAILWINDCSS::class,
            BOOTSTRAP::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}

?>
```
