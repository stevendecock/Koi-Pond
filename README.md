# Koi-Fish with javascript

Fork of https://github.com/kaizhelam/Koi-Fish.

Following changes were made:
- Isolate javascript code using an IIFE (so as to not put any variables on global scope).
- Ability to use an existing HTML canvas to render the Koi Pond using window.KoiPond.initKoiPond(canvas, populations)
- Ability to initialize the pond with multiple fish popuplations (different numbers and colors)
- Adding 'depth' to Koi class.  Depth affects the fish size (fish that swim deeper are smaller and darker)
- Rendering fish according to their depth: deeper fish swim below fish that swim on top. 
