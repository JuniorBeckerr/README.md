```php
<?php

namespace ArnaldoBecker;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Join Ads Network',
                'position' => 'Backend Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Python::class,
            NodeJs::class,            
            Rust::class,
            DigitalOcean::class,
            Docker::class,
        ];
    }
}
```
