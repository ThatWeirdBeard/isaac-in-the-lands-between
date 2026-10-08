# Source placeholder

The executable hook layer cannot be generated or validated safely without the target
Elden Ring build, its loaded module layout, and the installed Isaac data to inspect.
Do not guess retail offsets or ship untested hooks.

Next implementation steps in a real modding environment:
1. Recon exact Elden Ring version and loader.
2. Recon exact Isaac version and required data files.
3. Implement a minimal host hook that proves a custom projectile can be spawned.
4. Add local Isaac data reader/converter.
5. Implement LoadoutState and one item modifier.
6. Add familiar tick/effect.
7. Build opening room and pickup flow.
8. Add boss-slice test and evidence capture.
