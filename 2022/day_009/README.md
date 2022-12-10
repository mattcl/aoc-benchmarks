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
| `lanjian/day_09 input-lanjian` | 3.9 ± 0.7 | 2.3 | 8.8 | 1.18 ± 0.34 |
| `lanjian/day_09 input-mattcl` | 4.0 ± 0.8 | 2.4 | 7.9 | 1.22 ± 0.36 |
| `lanjian/day_09 input-pting` | 3.9 ± 0.8 | 2.4 | 7.9 | 1.17 ± 0.35 |
| `mattcl-solver/aoc run 9 input-lanjian` | 3.4 ± 1.2 | 1.8 | 15.6 | 1.03 ± 0.42 |
| `mattcl-solver/aoc run 9 input-mattcl` | 3.4 ± 0.8 | 1.9 | 8.4 | 1.03 ± 0.33 |
| `mattcl-solver/aoc run 9 input-pting` | 3.3 ± 0.7 | 1.8 | 7.6 | 1.00 |
| `python pting/day09.py input-lanjian` | 129.0 ± 15.3 | 112.8 | 185.7 | 39.14 ± 9.82 |
| `python pting/day09.py input-mattcl` | 126.8 ± 9.9 | 112.5 | 148.4 | 38.47 ± 9.02 |
| `python pting/day09.py input-pting` | 129.2 ± 8.0 | 119.8 | 150.4 | 39.18 ± 9.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
