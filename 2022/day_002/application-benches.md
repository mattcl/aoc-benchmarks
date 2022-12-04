# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.6 ± 1.0 | 11.6 | 23.5 | 9.79 ± 3.70 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.3 ± 1.1 | 11.3 | 22.9 | 9.55 ± 3.62 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.7 ± 0.8 | 11.6 | 16.0 | 9.88 ± 3.70 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.2 ± 0.9 | 11.8 | 19.2 | 10.23 ± 3.84 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.2 ± 1.5 | 11.4 | 27.4 | 9.47 ± 3.68 |
| `kcen/2022/02/solve input-aspidites` | 236.6 ± 20.8 | 214.1 | 286.4 | 183.44 ± 69.69 |
| `kcen/2022/02/solve input-kcen` | 215.5 ± 17.9 | 192.2 | 244.5 | 167.09 ± 63.30 |
| `kcen/2022/02/solve input-lanjian` | 232.0 ± 23.1 | 213.3 | 296.2 | 179.90 ± 68.86 |
| `kcen/2022/02/solve input-mattcl` | 251.1 ± 26.0 | 210.6 | 316.6 | 194.71 ± 74.74 |
| `kcen/2022/02/solve input-pting` | 212.2 ± 11.1 | 200.7 | 235.3 | 164.58 ± 61.44 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 0.6 | 0.9 | 5.5 | 1.64 ± 0.77 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.5 | 0.9 | 5.1 | 1.48 ± 0.69 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.7 | 1.1 | 8.7 | 1.70 ± 0.85 |
| `lanjian/day_02 input-mattcl` | 2.1 ± 0.8 | 1.0 | 7.0 | 1.66 ± 0.86 |
| `lanjian/day_02 input-pting` | 2.2 ± 0.9 | 1.0 | 10.8 | 1.71 ± 0.93 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.8 ± 0.6 | 0.8 | 7.4 | 1.37 ± 0.68 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.5 | 0.6 | 5.2 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.6 | 0.7 | 7.3 | 1.17 ± 0.64 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.6 | 1.0 | 6.4 | 1.35 ± 0.70 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 1.0 | 0.8 | 9.4 | 1.35 ± 0.91 |
| `python pting/day02.py input-aspidites` | 38.0 ± 5.4 | 31.9 | 57.5 | 29.49 ± 11.69 |
| `python pting/day02.py input-kcen` | 34.8 ± 3.7 | 29.2 | 46.7 | 27.00 ± 10.39 |
| `python pting/day02.py input-lanjian` | 36.9 ± 4.4 | 30.1 | 51.5 | 28.59 ± 11.10 |
| `python pting/day02.py input-mattcl` | 35.5 ± 4.3 | 29.2 | 49.4 | 27.54 ± 10.71 |
| `python pting/day02.py input-pting` | 34.6 ± 4.0 | 29.3 | 46.8 | 26.87 ± 10.39 |
