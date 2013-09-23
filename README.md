glowing-llama
=============

a blink(1) simple notification system

How?
====

+ Uses cron to invoke a small python script
+ Script traverses executable files in a rules.d/ directory
+ When a script returns non-zero or non-empty string - sets the blink(1) to the value returned
+ Scripts are ordered, so you can set priority.
+ When a script triggers a blink write, execution finishes.

Why?
====

Blink(1) is a cool tool for system monitoring

TODO
====

+ Daemonize the system to make it behave better.
+ Tidy up the code.
+ Introduce method for patterns rather than solid colours.

Probably do those in reverse order.

Name was a random generated github name, but it kinda fitted.
