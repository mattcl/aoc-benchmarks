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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.1 ± 5.6 | 13.5 | 35.3 | 7.46 ± 3.51 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 19.9 ± 5.7 | 13.5 | 37.0 | 6.73 ± 3.29 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 18.3 ± 5.2 | 13.1 | 28.3 | 6.19 ± 3.03 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.8 ± 5.7 | 13.0 | 30.2 | 6.70 ± 3.28 |
| `aspidites-solver/aoc -i input-pting -d 4` | 19.0 ± 6.1 | 12.8 | 37.9 | 6.42 ± 3.28 |
| `kcen/2022/04/solve input-aspidites` | 5.2 ± 1.5 | 2.6 | 17.3 | 1.74 ± 0.85 |
| `kcen/2022/04/solve input-kcen` | 5.5 ± 1.7 | 3.1 | 15.6 | 1.85 ± 0.93 |
| `kcen/2022/04/solve input-lanjian` | 5.0 ± 1.7 | 2.6 | 21.2 | 1.71 ± 0.88 |
| `kcen/2022/04/solve input-mattcl` | 4.7 ± 1.4 | 2.4 | 17.3 | 1.61 ± 0.80 |
| `kcen/2022/04/solve input-pting` | 7.7 ± 5.3 | 2.8 | 44.3 | 2.60 ± 2.08 |
| `lanjian/day_04 input-aspidites` | 3.2 ± 1.2 | 1.3 | 16.0 | 1.07 ± 0.59 |
| `lanjian/day_04 input-kcen` | 3.2 ± 0.9 | 1.4 | 7.0 | 1.07 ± 0.53 |
| `lanjian/day_04 input-lanjian` | 3.3 ± 1.2 | 1.3 | 13.2 | 1.12 ± 0.61 |
| `lanjian/day_04 input-mattcl` | 3.0 ± 1.2 | 1.1 | 19.7 | 1.00 |
| `lanjian/day_04 input-pting` | 3.2 ± 1.2 | 1.2 | 11.8 | 1.07 ± 0.59 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.3 ± 1.3 | 1.3 | 12.4 | 1.12 ± 0.63 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.2 ± 1.6 | 1.1 | 20.9 | 1.09 ± 0.68 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.4 ± 1.6 | 1.3 | 21.0 | 1.16 ± 0.71 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.1 ± 1.2 | 0.9 | 10.7 | 1.05 ± 0.58 |
| `mattcl-solver/aoc run 4 input-pting` | 3.5 ± 1.3 | 1.3 | 15.8 | 1.19 ± 0.66 |
| `python pting/day04.py input-aspidites` | 57.7 ± 10.4 | 44.4 | 89.4 | 19.50 ± 8.51 |
| `python pting/day04.py input-kcen` | 58.4 ± 8.0 | 43.7 | 83.0 | 19.74 ± 8.30 |
| `python pting/day04.py input-lanjian` | 55.7 ± 7.6 | 43.0 | 78.8 | 18.84 ± 7.92 |
| `python pting/day04.py input-mattcl` | 55.2 ± 7.5 | 41.5 | 76.2 | 18.65 ± 7.83 |
| `python pting/day04.py input-pting` | 55.1 ± 8.7 | 42.0 | 86.0 | 18.62 ± 7.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
