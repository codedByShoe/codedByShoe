```php
<?php

namespace Andrew Shoemaker;

class About extends Me
{

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Go::class,
            Laravel::class,
            Livewire::class,
            Vuejs::class,
            Htmx::class,
            Nuxt::class,
            TailwindCss::class,
            Bootstrap::class
        ];
    }

    public function getFutureGoal(): array
    {
        return ['Become best HTMX CEO', 'Find the startup that I founded.'];
    }
}
```

