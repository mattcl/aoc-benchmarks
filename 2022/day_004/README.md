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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.4 ± 7.2 | 13.3 | 38.8 | 7.30 ± 3.48 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 25.7 ± 11.4 | 13.5 | 87.3 | 8.36 ± 4.75 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.2 ± 6.7 | 13.3 | 41.5 | 7.57 ± 3.44 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 21.0 ± 6.5 | 13.3 | 39.5 | 6.84 ± 3.20 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.3 ± 7.1 | 13.2 | 44.4 | 7.25 ± 3.44 |
| `kcen/2022/04/solve input-aspidites` | 5.5 ± 2.3 | 2.9 | 18.6 | 1.78 ± 0.99 |
| `kcen/2022/04/solve input-kcen` | 6.5 ± 5.0 | 2.3 | 47.3 | 2.12 ± 1.79 |
| `kcen/2022/04/solve input-lanjian` | 4.5 ± 1.8 | 2.2 | 14.7 | 1.47 ± 0.77 |
| `kcen/2022/04/solve input-mattcl` | 5.9 ± 2.6 | 2.7 | 24.8 | 1.92 ± 1.09 |
| `kcen/2022/04/solve input-pting` | 4.8 ± 1.7 | 2.5 | 14.8 | 1.55 ± 0.77 |
| `lanjian/day_04 input-aspidites` | 3.3 ± 1.6 | 1.3 | 23.1 | 1.07 ± 0.65 |
| `lanjian/day_04 input-kcen` | 3.1 ± 1.1 | 1.2 | 10.5 | 1.00 |
| `lanjian/day_04 input-lanjian` | 3.8 ± 1.6 | 1.3 | 24.6 | 1.23 ± 0.67 |
| `lanjian/day_04 input-mattcl` | 6.8 ± 5.4 | 2.2 | 43.0 | 2.21 ± 1.93 |
| `lanjian/day_04 input-pting` | 3.4 ± 1.8 | 1.2 | 17.1 | 1.12 ± 0.70 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.2 ± 1.3 | 1.0 | 9.3 | 1.05 ± 0.56 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.5 ± 2.8 | 1.3 | 50.7 | 1.15 ± 1.01 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.4 ± 1.2 | 1.5 | 14.6 | 1.09 ± 0.56 |
| `mattcl-solver/aoc run 4 input-mattcl` | 4.5 ± 3.0 | 1.5 | 21.7 | 1.48 ± 1.12 |
| `mattcl-solver/aoc run 4 input-pting` | 3.1 ± 1.3 | 1.3 | 11.4 | 1.01 ± 0.56 |
| `python pting/day04.py input-aspidites` | 63.7 ± 9.7 | 50.0 | 89.2 | 20.74 ± 7.94 |
| `python pting/day04.py input-kcen` | 74.5 ± 13.4 | 55.3 | 112.0 | 24.27 ± 9.57 |
| `python pting/day04.py input-lanjian` | 59.9 ± 8.2 | 47.1 | 81.6 | 19.50 ± 7.36 |
| `python pting/day04.py input-mattcl` | 70.2 ± 11.2 | 49.1 | 107.8 | 22.86 ± 8.82 |
| `python pting/day04.py input-pting` | 70.3 ± 8.9 | 56.2 | 112.0 | 22.91 ± 8.56 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
