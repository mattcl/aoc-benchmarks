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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.6 ± 2.1 | 21.7 | 33.3 | 20.61 ± 5.77 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 23.0 ± 2.0 | 21.9 | 34.4 | 21.01 ± 5.83 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.1 ± 2.7 | 21.9 | 43.2 | 21.05 ± 6.08 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 23.5 ± 3.7 | 21.7 | 44.6 | 21.43 ± 6.59 |
| `aspidites-solver/aoc -i input-pting -d 4` | 23.0 ± 2.4 | 21.6 | 34.7 | 21.02 ± 5.96 |
| `kcen/2022/04/solve input-aspidites` | 2.4 ± 0.7 | 1.7 | 11.0 | 2.23 ± 0.84 |
| `kcen/2022/04/solve input-kcen` | 2.9 ± 1.0 | 2.0 | 17.8 | 2.67 ± 1.16 |
| `kcen/2022/04/solve input-lanjian` | 2.4 ± 0.6 | 1.6 | 5.4 | 2.23 ± 0.77 |
| `kcen/2022/04/solve input-mattcl` | 2.3 ± 0.4 | 1.6 | 5.1 | 2.11 ± 0.68 |
| `kcen/2022/04/solve input-pting` | 2.1 ± 0.5 | 1.6 | 6.2 | 1.93 ± 0.68 |
| `lanjian/day_04 input-aspidites` | 1.1 ± 0.3 | 0.7 | 2.9 | 1.00 |
| `lanjian/day_04 input-kcen` | 1.5 ± 0.5 | 0.7 | 5.2 | 1.35 ± 0.55 |
| `lanjian/day_04 input-lanjian` | 1.6 ± 0.6 | 0.7 | 10.0 | 1.43 ± 0.66 |
| `lanjian/day_04 input-mattcl` | 1.6 ± 0.5 | 0.6 | 5.8 | 1.45 ± 0.60 |
| `lanjian/day_04 input-pting` | 1.2 ± 0.6 | 0.6 | 9.3 | 1.07 ± 0.59 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.7 ± 0.7 | 0.8 | 9.5 | 1.52 ± 0.75 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.4 ± 0.5 | 0.8 | 5.0 | 1.28 ± 0.53 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.6 ± 0.4 | 0.8 | 3.7 | 1.49 ± 0.55 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.4 | 0.8 | 4.7 | 1.41 ± 0.53 |
| `mattcl-solver/aoc run 4 input-pting` | 1.2 ± 0.3 | 0.8 | 5.5 | 1.05 ± 0.39 |
| `python pting/day04.py input-aspidites` | 36.7 ± 7.0 | 29.8 | 76.6 | 33.52 ± 10.90 |
| `python pting/day04.py input-kcen` | 35.7 ± 3.5 | 30.5 | 49.6 | 32.57 ± 9.17 |
| `python pting/day04.py input-lanjian` | 37.0 ± 5.7 | 31.0 | 57.5 | 33.79 ± 10.33 |
| `python pting/day04.py input-mattcl` | 33.3 ± 3.4 | 29.2 | 44.2 | 30.35 ± 8.57 |
| `python pting/day04.py input-pting` | 35.4 ± 4.7 | 29.6 | 46.2 | 32.29 ± 9.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
