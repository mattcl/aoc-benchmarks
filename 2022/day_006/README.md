# Day 6 benchmarks

[link to problem](http://adventofcode.com/2022/day/6)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 6)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_06 input-lanjian` | 1.7 ± 1.0 | 0.5 | 11.6 | 1.00 |
| `lanjian/day_06 input-mattcl` | 2.1 ± 1.4 | 0.3 | 11.6 | 1.26 ± 1.13 |
| `lanjian/day_06 input-pting` | 1.7 ± 1.3 | 0.4 | 12.8 | 1.04 ± 1.01 |
| `mattcl-solver/aoc run 6 input-lanjian` | 3.7 ± 1.2 | 2.3 | 13.1 | 2.26 ± 1.56 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.4 ± 1.0 | 1.8 | 8.2 | 2.07 ± 1.41 |
| `mattcl-solver/aoc run 6 input-pting` | 4.4 ± 1.5 | 2.4 | 11.0 | 2.69 ± 1.88 |
| `python pting/day06.py input-lanjian` | 56.1 ± 8.8 | 44.2 | 92.9 | 33.96 ± 21.55 |
| `python pting/day06.py input-mattcl` | 56.9 ± 9.6 | 38.1 | 93.0 | 34.46 ± 21.98 |
| `python pting/day06.py input-pting` | 55.3 ± 8.1 | 42.6 | 91.8 | 33.46 ± 21.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
