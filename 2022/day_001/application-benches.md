# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 0.5 | 11.1 | 14.0 | 14.38 ± 5.95 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.5 ± 0.8 | 10.7 | 22.3 | 13.59 ± 5.69 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.0 ± 0.9 | 11.0 | 22.0 | 14.17 ± 5.93 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 11.8 ± 1.1 | 10.7 | 23.1 | 13.99 ± 5.92 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.7 ± 0.5 | 10.8 | 13.8 | 13.90 ± 5.76 |
| `kcen/2022/01/solve input-aspidites` | 105.5 ± 11.2 | 88.6 | 133.4 | 125.07 ± 53.21 |
| `kcen/2022/01/solve input-kcen` | 100.4 ± 7.4 | 87.5 | 121.3 | 119.00 ± 49.80 |
| `kcen/2022/01/solve input-lanjian` | 99.1 ± 9.4 | 88.4 | 127.7 | 117.48 ± 49.67 |
| `kcen/2022/01/solve input-mattcl` | 106.4 ± 9.4 | 92.1 | 127.3 | 126.11 ± 53.13 |
| `kcen/2022/01/solve input-pting` | 104.9 ± 6.7 | 92.7 | 116.9 | 124.36 ± 51.84 |
| `lanjian/day_01 input-aspidites` | 1.1 ± 0.4 | 0.2 | 3.3 | 1.33 ± 0.75 |
| `lanjian/day_01 input-kcen` | 2.6 ± 2.0 | 0.3 | 13.5 | 3.13 ± 2.65 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.7 | 0.5 | 5.7 | 2.03 ± 1.19 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.5 | 0.5 | 4.5 | 1.59 ± 0.88 |
| `lanjian/day_01 input-pting` | 0.8 ± 0.3 | 0.3 | 3.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.0 ± 0.6 | 0.3 | 7.1 | 1.19 ± 0.81 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.7 ± 1.5 | 0.3 | 10.2 | 1.98 ± 1.91 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.6 | 0.3 | 4.3 | 1.48 ± 0.95 |
| `mattcl-solver/aoc run 1 input-mattcl` | 0.9 ± 0.5 | 0.0 | 8.7 | 1.05 ± 0.73 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.4 | 0.1 | 4.8 | 1.17 ± 0.69 |
| `python pting/day01.py input-aspidites` | 32.6 ± 4.0 | 26.8 | 46.1 | 38.63 ± 16.61 |
| `python pting/day01.py input-kcen` | 31.4 ± 4.6 | 24.5 | 47.3 | 37.27 ± 16.30 |
| `python pting/day01.py input-lanjian` | 30.0 ± 3.0 | 25.3 | 40.3 | 35.61 ± 15.10 |
| `python pting/day01.py input-mattcl` | 32.3 ± 3.3 | 27.4 | 42.2 | 38.32 ± 16.25 |
| `python pting/day01.py input-pting` | 34.4 ± 5.3 | 24.0 | 57.4 | 40.80 ± 17.93 |
