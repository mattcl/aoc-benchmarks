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
| `lanjian/day_06 input-lanjian` | 2.3 ± 0.9 | 0.5 | 8.5 | 1.00 |
| `lanjian/day_06 input-mattcl` | 5.0 ± 5.0 | 0.9 | 43.9 | 2.18 ± 2.33 |
| `lanjian/day_06 input-pting` | 2.3 ± 1.1 | 0.6 | 8.2 | 1.00 ± 0.59 |
| `mattcl-solver/aoc run 6 input-lanjian` | 4.8 ± 1.2 | 2.6 | 11.3 | 2.07 ± 0.95 |
| `mattcl-solver/aoc run 6 input-mattcl` | 4.0 ± 1.1 | 1.9 | 8.0 | 1.73 ± 0.81 |
| `mattcl-solver/aoc run 6 input-pting` | 4.4 ± 1.4 | 2.5 | 18.5 | 1.92 ± 0.94 |
| `python pting/day06.py input-lanjian` | 60.9 ± 8.0 | 50.0 | 82.5 | 26.41 ± 10.51 |
| `python pting/day06.py input-mattcl` | 60.0 ± 9.1 | 44.7 | 91.6 | 26.01 ± 10.55 |
| `python pting/day06.py input-pting` | 58.2 ± 6.8 | 46.2 | 79.3 | 25.23 ± 9.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
