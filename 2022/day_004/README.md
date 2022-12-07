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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 21.4 ± 8.9 | 13.3 | 40.7 | 6.81 ± 4.46 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 25.7 ± 9.8 | 13.4 | 45.8 | 8.19 ± 5.20 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 20.2 ± 8.7 | 13.0 | 41.0 | 6.44 ± 4.27 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.5 ± 7.6 | 13.0 | 50.7 | 6.22 ± 3.97 |
| `aspidites-solver/aoc -i input-pting -d 4` | 24.8 ± 9.8 | 13.1 | 53.0 | 7.92 ± 5.07 |
| `kcen/2022/04/solve input-aspidites` | 5.4 ± 2.8 | 2.1 | 19.6 | 1.71 ± 1.24 |
| `kcen/2022/04/solve input-kcen` | 5.9 ± 3.4 | 2.0 | 20.1 | 1.88 ± 1.44 |
| `kcen/2022/04/solve input-lanjian` | 5.5 ± 2.9 | 2.1 | 17.4 | 1.75 ± 1.28 |
| `kcen/2022/04/solve input-mattcl` | 4.8 ± 2.5 | 1.6 | 14.0 | 1.53 ± 1.11 |
| `kcen/2022/04/solve input-pting` | 6.3 ± 3.3 | 2.0 | 18.4 | 2.02 ± 1.47 |
| `lanjian/day_04 input-aspidites` | 4.0 ± 2.1 | 1.2 | 13.6 | 1.28 ± 0.94 |
| `lanjian/day_04 input-kcen` | 3.3 ± 1.7 | 1.1 | 18.9 | 1.05 ± 0.77 |
| `lanjian/day_04 input-lanjian` | 3.1 ± 1.6 | 0.9 | 9.9 | 1.00 |
| `lanjian/day_04 input-mattcl` | 3.2 ± 2.0 | 0.8 | 17.9 | 1.01 ± 0.82 |
| `lanjian/day_04 input-pting` | 3.9 ± 2.1 | 0.8 | 28.8 | 1.24 ± 0.93 |
| `mattcl-solver/aoc run 4 input-aspidites` | 4.5 ± 2.2 | 1.1 | 17.4 | 1.43 ± 1.01 |
| `mattcl-solver/aoc run 4 input-kcen` | 4.0 ± 2.7 | 1.0 | 19.6 | 1.29 ± 1.08 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.7 ± 2.2 | 1.1 | 22.8 | 1.18 ± 0.93 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.3 ± 1.9 | 0.9 | 19.4 | 1.06 ± 0.80 |
| `mattcl-solver/aoc run 4 input-pting` | 7.1 ± 6.7 | 1.1 | 51.8 | 2.26 ± 2.42 |
| `python pting/day04.py input-aspidites` | 55.6 ± 22.2 | 40.2 | 142.9 | 17.74 ± 11.42 |
| `python pting/day04.py input-kcen` | 61.6 ± 30.7 | 42.8 | 182.2 | 19.64 ± 13.95 |
| `python pting/day04.py input-lanjian` | 71.6 ± 34.5 | 37.9 | 186.8 | 22.85 ± 15.96 |
| `python pting/day04.py input-mattcl` | 57.8 ± 22.7 | 42.5 | 125.7 | 18.43 ± 11.80 |
| `python pting/day04.py input-pting` | 66.3 ± 32.8 | 44.0 | 180.4 | 21.16 ± 14.97 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
