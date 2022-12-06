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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.7 ± 4.9 | 13.6 | 38.9 | 12.34 ± 8.79 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 23.0 ± 5.3 | 13.5 | 31.1 | 11.95 ± 8.59 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 21.7 ± 6.3 | 13.1 | 39.3 | 11.27 ± 8.35 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 22.0 ± 5.7 | 13.3 | 34.7 | 11.45 ± 8.35 |
| `aspidites-solver/aoc -i input-pting -d 4` | 21.2 ± 5.6 | 13.2 | 35.4 | 11.04 ± 8.07 |
| `kcen/2022/04/solve input-aspidites` | 4.6 ± 1.5 | 2.2 | 16.9 | 2.38 ± 1.79 |
| `kcen/2022/04/solve input-kcen` | 5.1 ± 1.5 | 2.1 | 14.6 | 2.66 ± 1.98 |
| `kcen/2022/04/solve input-lanjian` | 3.9 ± 1.5 | 1.8 | 12.0 | 2.02 ± 1.60 |
| `kcen/2022/04/solve input-mattcl` | 4.4 ± 2.1 | 1.9 | 25.2 | 2.28 ± 1.88 |
| `kcen/2022/04/solve input-pting` | 4.7 ± 1.9 | 2.1 | 16.9 | 2.46 ± 1.94 |
| `lanjian/day_04 input-aspidites` | 3.1 ± 1.3 | 0.8 | 10.9 | 1.61 ± 1.29 |
| `lanjian/day_04 input-kcen` | 2.8 ± 1.2 | 0.6 | 10.5 | 1.46 ± 1.17 |
| `lanjian/day_04 input-lanjian` | 1.9 ± 1.3 | 0.6 | 19.2 | 1.00 |
| `lanjian/day_04 input-mattcl` | 2.8 ± 1.3 | 0.6 | 16.0 | 1.44 ± 1.19 |
| `lanjian/day_04 input-pting` | 2.5 ± 1.6 | 0.7 | 16.1 | 1.32 ± 1.24 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.7 ± 1.1 | 0.7 | 8.9 | 1.42 ± 1.13 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.1 ± 1.0 | 0.5 | 6.2 | 1.08 ± 0.90 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.2 ± 1.2 | 0.5 | 12.6 | 1.14 ± 0.99 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.0 ± 1.2 | 0.9 | 9.6 | 1.54 ± 1.22 |
| `mattcl-solver/aoc run 4 input-pting` | 4.8 ± 4.6 | 0.7 | 31.0 | 2.50 ± 2.94 |
| `python pting/day04.py input-aspidites` | 61.0 ± 10.1 | 45.6 | 93.6 | 31.75 ± 22.27 |
| `python pting/day04.py input-kcen` | 61.3 ± 8.3 | 49.6 | 84.8 | 31.90 ± 22.16 |
| `python pting/day04.py input-lanjian` | 62.3 ± 10.1 | 45.1 | 93.1 | 32.41 ± 22.71 |
| `python pting/day04.py input-mattcl` | 63.0 ± 11.1 | 48.4 | 98.1 | 32.80 ± 23.08 |
| `python pting/day04.py input-pting` | 60.5 ± 9.7 | 47.6 | 89.2 | 31.49 ± 22.04 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
