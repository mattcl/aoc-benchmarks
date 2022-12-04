# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.9 ± 1.6 | 11.8 | 24.1 | 11.89 ± 3.96 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.1 ± 1.8 | 12.0 | 23.8 | 12.09 ± 4.08 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 1.9 | 11.8 | 24.5 | 11.90 ± 4.09 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.0 ± 2.2 | 11.7 | 25.4 | 11.95 ± 4.23 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.1 ± 1.9 | 12.0 | 23.7 | 12.03 ± 4.14 |
| `kcen/2022/03/solve input-aspidites` | 241.4 ± 9.2 | 226.0 | 257.1 | 222.37 ± 69.37 |
| `kcen/2022/03/solve input-kcen` | 244.6 ± 13.9 | 231.4 | 274.4 | 225.25 ± 70.90 |
| `kcen/2022/03/solve input-lanjian` | 243.7 ± 19.8 | 214.7 | 280.0 | 224.48 ± 71.86 |
| `kcen/2022/03/solve input-mattcl` | 220.8 ± 8.5 | 206.2 | 234.9 | 203.36 ± 63.45 |
| `kcen/2022/03/solve input-pting` | 238.0 ± 8.5 | 224.1 | 252.4 | 219.25 ± 68.33 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.6 | 0.7 | 9.5 | 1.23 ± 0.67 |
| `lanjian/day_03 input-kcen` | 1.8 ± 0.5 | 0.8 | 6.6 | 1.62 ± 0.71 |
| `lanjian/day_03 input-lanjian` | 1.4 ± 0.5 | 0.8 | 7.6 | 1.25 ± 0.58 |
| `lanjian/day_03 input-mattcl` | 1.1 ± 0.3 | 0.7 | 5.4 | 1.00 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.4 | 0.7 | 6.4 | 1.00 ± 0.48 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.8 ± 0.7 | 0.8 | 10.2 | 1.63 ± 0.84 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.8 ± 0.7 | 0.9 | 11.2 | 1.64 ± 0.83 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.6 | 0.8 | 9.1 | 1.27 ± 0.67 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.1 ± 0.3 | 0.7 | 4.2 | 1.06 ± 0.43 |
| `mattcl-solver/aoc run 3 input-pting` | 1.2 ± 0.4 | 0.7 | 8.9 | 1.09 ± 0.51 |
| `python pting/day03.py input-aspidites` | 32.5 ± 3.0 | 29.2 | 52.8 | 29.98 ± 9.69 |
| `python pting/day03.py input-kcen` | 35.8 ± 5.0 | 29.5 | 53.6 | 32.95 ± 11.19 |
| `python pting/day03.py input-lanjian` | 35.5 ± 4.1 | 29.4 | 47.9 | 32.66 ± 10.78 |
| `python pting/day03.py input-mattcl` | 34.4 ± 3.7 | 29.4 | 44.7 | 31.65 ± 10.37 |
| `python pting/day03.py input-pting` | 35.0 ± 4.6 | 30.0 | 58.8 | 32.21 ± 10.83 |
