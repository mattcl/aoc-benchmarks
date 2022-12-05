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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 12.7 ± 1.9 | 11.7 | 22.7 | 12.38 ± 3.87 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 12.7 ± 1.2 | 11.6 | 22.4 | 12.40 ± 3.61 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 12.4 ± 0.5 | 11.8 | 14.8 | 12.08 ± 3.35 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 13.3 ± 2.8 | 11.8 | 24.3 | 12.99 ± 4.48 |
| `aspidites-solver/aoc -i input-pting -d 4` | 12.9 ± 1.0 | 11.9 | 24.4 | 12.53 ± 3.58 |
| `kcen/2022/04/solve input-aspidites` | 2.8 ± 0.7 | 1.9 | 6.2 | 2.74 ± 1.00 |
| `kcen/2022/04/solve input-kcen` | 2.3 ± 0.4 | 1.7 | 7.0 | 2.20 ± 0.75 |
| `kcen/2022/04/solve input-lanjian` | 2.5 ± 0.5 | 1.8 | 5.1 | 2.48 ± 0.84 |
| `kcen/2022/04/solve input-mattcl` | 2.7 ± 0.8 | 1.8 | 11.7 | 2.58 ± 1.03 |
| `kcen/2022/04/solve input-pting` | 3.1 ± 0.7 | 2.0 | 9.3 | 3.06 ± 1.07 |
| `lanjian/day_04 input-aspidites` | 1.0 ± 0.3 | 0.7 | 4.6 | 1.00 |
| `lanjian/day_04 input-kcen` | 1.1 ± 0.2 | 0.7 | 2.8 | 1.05 ± 0.36 |
| `lanjian/day_04 input-lanjian` | 1.3 ± 0.4 | 0.7 | 5.5 | 1.30 ± 0.53 |
| `lanjian/day_04 input-mattcl` | 1.4 ± 0.5 | 0.8 | 8.6 | 1.40 ± 0.65 |
| `lanjian/day_04 input-pting` | 1.1 ± 0.3 | 0.7 | 5.4 | 1.07 ± 0.43 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.1 ± 0.4 | 0.6 | 5.5 | 1.04 ± 0.52 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.1 ± 0.3 | 0.7 | 6.2 | 1.07 ± 0.42 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.3 ± 0.4 | 0.7 | 5.2 | 1.29 ± 0.51 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.8 | 0.7 | 11.2 | 1.42 ± 0.83 |
| `mattcl-solver/aoc run 4 input-pting` | 1.2 ± 0.4 | 0.7 | 3.8 | 1.13 ± 0.48 |
| `python pting/day04.py input-aspidites` | 35.5 ± 3.7 | 30.1 | 46.6 | 34.59 ± 10.18 |
| `python pting/day04.py input-kcen` | 34.0 ± 2.7 | 30.2 | 41.2 | 33.14 ± 9.48 |
| `python pting/day04.py input-lanjian` | 35.2 ± 4.2 | 30.5 | 52.9 | 34.30 ± 10.29 |
| `python pting/day04.py input-mattcl` | 40.4 ± 6.6 | 31.4 | 54.1 | 39.37 ± 12.61 |
| `python pting/day04.py input-pting` | 39.7 ± 8.1 | 31.2 | 74.6 | 38.66 ± 13.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
