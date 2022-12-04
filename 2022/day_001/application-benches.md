# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 8.2 ± 0.9 | 6.6 | 12.1 | 7.09 ± 2.48 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 8.8 ± 2.6 | 6.0 | 16.4 | 7.61 ± 3.38 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 8.3 ± 1.0 | 6.7 | 14.0 | 7.16 ± 2.52 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 7.8 ± 0.9 | 6.3 | 13.4 | 6.79 ± 2.37 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.2 ± 1.1 | 6.3 | 13.9 | 7.08 ± 2.54 |
| `kcen/2022/01/solve.sh input-aspidites` | 266.9 ± 38.1 | 213.8 | 322.0 | 231.42 ± 83.44 |
| `kcen/2022/01/solve.sh input-kcen` | 198.3 ± 12.6 | 183.5 | 230.7 | 171.95 ± 57.97 |
| `kcen/2022/01/solve.sh input-lanjian` | 222.3 ± 34.8 | 183.1 | 299.9 | 192.78 ± 70.58 |
| `kcen/2022/01/solve.sh input-mattcl` | 196.1 ± 6.0 | 187.6 | 207.0 | 170.08 ± 56.55 |
| `kcen/2022/01/solve.sh input-pting` | 207.6 ± 12.6 | 184.2 | 235.9 | 180.06 ± 60.60 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.6 | 0.8 | 6.6 | 1.49 ± 0.69 |
| `lanjian/day_01 input-kcen` | 1.8 ± 0.6 | 1.0 | 6.7 | 1.57 ± 0.73 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.6 | 0.8 | 6.4 | 1.50 ± 0.69 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.6 | 0.9 | 9.0 | 1.60 ± 0.77 |
| `lanjian/day_01 input-pting` | 1.7 ± 0.4 | 0.9 | 3.7 | 1.48 ± 0.62 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.5 | 0.7 | 5.5 | 1.32 ± 0.63 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.4 | 0.7 | 5.3 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.7 ± 0.7 | 0.7 | 9.7 | 1.49 ± 0.79 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.4 ± 0.4 | 0.6 | 4.5 | 1.17 ± 0.53 |
| `mattcl-solver/aoc run 1 input-pting` | 1.7 ± 0.5 | 0.7 | 7.5 | 1.47 ± 0.66 |
| `python pting/day01.py input-aspidites` | 38.0 ± 9.8 | 28.7 | 84.2 | 32.97 ± 13.85 |
| `python pting/day01.py input-kcen` | 34.8 ± 4.7 | 28.5 | 48.6 | 30.14 ± 10.79 |
| `python pting/day01.py input-lanjian` | 35.1 ± 3.9 | 28.0 | 44.2 | 30.42 ± 10.62 |
| `python pting/day01.py input-mattcl` | 34.2 ± 5.7 | 27.8 | 59.3 | 29.64 ± 10.97 |
| `python pting/day01.py input-pting` | 36.3 ± 5.0 | 29.8 | 51.2 | 31.49 ± 11.31 |
