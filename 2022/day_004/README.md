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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 15.3 ± 3.8 | 12.6 | 29.3 | 9.40 ± 5.68 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 15.6 ± 4.0 | 12.9 | 27.4 | 9.58 ± 5.82 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 27.6 ± 12.3 | 13.0 | 65.1 | 16.92 ± 12.01 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 16.9 ± 5.0 | 12.6 | 30.6 | 10.38 ± 6.48 |
| `aspidites-solver/aoc -i input-pting -d 4` | 16.6 ± 4.6 | 12.8 | 29.3 | 10.20 ± 6.29 |
| `kcen/2022/04/solve input-aspidites` | 3.2 ± 1.1 | 1.8 | 9.8 | 1.98 ± 1.29 |
| `kcen/2022/04/solve input-kcen` | 3.2 ± 1.0 | 1.6 | 7.3 | 1.98 ± 1.25 |
| `kcen/2022/04/solve input-lanjian` | 3.8 ± 2.1 | 1.6 | 22.1 | 2.33 ± 1.82 |
| `kcen/2022/04/solve input-mattcl` | 4.1 ± 1.2 | 1.9 | 11.0 | 2.54 ± 1.59 |
| `kcen/2022/04/solve input-pting` | 3.7 ± 1.1 | 1.6 | 13.7 | 2.27 ± 1.42 |
| `lanjian/day_04 input-aspidites` | 1.9 ± 0.8 | 0.6 | 7.1 | 1.16 ± 0.82 |
| `lanjian/day_04 input-kcen` | 2.0 ± 1.0 | 0.6 | 8.4 | 1.24 ± 0.92 |
| `lanjian/day_04 input-lanjian` | 2.1 ± 1.0 | 0.6 | 9.6 | 1.30 ± 0.96 |
| `lanjian/day_04 input-mattcl` | 2.6 ± 1.7 | 0.7 | 31.5 | 1.59 ± 1.35 |
| `lanjian/day_04 input-pting` | 1.9 ± 0.9 | 0.5 | 6.2 | 1.15 ± 0.83 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.6 ± 0.9 | 0.5 | 10.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.1 ± 1.2 | 0.6 | 11.4 | 1.26 ± 1.01 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.4 ± 1.0 | 0.7 | 7.5 | 1.46 ± 1.01 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.0 ± 1.3 | 0.7 | 12.6 | 1.84 ± 1.30 |
| `mattcl-solver/aoc run 4 input-pting` | 2.0 ± 0.7 | 0.5 | 5.2 | 1.23 ± 0.82 |
| `python pting/day04.py input-aspidites` | 48.3 ± 6.3 | 38.9 | 66.2 | 29.65 ± 16.78 |
| `python pting/day04.py input-kcen` | 72.5 ± 28.6 | 44.2 | 152.3 | 44.45 ± 30.12 |
| `python pting/day04.py input-lanjian` | 49.5 ± 6.3 | 41.1 | 66.9 | 30.39 ± 17.18 |
| `python pting/day04.py input-mattcl` | 50.5 ± 5.3 | 40.2 | 64.2 | 30.94 ± 17.36 |
| `python pting/day04.py input-pting` | 47.3 ± 6.8 | 37.4 | 74.1 | 29.03 ± 16.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
