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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 20.1 ± 8.2 | 12.7 | 44.0 | 11.31 ± 8.82 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.0 ± 8.6 | 12.1 | 50.1 | 11.30 ± 8.96 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 17.9 ± 7.8 | 12.2 | 50.4 | 10.10 ± 8.04 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.5 ± 8.1 | 12.2 | 40.1 | 10.99 ± 8.63 |
| `aspidites-solver/aoc -i input-pting -d 4` | 17.6 ± 7.0 | 11.9 | 42.6 | 9.95 ± 7.70 |
| `kcen/2022/04/solve input-aspidites` | 4.5 ± 2.8 | 1.3 | 22.5 | 2.57 ± 2.33 |
| `kcen/2022/04/solve input-kcen` | 4.6 ± 2.8 | 1.7 | 17.4 | 2.61 ± 2.33 |
| `kcen/2022/04/solve input-lanjian` | 3.8 ± 1.8 | 1.3 | 14.6 | 2.14 ± 1.76 |
| `kcen/2022/04/solve input-mattcl` | 4.7 ± 2.8 | 1.8 | 18.2 | 2.63 ± 2.36 |
| `kcen/2022/04/solve input-pting` | 5.0 ± 2.8 | 1.8 | 15.4 | 2.81 ± 2.44 |
| `lanjian/day_04 input-aspidites` | 2.1 ± 1.6 | 0.1 | 20.7 | 1.16 ± 1.18 |
| `lanjian/day_04 input-kcen` | 2.4 ± 1.9 | 0.3 | 12.9 | 1.34 ± 1.41 |
| `lanjian/day_04 input-lanjian` | 2.4 ± 2.2 | 0.1 | 22.8 | 1.36 ± 1.52 |
| `lanjian/day_04 input-mattcl` | 2.3 ± 1.7 | 0.3 | 12.5 | 1.30 ± 1.28 |
| `lanjian/day_04 input-pting` | 3.4 ± 2.8 | 0.2 | 29.7 | 1.91 ± 2.01 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.9 ± 2.1 | 0.3 | 16.1 | 1.64 ± 1.59 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.8 ± 1.2 | 0.0 | 7.4 | 1.00 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.8 ± 1.8 | 0.3 | 11.5 | 1.56 ± 1.44 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.6 ± 1.6 | 0.2 | 10.6 | 1.47 ± 1.34 |
| `mattcl-solver/aoc run 4 input-pting` | 3.1 ± 1.8 | 0.6 | 16.8 | 1.73 ± 1.54 |
| `python pting/day04.py input-aspidites` | 54.6 ± 20.0 | 39.8 | 154.8 | 30.76 ± 23.36 |
| `python pting/day04.py input-kcen` | 58.9 ± 20.7 | 43.8 | 145.5 | 33.23 ± 24.99 |
| `python pting/day04.py input-lanjian` | 54.9 ± 19.4 | 43.4 | 136.7 | 30.96 ± 23.33 |
| `python pting/day04.py input-mattcl` | 57.9 ± 24.2 | 40.6 | 173.8 | 32.63 ± 25.63 |
| `python pting/day04.py input-pting` | 145.1 ± 94.8 | 54.1 | 360.2 | 81.80 ± 76.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
