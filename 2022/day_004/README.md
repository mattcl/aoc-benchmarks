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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.8 ± 5.2 | 13.6 | 40.5 | 8.74 ± 3.83 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 25.6 ± 6.1 | 14.0 | 56.6 | 9.40 ± 4.22 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.2 ± 5.4 | 13.5 | 38.4 | 8.52 ± 3.79 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 20.4 ± 6.0 | 13.5 | 38.3 | 7.49 ± 3.60 |
| `aspidites-solver/aoc -i input-pting -d 4` | 25.2 ± 6.3 | 13.4 | 60.6 | 9.26 ± 4.21 |
| `kcen/2022/04/solve input-aspidites` | 4.7 ± 1.4 | 2.3 | 16.5 | 1.72 ± 0.83 |
| `kcen/2022/04/solve input-kcen` | 6.1 ± 1.8 | 3.2 | 18.1 | 2.22 ± 1.08 |
| `kcen/2022/04/solve input-lanjian` | 4.8 ± 1.5 | 2.7 | 13.1 | 1.77 ± 0.88 |
| `kcen/2022/04/solve input-mattcl` | 4.4 ± 1.0 | 2.1 | 9.8 | 1.62 ± 0.73 |
| `kcen/2022/04/solve input-pting` | 4.4 ± 1.3 | 2.0 | 12.8 | 1.60 ± 0.78 |
| `lanjian/day_04 input-aspidites` | 2.8 ± 1.0 | 1.1 | 10.6 | 1.01 ± 0.53 |
| `lanjian/day_04 input-kcen` | 3.4 ± 2.4 | 1.1 | 41.9 | 1.26 ± 0.99 |
| `lanjian/day_04 input-lanjian` | 3.2 ± 1.2 | 1.4 | 15.1 | 1.19 ± 0.63 |
| `lanjian/day_04 input-mattcl` | 2.7 ± 1.0 | 1.1 | 8.8 | 1.00 |
| `lanjian/day_04 input-pting` | 3.6 ± 1.4 | 1.2 | 15.6 | 1.33 ± 0.72 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.0 ± 1.1 | 1.2 | 9.0 | 1.12 ± 0.58 |
| `mattcl-solver/aoc run 4 input-kcen` | 7.1 ± 6.4 | 1.8 | 42.1 | 2.59 ± 2.55 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.5 ± 1.1 | 1.7 | 17.7 | 1.30 ± 0.64 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.8 ± 1.1 | 1.2 | 12.4 | 1.04 ± 0.56 |
| `mattcl-solver/aoc run 4 input-pting` | 3.7 ± 1.8 | 1.2 | 23.4 | 1.37 ± 0.83 |
| `python pting/day04.py input-aspidites` | 63.4 ± 10.4 | 50.7 | 97.8 | 23.26 ± 9.61 |
| `python pting/day04.py input-kcen` | 68.5 ± 9.2 | 53.5 | 99.5 | 25.13 ± 10.12 |
| `python pting/day04.py input-lanjian` | 84.4 ± 36.2 | 47.8 | 188.5 | 30.96 ± 17.74 |
| `python pting/day04.py input-mattcl` | 58.9 ± 6.4 | 47.5 | 76.2 | 21.61 ± 8.54 |
| `python pting/day04.py input-pting` | 60.1 ± 7.6 | 48.3 | 94.5 | 22.05 ± 8.82 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
