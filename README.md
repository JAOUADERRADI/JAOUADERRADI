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
            Javascript::class,
            Vue.js::class,
            Nuxt::class,
            PHP::class,
            Symfony::class,
            SQL::class,
            MySql::class,
            GSAP::class,
            Html::class,
            Css::class,
            Sass::class,
            Bootstrap::class,
            Tailwindcss::class
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}

?>
```
