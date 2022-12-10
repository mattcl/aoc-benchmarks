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
| `lanjian/day_09 input-lanjian` | 4.3 ± 1.1 | 2.8 | 12.6 | 1.21 ± 0.44 |
| `lanjian/day_09 input-mattcl` | 5.3 ± 1.8 | 3.0 | 20.6 | 1.49 ± 0.63 |
| `lanjian/day_09 input-pting` | 5.0 ± 2.1 | 2.9 | 36.0 | 1.40 ± 0.69 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.3 ± 1.2 | 2.3 | 16.9 | 1.20 ± 0.46 |
| `mattcl-solver/aoc run 9 input-mattcl` | 3.6 ± 0.9 | 1.9 | 11.0 | 1.00 |
| `mattcl-solver/aoc run 9 input-pting` | 4.0 ± 1.1 | 2.4 | 14.1 | 1.13 ± 0.42 |
| `python pting/day09.py input-lanjian` | 157.0 ± 15.2 | 136.8 | 193.2 | 43.86 ± 11.99 |
| `python pting/day09.py input-mattcl` | 170.8 ± 20.9 | 147.7 | 213.4 | 47.74 ± 13.52 |
| `python pting/day09.py input-pting` | 158.6 ± 11.3 | 140.1 | 183.0 | 44.33 ± 11.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
