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
| `lanjian/day_06 input-lanjian` | 2.8 ± 1.7 | 0.6 | 16.1 | 1.20 ± 0.97 |
| `lanjian/day_06 input-mattcl` | 3.1 ± 2.1 | 0.8 | 15.7 | 1.34 ± 1.14 |
| `lanjian/day_06 input-pting` | 3.8 ± 2.0 | 0.7 | 21.6 | 1.62 ± 1.24 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.9 ± 1.4 | 0.9 | 17.4 | 1.23 ± 0.89 |
| `mattcl-solver/aoc run 6 input-mattcl` | 2.3 ± 1.3 | 0.8 | 9.2 | 1.00 |
| `mattcl-solver/aoc run 6 input-pting` | 2.7 ± 1.6 | 0.7 | 13.9 | 1.14 ± 0.91 |
| `python pting/day06.py input-lanjian` | 57.4 ± 14.8 | 37.5 | 116.4 | 24.52 ± 14.66 |
| `python pting/day06.py input-mattcl` | 67.8 ± 24.6 | 47.1 | 169.1 | 28.97 ± 18.82 |
| `python pting/day06.py input-pting` | 69.2 ± 24.8 | 50.7 | 158.1 | 29.55 ± 19.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
