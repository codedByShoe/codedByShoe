```php
<?php

namespace Andrew Shoemaker;

class About extends Me
{
    public function getFeaturedProjects(Request $request): array
    {
        return [
          'LaravelStorefront' => $request->LaravelLivewire,
          'Twitter-clone' => $request->VueInertiaLaravel,
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Livewire::class,
            Vuejs::class,
            Nuxt::class,
            TailwindCss::class,
            Bootstrap::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source & find my place at an amazing company.';
    }
}
```

