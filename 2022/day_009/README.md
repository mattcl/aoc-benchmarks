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
| `lanjian/day_09 input-kcen` | 1.9 ± 0.1 | 1.7 | 4.2 | 1.31 ± 0.16 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 3.8 | 1.29 ± 0.16 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 4.0 | 1.30 ± 0.16 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.2 | 1.8 | 4.4 | 1.32 ± 0.17 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.2 | 1.3 | 5.6 | 1.01 ± 0.15 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.5 ± 0.1 | 1.3 | 3.8 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.4 | 1.01 ± 0.13 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.4 | 3.6 | 1.03 ± 0.14 |
| `python pting/day09/day09.py input-kcen` | 78.8 ± 2.0 | 76.7 | 89.5 | 53.76 ± 5.63 |
| `python pting/day09/day09.py input-lanjian` | 76.0 ± 3.1 | 72.9 | 85.5 | 51.89 ± 5.67 |
| `python pting/day09/day09.py input-mattcl` | 76.9 ± 2.4 | 74.7 | 89.7 | 52.45 ± 5.56 |
| `python pting/day09/day09.py input-pting` | 76.7 ± 2.8 | 74.3 | 89.2 | 52.32 ± 5.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
