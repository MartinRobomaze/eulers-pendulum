# IYPT 2023 Euler's pendulum
This repository is a partial solution for IYPT problem number 8. The solution contains experimental data and jupyter notebooks used to process data in these folders:

- `data` - Contains all experimental data (only processed csv files),
- `data_processing` - contains jupyter notebook where data is processed and graphs are generated,
- `magnetic moment` - contains measured magnetizations of used magnets,
- `simulation` - contains programs used to simulate the magnet motion.

### What is done
* Experiments with changing parameters of the pendulum (diameter, length, magnetization of magnets),
* simulation describing the movement of the pendulum without magnetic forces,
* attempted simulation of pendulum movement considering effects of magnetic forces
### What needs to be done
* Reworking the calculation of magnetic force - current way is not very precise,
* correcting experimental data for perspective error and correctly calculating the incilation angle from the data.

Videos of exprimental data available at: (TODO soon).

This solution is partially based on presentations from the [Slovak YPT introductory meetup](tmfsr.sk/sk/aktuality/227) (presentations in slovak).
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
