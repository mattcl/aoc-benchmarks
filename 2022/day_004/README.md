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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.0 ± 2.1 | 21.8 | 34.4 | 18.19 ± 6.53 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 23.6 ± 3.1 | 21.9 | 34.5 | 18.69 ± 6.93 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.9 ± 3.4 | 22.1 | 44.1 | 18.95 ± 7.10 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 23.2 ± 2.2 | 22.0 | 33.5 | 18.38 ± 6.62 |
| `aspidites-solver/aoc -i input-pting -d 4` | 23.8 ± 3.2 | 21.9 | 34.2 | 18.87 ± 7.02 |
| `kcen/2022/04/solve input-aspidites` | 2.9 ± 0.5 | 2.0 | 6.2 | 2.31 ± 0.90 |
| `kcen/2022/04/solve input-kcen` | 2.8 ± 0.7 | 1.9 | 8.9 | 2.20 ± 0.93 |
| `kcen/2022/04/solve input-lanjian` | 3.1 ± 0.9 | 2.0 | 10.0 | 2.44 ± 1.09 |
| `kcen/2022/04/solve input-mattcl` | 2.7 ± 0.5 | 1.9 | 6.9 | 2.16 ± 0.86 |
| `kcen/2022/04/solve input-pting` | 3.2 ± 1.6 | 1.9 | 19.5 | 2.54 ± 1.52 |
| `lanjian/day_04 input-aspidites` | 1.6 ± 0.4 | 0.9 | 4.2 | 1.24 ± 0.52 |
| `lanjian/day_04 input-kcen` | 1.5 ± 0.4 | 0.8 | 3.7 | 1.20 ± 0.50 |
| `lanjian/day_04 input-lanjian` | 1.5 ± 0.6 | 0.8 | 8.9 | 1.21 ± 0.64 |
| `lanjian/day_04 input-mattcl` | 1.6 ± 0.4 | 0.9 | 5.5 | 1.24 ± 0.53 |
| `lanjian/day_04 input-pting` | 1.3 ± 0.6 | 0.9 | 11.2 | 1.05 ± 0.62 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.3 ± 0.4 | 0.7 | 10.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.5 ± 0.4 | 0.8 | 5.3 | 1.21 ± 0.53 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.7 ± 0.5 | 0.8 | 7.7 | 1.31 ± 0.61 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.4 | 0.8 | 6.5 | 1.16 ± 0.52 |
| `mattcl-solver/aoc run 4 input-pting` | 1.4 ± 0.6 | 0.7 | 11.4 | 1.08 ± 0.59 |
| `python pting/day04.py input-aspidites` | 37.2 ± 4.2 | 31.5 | 52.2 | 29.49 ± 10.77 |
| `python pting/day04.py input-kcen` | 34.6 ± 2.3 | 30.0 | 41.4 | 27.39 ± 9.69 |
| `python pting/day04.py input-lanjian` | 35.9 ± 4.0 | 29.9 | 49.7 | 28.48 ± 10.37 |
| `python pting/day04.py input-mattcl` | 34.5 ± 4.0 | 29.5 | 50.0 | 27.35 ± 10.00 |
| `python pting/day04.py input-pting` | 33.3 ± 2.2 | 29.7 | 41.3 | 26.37 ± 9.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
