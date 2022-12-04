# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 63.2 ± 6.4 | 53.8 | 80.9 | 38.81 ± 15.84 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 60.1 ± 5.1 | 54.2 | 79.2 | 36.88 ± 14.91 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 58.3 ± 4.6 | 52.1 | 75.1 | 35.80 ± 14.43 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 61.3 ± 6.9 | 53.0 | 90.7 | 37.64 ± 15.47 |
| `aspidites-solver/aoc -i input-pting -d 2` | 57.9 ± 5.2 | 52.2 | 77.5 | 35.52 ± 14.39 |
| `kcen/2022/02/solve input-aspidites` | 240.1 ± 18.3 | 213.2 | 275.6 | 147.33 ± 59.32 |
| `kcen/2022/02/solve input-kcen` | 210.5 ± 6.6 | 199.7 | 220.2 | 129.14 ± 51.21 |
| `kcen/2022/02/solve input-lanjian` | 213.6 ± 26.8 | 180.1 | 262.0 | 131.05 ± 54.35 |
| `kcen/2022/02/solve input-mattcl` | 232.4 ± 34.0 | 196.3 | 293.1 | 142.60 ± 60.10 |
| `kcen/2022/02/solve input-pting` | 208.1 ± 12.8 | 186.9 | 238.7 | 127.70 ± 51.09 |
| `lanjian/day_02 input-aspidites` | 2.4 ± 0.6 | 1.3 | 10.0 | 1.44 ± 0.69 |
| `lanjian/day_02 input-kcen` | 2.1 ± 0.6 | 1.2 | 4.4 | 1.26 ± 0.61 |
| `lanjian/day_02 input-lanjian` | 1.9 ± 0.5 | 1.2 | 5.3 | 1.18 ± 0.55 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.6 | 1.1 | 8.2 | 1.19 ± 0.60 |
| `lanjian/day_02 input-pting` | 2.3 ± 0.5 | 1.4 | 4.6 | 1.43 ± 0.63 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.2 ± 1.0 | 1.1 | 8.5 | 1.32 ± 0.81 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.0 ± 0.6 | 1.0 | 7.0 | 1.20 ± 0.62 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.6 | 1.0 | 17.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.9 ± 0.4 | 1.1 | 4.1 | 1.16 ± 0.52 |
| `mattcl-solver/aoc run 2 input-pting` | 2.1 ± 0.5 | 1.1 | 5.8 | 1.29 ± 0.60 |
| `python pting/day02.py input-aspidites` | 43.8 ± 11.1 | 32.8 | 114.9 | 26.88 ± 12.62 |
| `python pting/day02.py input-kcen` | 33.0 ± 2.8 | 29.1 | 43.8 | 20.26 ± 8.19 |
| `python pting/day02.py input-lanjian` | 36.3 ± 3.8 | 30.4 | 48.5 | 22.27 ± 9.10 |
| `python pting/day02.py input-mattcl` | 33.9 ± 5.1 | 26.7 | 58.4 | 20.81 ± 8.81 |
| `python pting/day02.py input-pting` | 34.9 ± 3.7 | 29.8 | 46.8 | 21.41 ± 8.75 |
