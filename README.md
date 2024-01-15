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
                'position' => 'Front-end Developer'         
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
            Bootstrap::class
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}

?>
```
