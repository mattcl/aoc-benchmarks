# Day 9 benchmarks

[link to problem](http://adventofcode.com/2022/day/9)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 9)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_09 input-kcen` | 1.9 ± 0.2 | 1.7 | 6.9 | 1.36 ± 0.24 |
| `lanjian/day_09 input-lanjian` | 1.8 ± 0.1 | 1.6 | 4.2 | 1.32 ± 0.17 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.2 | 1.7 | 4.3 | 1.38 ± 0.20 |
| `lanjian/day_09 input-pting` | 1.8 ± 0.1 | 1.7 | 4.6 | 1.35 ± 0.18 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.4 ± 0.3 | 1.2 | 7.8 | 1.03 ± 0.23 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.2 | 1.2 | 5.1 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.4 ± 0.1 | 1.2 | 4.5 | 1.03 ± 0.15 |
| `mattcl-solver/aoc run 9 input-pting` | 1.4 ± 0.1 | 1.2 | 2.4 | 1.02 ± 0.13 |
| `python pting/day09/day09.py input-kcen` | 78.3 ± 2.3 | 76.2 | 89.5 | 57.55 ± 6.84 |
| `python pting/day09/day09.py input-lanjian` | 74.0 ± 2.0 | 71.9 | 84.2 | 54.36 ± 6.42 |
| `python pting/day09/day09.py input-mattcl` | 75.9 ± 1.0 | 74.4 | 78.6 | 55.80 ± 6.46 |
| `python pting/day09/day09.py input-pting` | 75.4 ± 1.0 | 73.7 | 77.6 | 55.38 ± 6.41 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
