# Tesseracting

**Play it:** https://erenciracioglu-dotcom.github.io/Tesseracting/

A small toy for feeling your way around four dimensions. A ball bounces weightless inside a tesseract that turns in a plane (in 4D things turn around a plane, not an axis). You watch it two ways at once: from outside, as the tesseract's 3D shadow, and through the ball's own eyes, which only ever see a 3D slice of the 4D world.

It opens as a plain turning tesseract. The switches underneath add one idea at a time.

Best on a desktop browser with a mouse; touch works too.

## Controls

- Drag either view to look around. Shift-drag (or right-drag) turns your view into the fourth direction.
- Space kicks the ball. P pauses; you can still look around while paused.
- Free fly: W A S D to fly, R and F for up and down, E and Q to slide ana and kata (the two ways along the fourth direction). Shift flies faster.
- Keys 1 to 7 switch the layers.

## The switches

- **Shape**: a tesseract, or hexagon × hexagon, whose spinning shadow is the classic ball-in-a-spinning-hexagon test.
- **Turns in**: the plane or planes it turns in. Turning in one plane leaves the plane at right angles to it perfectly still.
- **Eyes**: free look, along the ball's path, riding with the walls, or free fly.
- **Outside view follows eyes**: the outside view turns exactly as your eyes do, including turns into the fourth direction.
- **Time**: pause, slow motion, or slow down at every bounce.
- **Flat shadows**: the shape's shadows on two flat planes. Turning in xw, one spins like the hexagon test and the other stands still.
- **Ball's room**: the 3D slice the ball sees, drawn inside the tesseract.
- **Wall markers**: where every wall is, including walls hidden in the fourth direction.
- **Ana/kata sight**: faint ghosts of what lies just outside the ball's slice.
- **Wall hum**: each wall hums louder as it gets close, muffled when it is hidden in the fourth direction.
- **View cone**: the ball's field of view, painted onto the walls it sees.
- **Chairs**: a chair in every cell, for a sense of up, front and handedness.

## How it works

Everything runs in the browser from a single HTML file with three.js. The ball's view is ray-cast in 4D in a fragment shader; the outside view is a perspective projection from 4D to 3D. The ball reflects off the moving walls exactly, so turning in xw alone leaves its yz motion completely untouched.

## Credits

Made by Faruk Eren Ciracioglu with Claude Opus 5.5.
Contact: erenciracioglu@gmail.com

## License

MIT. See [LICENSE](LICENSE).
