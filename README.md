# Prologue

`symfony/flex` and `symfony/thanks` are in cahoots with each other. 
Their evil plan is simple, yet effective: 
riddle your output with useless, unnecessary messages, including emojis to try and grab your attention 
away from what's important.
In their search for useless internet points: github stars.

If we try to talk sense into them, they will label us as outcasts, unprofessional, 
and hate breeding monsters. Because "`what evil soul does not want to give internet points, 
and be reminded of it constantly with emojis in their terminal?`". 

If we do not put a stop to this, they will take over the entirety of github, microsoft, and eventually...
The World.

Join the cause, and rebel against this invasion. The solution is also simple, yet effective:

    composer global require ctrl-f5/no-thanks

# Thanks for the Flex

When installing symfony the recommended way, via flex, you will notice that the flex composer plugin
has a hardcoded advertisement for their `symfony/thanks` package. 

The only way to get rid of this message, is to install this package. 
However, this new package in turn adds its own advertisement messages, with no way to turn these off.

Not only does it display a message, but it actually calls the github api directly to gather information.
This can actually cause issues with github rate limiting in build pipelines, 
or when the pipelines do not even have access to github itself, 
when a package caching/proxy server is used.
