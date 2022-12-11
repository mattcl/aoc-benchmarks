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
| `lanjian/day_09 input-lanjian` | 4.2 ± 0.8 | 2.3 | 8.5 | 1.17 ± 0.35 |
| `lanjian/day_09 input-mattcl` | 4.3 ± 1.0 | 2.5 | 10.0 | 1.21 ± 0.39 |
| `lanjian/day_09 input-pting` | 4.3 ± 0.8 | 2.6 | 8.7 | 1.19 ± 0.35 |
| `mattcl-solver/aoc run 9 input-lanjian` | 3.6 ± 0.8 | 1.8 | 8.2 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 3.7 ± 0.8 | 1.9 | 8.3 | 1.03 ± 0.32 |
| `mattcl-solver/aoc run 9 input-pting` | 4.2 ± 1.0 | 2.2 | 9.9 | 1.17 ± 0.38 |
| `python pting/day09.py input-lanjian` | 126.5 ± 10.0 | 116.2 | 157.1 | 35.28 ± 8.25 |
| `python pting/day09.py input-mattcl` | 135.6 ± 9.2 | 119.2 | 154.0 | 37.85 ± 8.71 |
| `python pting/day09.py input-pting` | 127.8 ± 6.9 | 119.8 | 142.8 | 35.66 ± 8.07 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
