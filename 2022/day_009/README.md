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
| `lanjian/day_09 input-kcen` | 1.9 ± 0.1 | 1.8 | 2.5 | 1.34 ± 0.10 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 3.7 | 1.31 ± 0.10 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 4.0 | 1.36 ± 0.12 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.8 | 3.9 | 1.36 ± 0.11 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.2 | 1.3 | 5.3 | 1.04 ± 0.13 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.3 | 1.03 ± 0.09 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.2 | 1.3 | 7.1 | 1.04 ± 0.15 |
| `python pting/day09/day09.py input-kcen` | 78.4 ± 2.7 | 76.3 | 89.8 | 54.94 ± 3.78 |
| `python pting/day09/day09.py input-lanjian` | 74.8 ± 2.7 | 72.7 | 84.7 | 52.42 ± 3.65 |
| `python pting/day09/day09.py input-mattcl` | 76.4 ± 2.5 | 74.2 | 85.1 | 53.55 ± 3.63 |
| `python pting/day09/day09.py input-pting` | 75.9 ± 2.2 | 73.8 | 87.2 | 53.21 ± 3.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
