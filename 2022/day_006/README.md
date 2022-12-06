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
| `lanjian/day_06 input-lanjian` | 1.8 ± 1.4 | 0.0 | 13.6 | 1.59 ± 2.00 |
| `lanjian/day_06 input-mattcl` | 1.2 ± 1.5 | 0.0 | 11.8 | 1.04 ± 1.66 |
| `lanjian/day_06 input-pting` | 1.1 ± 1.1 | 0.0 | 11.0 | 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 4.6 ± 1.8 | 1.8 | 19.5 | 4.06 ± 4.36 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.7 ± 1.4 | 0.9 | 10.5 | 3.21 ± 3.45 |
| `mattcl-solver/aoc run 6 input-pting` | 4.2 ± 1.3 | 1.5 | 12.6 | 3.68 ± 3.88 |
| `python pting/day06.py input-lanjian` | 99.5 ± 44.3 | 50.3 | 187.7 | 87.41 ± 96.11 |
| `python pting/day06.py input-mattcl` | 62.3 ± 8.2 | 49.4 | 88.3 | 54.68 ± 55.45 |
| `python pting/day06.py input-pting` | 61.9 ± 11.1 | 44.5 | 90.2 | 54.33 ± 55.49 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
