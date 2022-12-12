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
| `lanjian/day_09 input-kcen` | 1.9 ± 0.1 | 1.8 | 4.4 | 1.31 ± 0.14 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.2 | 1.7 | 5.9 | 1.31 ± 0.18 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 2.4 | 1.32 ± 0.14 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.8 | 3.2 | 1.32 ± 0.14 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.1 | 1.3 | 2.1 | 1.01 ± 0.11 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 5.6 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 4.7 | 1.02 ± 0.12 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 2.8 | 1.01 ± 0.11 |
| `python pting/day09/day09.py input-kcen` | 79.0 ± 4.5 | 76.8 | 105.8 | 54.72 ± 5.92 |
| `python pting/day09/day09.py input-lanjian` | 74.5 ± 2.0 | 72.8 | 84.8 | 51.61 ± 4.92 |
| `python pting/day09/day09.py input-mattcl` | 75.8 ± 0.9 | 74.6 | 79.4 | 52.50 ± 4.85 |
| `python pting/day09/day09.py input-pting` | 76.7 ± 2.6 | 74.6 | 86.7 | 53.09 ± 5.20 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
