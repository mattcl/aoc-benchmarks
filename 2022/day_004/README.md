# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 4)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 4` | 34.9 ± 4.4 | 31.9 | 46.6 | 29.93 ± 11.61 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 33.9 ± 5.2 | 31.9 | 73.1 | 29.05 ± 11.53 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 35.1 ± 4.3 | 32.1 | 45.2 | 30.11 ± 11.65 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 38.4 ± 6.6 | 32.0 | 62.6 | 32.92 ± 13.34 |
| `aspidites-solver/aoc -i input-pting -d 4` | 33.1 ± 2.7 | 31.8 | 43.4 | 28.36 ± 10.64 |
| `kcen/2022/04/solve input-aspidites` | 2.8 ± 0.7 | 1.9 | 9.3 | 2.36 ± 1.05 |
| `kcen/2022/04/solve input-kcen` | 2.6 ± 0.5 | 1.9 | 5.8 | 2.24 ± 0.91 |
| `kcen/2022/04/solve input-lanjian` | 2.5 ± 0.4 | 1.8 | 5.3 | 2.13 ± 0.86 |
| `kcen/2022/04/solve input-mattcl` | 2.9 ± 0.6 | 1.9 | 8.1 | 2.52 ± 1.04 |
| `kcen/2022/04/solve input-pting` | 2.5 ± 0.5 | 1.8 | 6.3 | 2.19 ± 0.91 |
| `lanjian/day_04 input-aspidites` | 1.4 ± 0.4 | 0.8 | 5.1 | 1.20 ± 0.55 |
| `lanjian/day_04 input-kcen` | 1.4 ± 0.4 | 0.8 | 7.5 | 1.17 ± 0.56 |
| `lanjian/day_04 input-lanjian` | 1.3 ± 0.3 | 0.7 | 3.4 | 1.08 ± 0.47 |
| `lanjian/day_04 input-mattcl` | 1.4 ± 0.6 | 0.7 | 7.4 | 1.21 ± 0.66 |
| `lanjian/day_04 input-pting` | 1.2 ± 0.4 | 0.8 | 6.7 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.6 ± 0.8 | 0.9 | 10.4 | 1.37 ± 0.83 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.6 ± 0.6 | 0.9 | 12.1 | 1.38 ± 0.72 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.4 ± 0.3 | 0.9 | 3.3 | 1.18 ± 0.51 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.8 ± 0.8 | 0.9 | 9.5 | 1.58 ± 0.92 |
| `mattcl-solver/aoc run 4 input-pting` | 1.3 ± 0.3 | 0.9 | 4.5 | 1.08 ± 0.47 |
| `python pting/day04.py input-aspidites` | 35.0 ± 4.9 | 30.4 | 66.4 | 29.99 ± 11.77 |
| `python pting/day04.py input-kcen` | 34.6 ± 2.9 | 30.6 | 46.2 | 29.66 ± 11.16 |
| `python pting/day04.py input-lanjian` | 33.7 ± 2.3 | 30.2 | 40.6 | 28.91 ± 10.77 |
| `python pting/day04.py input-mattcl` | 35.4 ± 3.9 | 30.4 | 49.2 | 30.36 ± 11.62 |
| `python pting/day04.py input-pting` | 32.6 ± 2.5 | 29.8 | 45.4 | 27.94 ± 10.46 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
