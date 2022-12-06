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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 15.9 ± 5.0 | 12.2 | 29.5 | 12.04 ± 9.61 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 17.0 ± 5.2 | 12.4 | 29.6 | 12.87 ± 10.24 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 22.2 ± 6.9 | 12.2 | 36.5 | 16.74 ± 13.36 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 17.1 ± 5.8 | 11.8 | 36.9 | 12.95 ± 10.47 |
| `aspidites-solver/aoc -i input-pting -d 4` | 16.8 ± 5.1 | 12.1 | 25.7 | 12.71 ± 10.08 |
| `kcen/2022/04/solve input-aspidites` | 6.8 ± 7.6 | 1.3 | 60.4 | 5.16 ± 6.87 |
| `kcen/2022/04/solve input-kcen` | 3.6 ± 1.6 | 1.6 | 15.9 | 2.71 ± 2.31 |
| `kcen/2022/04/solve input-lanjian` | 3.6 ± 1.6 | 1.3 | 17.0 | 2.75 ± 2.37 |
| `kcen/2022/04/solve input-mattcl` | 3.2 ± 1.4 | 1.2 | 13.0 | 2.43 ± 2.08 |
| `kcen/2022/04/solve input-pting` | 2.6 ± 1.0 | 1.2 | 8.0 | 1.93 ± 1.61 |
| `lanjian/day_04 input-aspidites` | 1.4 ± 1.0 | 0.1 | 10.6 | 1.05 ± 1.08 |
| `lanjian/day_04 input-kcen` | 1.8 ± 1.0 | 0.1 | 9.0 | 1.38 ± 1.26 |
| `lanjian/day_04 input-lanjian` | 2.9 ± 1.8 | 0.6 | 15.4 | 2.22 ± 2.10 |
| `lanjian/day_04 input-mattcl` | 2.0 ± 1.1 | 0.4 | 6.8 | 1.51 ± 1.38 |
| `lanjian/day_04 input-pting` | 1.9 ± 1.3 | 0.1 | 15.3 | 1.41 ± 1.44 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.3 ± 1.0 | 0.0 | 9.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.4 ± 1.1 | 0.0 | 9.6 | 1.09 ± 1.16 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.6 ± 1.2 | 0.6 | 9.4 | 1.99 ± 1.74 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.6 ± 1.6 | 0.4 | 14.5 | 1.96 ± 1.88 |
| `mattcl-solver/aoc run 4 input-pting` | 1.8 ± 1.1 | 0.2 | 8.3 | 1.40 ± 1.31 |
| `python pting/day04.py input-aspidites` | 58.3 ± 19.1 | 43.8 | 143.8 | 44.04 ± 35.42 |
| `python pting/day04.py input-kcen` | 51.0 ± 5.9 | 39.3 | 65.9 | 38.52 ± 28.63 |
| `python pting/day04.py input-lanjian` | 61.8 ± 7.5 | 51.8 | 82.0 | 46.69 ± 34.74 |
| `python pting/day04.py input-mattcl` | 60.3 ± 9.1 | 47.2 | 91.0 | 45.55 ± 34.14 |
| `python pting/day04.py input-pting` | 53.1 ± 5.2 | 43.4 | 65.9 | 40.09 ± 29.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
