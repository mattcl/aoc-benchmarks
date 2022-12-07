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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 21.0 ± 6.4 | 13.3 | 38.6 | 8.11 ± 6.40 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.1 ± 9.1 | 12.7 | 45.4 | 7.76 ± 6.65 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.5 ± 7.1 | 13.6 | 46.6 | 9.07 ± 7.15 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.6 ± 7.1 | 13.0 | 39.0 | 7.55 ± 6.14 |
| `aspidites-solver/aoc -i input-pting -d 4` | 21.6 ± 8.9 | 13.2 | 47.2 | 8.35 ± 6.99 |
| `kcen/2022/04/solve input-aspidites` | 5.0 ± 1.7 | 2.0 | 11.5 | 1.94 ± 1.56 |
| `kcen/2022/04/solve input-kcen` | 4.7 ± 2.5 | 1.7 | 13.5 | 1.81 ± 1.64 |
| `kcen/2022/04/solve input-lanjian` | 4.9 ± 1.9 | 2.0 | 10.9 | 1.89 ± 1.57 |
| `kcen/2022/04/solve input-mattcl` | 4.8 ± 1.9 | 1.9 | 14.1 | 1.84 ± 1.53 |
| `kcen/2022/04/solve input-pting` | 5.9 ± 3.5 | 2.0 | 22.3 | 2.28 ± 2.14 |
| `lanjian/day_04 input-aspidites` | 3.6 ± 1.8 | 0.7 | 13.9 | 1.37 ± 1.22 |
| `lanjian/day_04 input-kcen` | 4.3 ± 2.3 | 1.1 | 22.0 | 1.67 ± 1.50 |
| `lanjian/day_04 input-lanjian` | 2.6 ± 1.9 | 0.5 | 18.8 | 1.00 |
| `lanjian/day_04 input-mattcl` | 4.5 ± 1.7 | 0.5 | 11.6 | 1.73 ± 1.41 |
| `lanjian/day_04 input-pting` | 3.2 ± 1.7 | 0.6 | 16.9 | 1.22 ± 1.10 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.2 ± 1.9 | 0.4 | 16.7 | 1.23 ± 1.15 |
| `mattcl-solver/aoc run 4 input-kcen` | 4.5 ± 2.4 | 1.3 | 25.8 | 1.75 ± 1.57 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.1 ± 1.6 | 0.6 | 9.4 | 1.20 ± 1.07 |
| `mattcl-solver/aoc run 4 input-mattcl` | 8.0 ± 9.1 | 1.4 | 64.7 | 3.07 ± 4.15 |
| `mattcl-solver/aoc run 4 input-pting` | 3.9 ± 2.1 | 0.9 | 16.7 | 1.52 ± 1.38 |
| `python pting/day04.py input-aspidites` | 66.8 ± 26.6 | 45.7 | 132.4 | 25.78 ± 21.39 |
| `python pting/day04.py input-kcen` | 57.4 ± 14.8 | 41.6 | 113.4 | 22.14 ± 17.10 |
| `python pting/day04.py input-lanjian` | 64.2 ± 28.4 | 39.2 | 161.1 | 24.78 ± 21.12 |
| `python pting/day04.py input-mattcl` | 74.4 ± 32.1 | 47.5 | 158.7 | 28.71 ± 24.29 |
| `python pting/day04.py input-pting` | 61.9 ± 27.7 | 41.2 | 170.5 | 23.88 ± 20.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
