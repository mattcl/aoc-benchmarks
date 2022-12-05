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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 13.2 ± 1.8 | 12.0 | 24.1 | 10.19 ± 4.83 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 12.6 ± 1.2 | 11.7 | 22.2 | 9.73 ± 4.53 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 12.6 ± 2.0 | 11.7 | 24.5 | 9.71 ± 4.67 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 12.6 ± 1.1 | 11.8 | 24.4 | 9.72 ± 4.50 |
| `aspidites-solver/aoc -i input-pting -d 4` | 13.7 ± 3.2 | 11.8 | 32.7 | 10.54 ± 5.38 |
| `kcen/2022/04/solve input-aspidites` | 3.1 ± 0.6 | 2.0 | 5.8 | 2.41 ± 1.20 |
| `kcen/2022/04/solve input-kcen` | 2.8 ± 0.7 | 1.9 | 6.4 | 2.17 ± 1.11 |
| `kcen/2022/04/solve input-lanjian` | 2.5 ± 0.5 | 1.8 | 5.6 | 1.96 ± 0.97 |
| `kcen/2022/04/solve input-mattcl` | 2.7 ± 0.6 | 1.7 | 7.5 | 2.11 ± 1.07 |
| `kcen/2022/04/solve input-pting` | 2.7 ± 0.6 | 1.8 | 6.1 | 2.07 ± 1.04 |
| `lanjian/day_04 input-aspidites` | 1.3 ± 0.6 | 0.8 | 5.9 | 1.00 |
| `lanjian/day_04 input-kcen` | 1.9 ± 0.5 | 0.9 | 9.8 | 1.45 ± 0.77 |
| `lanjian/day_04 input-lanjian` | 1.9 ± 1.0 | 0.8 | 15.2 | 1.43 ± 0.98 |
| `lanjian/day_04 input-mattcl` | 1.7 ± 0.5 | 0.8 | 4.6 | 1.35 ± 0.73 |
| `lanjian/day_04 input-pting` | 1.5 ± 0.6 | 0.7 | 10.7 | 1.16 ± 0.69 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.5 ± 0.6 | 0.7 | 7.3 | 1.17 ± 0.70 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.6 ± 0.4 | 0.7 | 3.5 | 1.23 ± 0.63 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.5 ± 0.4 | 0.7 | 4.7 | 1.13 ± 0.61 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.4 ± 0.4 | 0.7 | 4.5 | 1.08 ± 0.57 |
| `mattcl-solver/aoc run 4 input-pting` | 1.6 ± 0.5 | 0.8 | 4.5 | 1.25 ± 0.67 |
| `python pting/day04.py input-aspidites` | 39.6 ± 7.8 | 30.8 | 66.8 | 30.52 ± 15.12 |
| `python pting/day04.py input-kcen` | 36.1 ± 3.8 | 29.0 | 49.3 | 27.83 ± 12.99 |
| `python pting/day04.py input-lanjian` | 36.1 ± 3.8 | 31.7 | 48.1 | 27.78 ± 12.97 |
| `python pting/day04.py input-mattcl` | 38.0 ± 5.1 | 31.0 | 57.4 | 29.24 ± 13.86 |
| `python pting/day04.py input-pting` | 35.7 ± 3.5 | 30.1 | 48.1 | 27.49 ± 12.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
