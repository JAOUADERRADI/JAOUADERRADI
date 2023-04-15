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
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Html::class,
            Css::class,
            Sass::class,
            Javascript::class,
            Php::class,
            Bootstrap::class,
            TailwindCss::class
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
