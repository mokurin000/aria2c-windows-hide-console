# What is this?

On windows, when spawning a console program, by default would create a console window, which will cause bad UX.

Instead of `WSCript.Shell` things, we could simply set `SUBSYSTEM` of the cli program to `WINDOWS`

This action would fetch aria2 updates weekly, patch SUBSYSTEM, then upload to releases.
