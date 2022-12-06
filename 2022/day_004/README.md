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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.3 ± 7.3 | 12.6 | 40.7 | 9.79 ± 5.63 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 21.9 ± 8.0 | 12.5 | 43.1 | 9.21 ± 5.55 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 25.1 ± 9.1 | 12.7 | 51.6 | 10.55 ± 6.36 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 21.6 ± 8.1 | 12.7 | 41.9 | 9.09 ± 5.55 |
| `aspidites-solver/aoc -i input-pting -d 4` | 26.4 ± 8.8 | 12.9 | 66.2 | 11.11 ± 6.50 |
| `kcen/2022/04/solve input-aspidites` | 4.7 ± 2.7 | 1.9 | 16.2 | 1.97 ± 1.48 |
| `kcen/2022/04/solve input-kcen` | 4.1 ± 2.2 | 1.7 | 17.1 | 1.74 ± 1.26 |
| `kcen/2022/04/solve input-lanjian` | 4.6 ± 2.0 | 1.9 | 16.3 | 1.92 ± 1.26 |
| `kcen/2022/04/solve input-mattcl` | 4.0 ± 2.0 | 1.8 | 17.2 | 1.69 ± 1.18 |
| `kcen/2022/04/solve input-pting` | 4.7 ± 2.6 | 1.5 | 17.3 | 1.97 ± 1.46 |
| `lanjian/day_04 input-aspidites` | 2.7 ± 1.8 | 0.3 | 19.2 | 1.13 ± 0.94 |
| `lanjian/day_04 input-kcen` | 2.5 ± 1.5 | 0.3 | 9.1 | 1.04 ± 0.81 |
| `lanjian/day_04 input-lanjian` | 3.0 ± 2.2 | 0.3 | 29.2 | 1.24 ± 1.10 |
| `lanjian/day_04 input-mattcl` | 2.4 ± 1.1 | 0.8 | 9.1 | 1.00 |
| `lanjian/day_04 input-pting` | 3.4 ± 1.6 | 0.8 | 10.4 | 1.44 ± 0.97 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.7 ± 2.3 | 0.5 | 38.2 | 1.14 ± 1.10 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.9 ± 2.3 | 0.5 | 14.7 | 1.65 ± 1.27 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.8 ± 1.3 | 0.7 | 9.4 | 1.18 ± 0.79 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.8 ± 1.4 | 0.9 | 10.7 | 1.17 ± 0.81 |
| `mattcl-solver/aoc run 4 input-pting` | 3.4 ± 1.9 | 0.7 | 17.8 | 1.44 ± 1.06 |
| `python pting/day04.py input-aspidites` | 60.5 ± 17.4 | 44.9 | 124.9 | 25.46 ± 14.26 |
| `python pting/day04.py input-kcen` | 80.9 ± 39.8 | 42.3 | 183.3 | 34.05 ± 23.43 |
| `python pting/day04.py input-lanjian` | 55.4 ± 9.5 | 45.5 | 112.1 | 23.32 ± 11.91 |
| `python pting/day04.py input-mattcl` | 76.5 ± 36.2 | 45.9 | 191.3 | 32.18 ± 21.72 |
| `python pting/day04.py input-pting` | 73.3 ± 37.0 | 47.2 | 192.0 | 30.83 ± 21.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
