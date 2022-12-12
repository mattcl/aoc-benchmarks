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
| `lanjian/day_09 input-kcen` | 1.9 ± 0.1 | 1.8 | 3.7 | 1.33 ± 0.17 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.2 | 1.7 | 3.9 | 1.31 ± 0.18 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 3.3 | 1.33 ± 0.16 |
| `lanjian/day_09 input-pting` | 2.0 ± 0.1 | 1.8 | 3.8 | 1.34 ± 0.17 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.2 | 1.3 | 4.3 | 1.02 ± 0.16 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.5 ± 0.2 | 1.3 | 3.5 | 1.02 ± 0.18 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.3 | 1.01 ± 0.14 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.2 | 1.3 | 3.5 | 1.00 |
| `python pting/day09/day09.py input-kcen` | 78.3 ± 2.7 | 76.3 | 90.0 | 53.71 ± 6.18 |
| `python pting/day09/day09.py input-lanjian` | 73.8 ± 0.9 | 72.2 | 76.3 | 50.68 ± 5.59 |
| `python pting/day09/day09.py input-mattcl` | 76.2 ± 1.9 | 74.5 | 86.2 | 52.32 ± 5.89 |
| `python pting/day09/day09.py input-pting` | 76.7 ± 2.1 | 74.5 | 87.3 | 52.64 ± 5.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
