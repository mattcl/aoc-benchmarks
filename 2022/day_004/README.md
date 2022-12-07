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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 21.1 ± 7.0 | 13.2 | 43.3 | 8.59 ± 4.44 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 21.1 ± 6.3 | 13.1 | 44.1 | 8.59 ± 4.26 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.1 ± 5.6 | 13.3 | 47.2 | 9.40 ± 4.38 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 21.2 ± 5.7 | 12.8 | 31.0 | 8.62 ± 4.15 |
| `aspidites-solver/aoc -i input-pting -d 4` | 17.9 ± 5.1 | 13.2 | 28.9 | 7.28 ± 3.57 |
| `kcen/2022/04/solve input-aspidites` | 4.7 ± 1.6 | 2.2 | 13.5 | 1.91 ± 0.99 |
| `kcen/2022/04/solve input-kcen` | 4.8 ± 1.4 | 2.1 | 12.5 | 1.95 ± 0.97 |
| `kcen/2022/04/solve input-lanjian` | 4.3 ± 1.2 | 2.2 | 8.8 | 1.73 ± 0.84 |
| `kcen/2022/04/solve input-mattcl` | 4.3 ± 1.6 | 2.2 | 20.7 | 1.77 ± 0.97 |
| `kcen/2022/04/solve input-pting` | 5.0 ± 1.3 | 2.6 | 9.4 | 2.05 ± 0.97 |
| `lanjian/day_04 input-aspidites` | 2.5 ± 1.1 | 0.9 | 9.9 | 1.02 ± 0.61 |
| `lanjian/day_04 input-kcen` | 2.5 ± 1.0 | 0.8 | 9.6 | 1.00 |
| `lanjian/day_04 input-lanjian` | 2.7 ± 1.3 | 0.8 | 15.6 | 1.09 ± 0.70 |
| `lanjian/day_04 input-mattcl` | 3.2 ± 1.6 | 1.0 | 10.6 | 1.32 ± 0.83 |
| `lanjian/day_04 input-pting` | 3.5 ± 1.4 | 0.9 | 13.2 | 1.41 ± 0.79 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.5 ± 1.2 | 1.0 | 8.6 | 1.42 ± 0.76 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.1 ± 1.3 | 1.0 | 17.9 | 1.26 ± 0.72 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.4 ± 1.8 | 0.9 | 15.5 | 1.40 ± 0.93 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.5 ± 1.5 | 1.1 | 14.3 | 1.43 ± 0.85 |
| `mattcl-solver/aoc run 4 input-pting` | 3.1 ± 1.4 | 0.9 | 14.2 | 1.27 ± 0.75 |
| `python pting/day04.py input-aspidites` | 59.9 ± 9.3 | 43.8 | 92.9 | 24.36 ± 10.40 |
| `python pting/day04.py input-kcen` | 57.0 ± 9.8 | 43.1 | 93.3 | 23.15 ± 10.04 |
| `python pting/day04.py input-lanjian` | 54.1 ± 4.7 | 46.0 | 70.1 | 21.99 ± 8.96 |
| `python pting/day04.py input-mattcl` | 62.4 ± 11.4 | 45.7 | 95.8 | 25.37 ± 11.11 |
| `python pting/day04.py input-pting` | 78.6 ± 39.3 | 46.5 | 262.3 | 31.92 ± 20.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
