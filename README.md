# intel-wifi-card-fix
Some laptops that use Intel wifi cards such as Thinkpad Yoga have a bug with their Intel Wifi card giving bad performance after waking up from sleep. This is a easy workaround that resets the wifi card which fixes the performance problem.

# Run the script wifi-fix.bat using task scheduler
1. Create a new task
2. Trigger task "on an event"
3. Basic > Log > System
5. Event ID 507
6. Set task to run at highest privileges
