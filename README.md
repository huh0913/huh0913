- 👋 Hi, I’m @huh0913
- 👀 I’m interested in Frontend Development
- 🌱 I’m currently learning in IT PARK
- 📫 How to reach me: Telegram @pOuOd, Instagramm dava674
- 😄 Pronouns: ...
- ⚡ Fun fact: I'm beginner in the field of programming, and I'm also learning other interesting things

<!---
huh0913/huh0913 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<?php

namespace AshKellerman;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
