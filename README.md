# Network Feminisms & Convivial Technologies

An interactive single-page art piece — a technofeminist ecosystem of bio-mechanical
organisms. Hovering a bug rewrites the prompt line; clicking one fires its glitch
animation and ripples the disturbance outward through the network.

## Run it

No build step, no dependencies. Just open `index.html` in a browser, or serve the
folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

The bug animations are `.webm` clips; browsers only autoplay them after a user
interaction, so a fresh load shows the still bugs floating and the clips play on click.

## Structure

```
index.html        # everything: markup, CSS, JS
assets/
  bug1..5.png      # resting pose for each organism
  bugN01..N05.webm # 5 glitch animation variants per organism
```

Bug positions and sizes live in the `BUGS` array near the top of the script.

## Credits

Concept & spec: [friend's name]. Built with HTML/CSS/JS.
