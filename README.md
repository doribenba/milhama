# Atlas

Atlas is a beta strategy simulation game about watching a fictional world order change in real time.

Choose a country, tune its strategic profile, and start a global conflict. From there, the core experience is to sit back and watch: countries compete, expand, lose territory, retaliate, and eventually leave one final power standing.

## What happens in a simulation

Each country begins with a profile made up of military strength, economy, resilience, technology, foreign support, and, for selected countries, nuclear weapons. These values combine into a relative power score that influences the outcome of conflicts.

The simulation favors nearby rivals, but it is not deterministic on purpose. Stronger countries have an advantage, not a guarantee. That uncertainty is part of the game: surprising upsets, unexpected empires, and dramatic reversals can emerge in every run.

Territory can be fully absorbed or taken piece by piece, depending on the current conflict. Nuclear-capable countries may also retaliate when facing elimination.

## Player intervention

Atlas is designed primarily as a watch-first game, but the player can occasionally intervene during an active simulation:

- Press and hold a country to pause the simulation.
- The selected country remains colored while the rest of the map turns gray.
- Drag across the map to choose a red target.
- Release over another country to launch an attack and watch the outcome.

The game then resumes automatically, carrying the result forward into the wider conflict.

## Controls

- Click a country outside an active simulation to inspect and edit its strategic values.
- Use the simulation-speed control to change the pacing.
- Pause, resume, skip ahead, or step backward through recent conflict history.
- Use the map controls to zoom, reset the view, or expand the map.

## Status

Atlas is in beta and is actively being developed as a game. The current model is fictional and outcome-focused. It is not intended to represent real-world military capability, political likelihood, or geopolitical predictions.

## Running locally

This is a static web project. Serve the project directory with any local web server, then open `index.html` in a browser.

The app loads D3 and TopoJSON from CDNs, so an internet connection is needed when those resources are not already cached.
