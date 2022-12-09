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
| `lanjian/day_09 input-lanjian` | 5.6 ± 2.6 | 2.9 | 21.0 | 1.23 ± 0.78 |
| `lanjian/day_09 input-mattcl` | 6.0 ± 2.9 | 2.8 | 26.0 | 1.33 ± 0.86 |
| `lanjian/day_09 input-pting` | 5.4 ± 2.8 | 2.7 | 22.2 | 1.18 ± 0.81 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.6 ± 2.3 | 2.0 | 30.3 | 1.02 ± 0.67 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.6 ± 2.0 | 1.7 | 16.8 | 1.00 |
| `mattcl-solver/aoc run 9 input-pting` | 5.4 ± 2.8 | 2.3 | 25.9 | 1.19 ± 0.80 |
| `python pting/day09.py input-lanjian` | 182.1 ± 32.1 | 147.7 | 261.9 | 40.01 ± 18.89 |
| `python pting/day09.py input-mattcl` | 187.7 ± 29.5 | 153.8 | 258.1 | 41.23 ± 19.19 |
| `python pting/day09.py input-pting` | 181.2 ± 21.9 | 135.4 | 235.9 | 39.80 ± 18.09 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
