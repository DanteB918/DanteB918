```php
<?php

namespace DanteBradshaw;

class About extends Me
{
    public function getHobbies(): array
    {
        return [
            'hobbies' => [
                'Chess' => 'in my free time',
                'Gaming' => 'pretty rarely',
                'Coding' => 'All the time.'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        //I may have missed some stuff but here's the gist:
        return [ 
            Php::class,
            Python::class,
            Javascript::class,
            Laravel::class,
            Reactjs::class,
            Scss::class,
            Less::class,
            Docker::class,
            Bash::class,
            Ansible::class,
            Aws::class,
        ];
    }
}
```
