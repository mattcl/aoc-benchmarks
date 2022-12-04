# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 7.7 ± 1.0 | 6.3 | 13.9 | 6.34 ± 2.20 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 8.3 ± 1.2 | 6.6 | 18.6 | 6.80 ± 2.40 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 8.0 ± 1.2 | 6.2 | 14.0 | 6.59 ± 2.34 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.0 ± 1.2 | 6.3 | 12.6 | 6.58 ± 2.36 |
| `aspidites-solver/aoc -i input-pting -d 1` | 7.9 ± 1.2 | 6.3 | 18.8 | 6.45 ± 2.29 |
| `kcen/2022/01/solve.sh input-aspidites` | 209.8 ± 16.8 | 189.8 | 235.5 | 172.27 ± 57.37 |
| `kcen/2022/01/solve.sh input-kcen` | 213.0 ± 13.2 | 184.0 | 231.3 | 174.84 ± 57.53 |
| `kcen/2022/01/solve.sh input-lanjian` | 222.7 ± 20.1 | 201.1 | 277.3 | 182.84 ± 61.35 |
| `kcen/2022/01/solve.sh input-mattcl` | 208.1 ± 13.0 | 194.9 | 239.0 | 170.81 ± 56.23 |
| `kcen/2022/01/solve.sh input-pting` | 201.0 ± 11.7 | 188.7 | 234.7 | 165.01 ± 54.20 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.4 | 0.8 | 4.1 | 1.33 ± 0.56 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.6 | 0.9 | 8.5 | 1.31 ± 0.65 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.5 | 0.8 | 4.5 | 1.41 ± 0.60 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.8 | 0.9 | 9.3 | 1.44 ± 0.80 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.4 | 0.9 | 4.2 | 1.28 ± 0.53 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.5 | 0.7 | 7.1 | 1.06 ± 0.51 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.6 | 0.7 | 5.6 | 1.26 ± 0.63 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.5 | 0.6 | 8.3 | 1.08 ± 0.56 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.4 | 0.7 | 3.8 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.3 | 0.7 | 3.4 | 1.12 ± 0.46 |
| `python pting/day01.py input-aspidites` | 36.0 ± 6.3 | 28.0 | 58.2 | 29.53 ± 10.86 |
| `python pting/day01.py input-kcen` | 34.5 ± 5.6 | 28.0 | 51.9 | 28.33 ± 10.26 |
| `python pting/day01.py input-lanjian` | 35.6 ± 5.6 | 28.0 | 52.2 | 29.23 ± 10.50 |
| `python pting/day01.py input-mattcl` | 44.5 ± 17.0 | 31.1 | 121.7 | 36.52 ± 18.27 |
| `python pting/day01.py input-pting` | 34.9 ± 5.2 | 28.2 | 52.8 | 28.64 ± 10.19 |
