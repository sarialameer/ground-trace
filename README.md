# When the Satellite Goes Dark

Ground trace of a satellite about an oblate planet, proved by hand and then coded.

> **Simulation GIF:** coming soon. It will show the ground trace of the ISS and of Sentinel-1 over a world map,
> with the night side shaded and the satellite marker changing colour when it enters Earth's shadow.

## The idea

A satellite orbits a planet that is not a perfect sphere. The flattening of the planet slowly turns the orbit,
and the planet rotates underneath it. The point on the ground directly below the satellite (the sub-satellite point)
draws a path on the map: the **ground trace**.

This project asks two questions:

1. Where is the ground trace at any time? (Proved from the oblate-planet gravity field, step by step.)
2. When is the satellite in the dark? There are two kinds of dark:
   the **satellite** is in Earth's shadow (an eclipse), or the **ground point below it** is on the night side.

Every result is proved by hand first, then written as a Python function and as a Wolfram Language function,
and checked on two real satellites: the **ISS** and **Sentinel-1**.

## Source

The ground-trace method follows Escobal, P. R., *Methods of Orbit Determination*, Wiley, 1965, section 10.3.2.
The darkness part (Sun, night side, eclipse) is an extension that is not in that section.
No pages of the book are included in this repository.

## Progress

- [ ] Part 0: Prerequisites 4 hours and 40 minutes
- [ ] Part 1: 
- [ ] Part 2: 
- [ ] Part 3: 
- [ ] Part 4: 
- [ ] Part 5: 
- [ ] Part 6: 
- [ ] Part 7: 
- [ ] Part 8: 
- [ ] Part 9: 

## Repository map

| Folder | What is in it |
|---|---|
| `derivations/latex/` | The proofs typeset in LaTeX |
| `src/groundtrace/` | The Python package |
| `tests/` | Tests for the package |
| `notebooks/` | Jupyter notebooks |
| `mathematica/` | Wolfram Language notebooks and packages |
| `data/raw/` | Downloaded data, never edited |
| `data/processed/` | Data made by the code |
| `animations/` | Code for the simulations |
| `assets/` | Finished GIFs and figures used in this README |

## How to run it

Not written yet. It will be added when the code exists.

## License

- Code (`src/`, `tests/`, `notebooks/`, `mathematica/`): MIT, see [LICENSE](LICENSE).
- Derivations, guide, figures, animations: CC BY 4.0, see [LICENSE-docs](LICENSE-docs).
