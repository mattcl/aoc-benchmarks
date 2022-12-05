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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 35.0 ± 4.3 | 31.9 | 44.3 | 30.22 ± 7.16 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 38.4 ± 5.6 | 32.0 | 53.8 | 33.18 ± 8.29 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 36.8 ± 5.4 | 32.0 | 52.7 | 31.82 ± 7.93 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 35.0 ± 4.6 | 31.9 | 53.1 | 30.25 ± 7.30 |
| `aspidites-solver/aoc -i input-pting -d 4` | 38.1 ± 6.6 | 31.9 | 73.5 | 32.90 ± 8.79 |
| `kcen/2022/04/solve input-aspidites` | 2.5 ± 0.5 | 1.8 | 5.3 | 2.13 ± 0.58 |
| `kcen/2022/04/solve input-kcen` | 2.8 ± 0.6 | 2.0 | 9.5 | 2.46 ± 0.74 |
| `kcen/2022/04/solve input-lanjian` | 2.8 ± 0.8 | 1.9 | 13.5 | 2.39 ± 0.84 |
| `kcen/2022/04/solve input-mattcl` | 2.4 ± 0.4 | 1.8 | 4.9 | 2.09 ± 0.56 |
| `kcen/2022/04/solve input-pting` | 3.4 ± 1.1 | 1.9 | 11.3 | 2.97 ± 1.12 |
| `lanjian/day_04 input-aspidites` | 1.4 ± 0.4 | 0.8 | 3.7 | 1.22 ± 0.43 |
| `lanjian/day_04 input-kcen` | 1.6 ± 0.6 | 0.8 | 7.9 | 1.40 ± 0.61 |
| `lanjian/day_04 input-lanjian` | 1.5 ± 0.4 | 0.8 | 3.6 | 1.30 ± 0.43 |
| `lanjian/day_04 input-mattcl` | 1.2 ± 0.2 | 0.8 | 2.9 | 1.00 |
| `lanjian/day_04 input-pting` | 1.4 ± 0.4 | 0.8 | 5.7 | 1.21 ± 0.44 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.6 ± 0.4 | 0.9 | 3.9 | 1.35 ± 0.43 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.9 ± 0.8 | 0.9 | 9.6 | 1.65 ± 0.77 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.8 ± 0.9 | 0.9 | 10.5 | 1.53 ± 0.81 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.5 | 1.0 | 9.7 | 1.31 ± 0.52 |
| `mattcl-solver/aoc run 4 input-pting` | 1.9 ± 0.5 | 1.0 | 5.9 | 1.68 ± 0.56 |
| `python pting/day04.py input-aspidites` | 34.1 ± 2.1 | 30.7 | 43.0 | 29.51 ± 6.23 |
| `python pting/day04.py input-kcen` | 35.7 ± 3.4 | 30.5 | 52.6 | 30.88 ± 6.91 |
| `python pting/day04.py input-lanjian` | 35.4 ± 4.3 | 30.0 | 49.8 | 30.58 ± 7.23 |
| `python pting/day04.py input-mattcl` | 33.5 ± 3.3 | 30.1 | 54.4 | 28.96 ± 6.53 |
| `python pting/day04.py input-pting` | 35.8 ± 3.7 | 30.5 | 47.5 | 30.98 ± 7.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
