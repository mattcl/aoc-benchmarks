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
| `lanjian/day_09 input-kcen` | 2.0 ± 0.1 | 1.8 | 2.6 | 1.33 ± 0.10 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.8 | 3.7 | 1.31 ± 0.11 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 3.7 | 1.32 ± 0.10 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.8 | 3.7 | 1.32 ± 0.10 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.1 | 1.4 | 3.5 | 1.01 ± 0.09 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.5 ± 0.1 | 1.3 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.3 | 1.01 ± 0.08 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 3.7 | 1.01 ± 0.10 |
| `python pting/day09/day09.py input-kcen` | 78.1 ± 2.9 | 76.1 | 90.3 | 53.05 ± 3.74 |
| `python pting/day09/day09.py input-lanjian` | 74.0 ± 2.2 | 71.7 | 82.5 | 50.27 ± 3.37 |
| `python pting/day09/day09.py input-mattcl` | 76.8 ± 3.1 | 74.4 | 87.4 | 52.15 ± 3.77 |
| `python pting/day09/day09.py input-pting` | 75.5 ± 2.1 | 73.5 | 86.4 | 51.27 ± 3.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
