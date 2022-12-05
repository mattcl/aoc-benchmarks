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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 32.7 ± 2.0 | 31.8 | 42.8 | 28.61 ± 6.92 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 34.1 ± 3.8 | 31.9 | 45.1 | 29.83 ± 7.74 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 35.4 ± 4.6 | 32.0 | 44.1 | 30.98 ± 8.29 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 34.3 ± 4.1 | 31.9 | 53.6 | 29.98 ± 7.89 |
| `aspidites-solver/aoc -i input-pting -d 4` | 33.4 ± 3.0 | 31.9 | 43.9 | 29.23 ± 7.34 |
| `kcen/2022/04/solve input-aspidites` | 2.3 ± 0.3 | 1.8 | 3.9 | 1.97 ± 0.55 |
| `kcen/2022/04/solve input-kcen` | 2.4 ± 0.4 | 1.7 | 4.8 | 2.07 ± 0.62 |
| `kcen/2022/04/solve input-lanjian` | 2.8 ± 0.8 | 1.6 | 8.1 | 2.43 ± 0.90 |
| `kcen/2022/04/solve input-mattcl` | 2.4 ± 0.4 | 1.9 | 4.7 | 2.14 ± 0.61 |
| `kcen/2022/04/solve input-pting` | 2.2 ± 0.3 | 1.9 | 9.0 | 1.93 ± 0.54 |
| `lanjian/day_04 input-aspidites` | 1.6 ± 0.7 | 0.9 | 5.9 | 1.41 ± 0.69 |
| `lanjian/day_04 input-kcen` | 1.3 ± 0.6 | 0.8 | 10.9 | 1.12 ± 0.60 |
| `lanjian/day_04 input-lanjian` | 2.0 ± 1.1 | 0.9 | 15.2 | 1.75 ± 1.04 |
| `lanjian/day_04 input-mattcl` | 1.3 ± 0.3 | 0.8 | 3.3 | 1.11 ± 0.35 |
| `lanjian/day_04 input-pting` | 1.1 ± 0.3 | 0.8 | 4.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.5 ± 0.4 | 1.0 | 5.7 | 1.27 ± 0.46 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.3 ± 0.4 | 0.9 | 8.9 | 1.17 ± 0.47 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.6 ± 0.6 | 0.9 | 6.9 | 1.42 ± 0.59 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.4 ± 0.5 | 0.9 | 7.1 | 1.20 ± 0.51 |
| `mattcl-solver/aoc run 4 input-pting` | 1.3 ± 0.3 | 0.9 | 6.4 | 1.13 ± 0.39 |
| `python pting/day04.py input-aspidites` | 33.7 ± 3.0 | 29.5 | 50.1 | 29.47 ± 7.38 |
| `python pting/day04.py input-kcen` | 36.5 ± 5.1 | 29.4 | 56.0 | 31.95 ± 8.72 |
| `python pting/day04.py input-lanjian` | 45.6 ± 20.2 | 32.2 | 123.9 | 39.84 ± 20.00 |
| `python pting/day04.py input-mattcl` | 35.0 ± 3.8 | 29.6 | 58.6 | 30.57 ± 7.89 |
| `python pting/day04.py input-pting` | 32.8 ± 2.2 | 29.4 | 41.7 | 28.65 ± 6.99 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
