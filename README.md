# semistatic-btu

A 3D-printable ball transfer unit (BTU) for trackballs, inspired by [scatterthought/semistatic-bearing](https://github.com/scatterthought/semistatic-bearing).

It's designed to pair with the [efog.tech](https://efog.tech/) Endgame trackball.

## Design

This BTU uses a **main / sub ball** design:

- A single **6mm main ball** rides on top of three **3mm sub-balls**.
- The sub-balls provide low-friction contact points for the main ball to roll on.

The key feature is the clearance around the main ball. The cavity is carefully sized so the main ball has some room — enough that it never contacts the printed shell, but not so much that the sub-balls leave their seated positions.

Under load, the main ball only ever contacts the three sub-balls, keeping friction low and consistent.

## Bill of materials (per unit)

- 1× 6mm main ball
- 3× 3mm sub-balls

## Files

| File | Description |
| --- | --- |
| `stl/semistatic-btu-body.stl` | Main housing that holds the sub-balls and main ball |
| `stl/semistatic-btu-cap.stl` | Cap that retains the main ball |

## Materials

I've ordered various ball materials to test which combination works best. Results will be posted here once testing is done.

## License

MIT. See [LICENSE](LICENSE).
