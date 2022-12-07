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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.5 ± 5.3 | 13.5 | 30.0 | 8.28 ± 5.11 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 18.9 ± 5.4 | 13.0 | 27.5 | 6.96 ± 4.44 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 25.4 ± 6.2 | 14.1 | 49.1 | 9.36 ± 5.82 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 23.0 ± 6.0 | 13.6 | 36.6 | 8.46 ± 5.31 |
| `aspidites-solver/aoc -i input-pting -d 4` | 20.5 ± 6.1 | 13.4 | 36.7 | 7.55 ± 4.87 |
| `kcen/2022/04/solve input-aspidites` | 6.0 ± 5.3 | 2.0 | 41.1 | 2.21 ± 2.32 |
| `kcen/2022/04/solve input-kcen` | 4.3 ± 1.5 | 2.0 | 22.2 | 1.58 ± 1.06 |
| `kcen/2022/04/solve input-lanjian` | 5.1 ± 1.5 | 2.3 | 14.9 | 1.86 ± 1.21 |
| `kcen/2022/04/solve input-mattcl` | 5.8 ± 1.9 | 3.1 | 22.1 | 2.14 ± 1.41 |
| `kcen/2022/04/solve input-pting` | 4.9 ± 1.7 | 2.4 | 19.3 | 1.80 ± 1.21 |
| `lanjian/day_04 input-aspidites` | 3.0 ± 1.1 | 0.8 | 9.7 | 1.10 ± 0.76 |
| `lanjian/day_04 input-kcen` | 3.3 ± 1.8 | 0.7 | 18.2 | 1.20 ± 0.95 |
| `lanjian/day_04 input-lanjian` | 3.1 ± 1.1 | 0.8 | 9.9 | 1.16 ± 0.78 |
| `lanjian/day_04 input-mattcl` | 3.8 ± 2.5 | 0.8 | 19.5 | 1.40 ± 1.21 |
| `lanjian/day_04 input-pting` | 2.7 ± 1.5 | 0.4 | 12.8 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.8 ± 1.2 | 0.7 | 8.5 | 1.05 ± 0.75 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.9 ± 1.6 | 1.0 | 13.5 | 1.08 ± 0.85 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.7 ± 1.8 | 1.0 | 29.6 | 1.37 ± 1.03 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.8 ± 1.4 | 0.7 | 8.5 | 1.05 ± 0.79 |
| `mattcl-solver/aoc run 4 input-pting` | 3.0 ± 1.4 | 0.9 | 16.2 | 1.11 ± 0.82 |
| `python pting/day04.py input-aspidites` | 60.2 ± 10.7 | 42.0 | 93.5 | 22.19 ± 13.28 |
| `python pting/day04.py input-kcen` | 57.9 ± 8.2 | 43.8 | 74.9 | 21.35 ± 12.56 |
| `python pting/day04.py input-lanjian` | 68.2 ± 13.3 | 49.7 | 97.8 | 25.15 ± 15.17 |
| `python pting/day04.py input-mattcl` | 74.1 ± 10.2 | 54.3 | 107.7 | 27.32 ± 16.06 |
| `python pting/day04.py input-pting` | 57.1 ± 9.4 | 44.6 | 88.0 | 21.06 ± 12.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
