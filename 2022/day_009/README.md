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
| `lanjian/day_09 input-kcen` | 1.9 ± 0.1 | 1.8 | 3.6 | 1.35 ± 0.10 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.3 | 1.8 | 10.1 | 1.33 ± 0.20 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 3.9 | 1.34 ± 0.10 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.8 | 2.6 | 1.34 ± 0.09 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.1 | 1.3 | 2.7 | 1.04 ± 0.08 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 2.1 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.4 | 1.9 | 1.02 ± 0.07 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 2.0 | 1.02 ± 0.07 |
| `python pting/day09/day09.py input-kcen` | 77.5 ± 0.9 | 76.2 | 80.8 | 53.89 ± 2.85 |
| `python pting/day09/day09.py input-lanjian` | 74.7 ± 1.4 | 73.4 | 79.7 | 51.93 ± 2.86 |
| `python pting/day09/day09.py input-mattcl` | 77.1 ± 3.6 | 74.6 | 87.0 | 53.57 ± 3.75 |
| `python pting/day09/day09.py input-pting` | 75.6 ± 1.2 | 74.4 | 81.4 | 52.56 ± 2.85 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
