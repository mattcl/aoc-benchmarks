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
| `lanjian/day_09 input-lanjian` | 4.2 ± 1.1 | 2.7 | 17.5 | 1.18 ± 0.50 |
| `lanjian/day_09 input-mattcl` | 4.2 ± 1.0 | 2.3 | 9.1 | 1.17 ± 0.47 |
| `lanjian/day_09 input-pting` | 4.6 ± 1.2 | 2.7 | 11.2 | 1.27 ± 0.54 |
| `mattcl-solver/aoc run 9 input-lanjian` | 3.8 ± 1.4 | 1.6 | 11.1 | 1.05 ± 0.51 |
| `mattcl-solver/aoc run 9 input-mattcl` | 3.9 ± 2.0 | 1.9 | 24.1 | 1.09 ± 0.65 |
| `mattcl-solver/aoc run 9 input-pting` | 3.6 ± 1.2 | 1.8 | 13.0 | 1.00 |
| `python pting/day09.py input-lanjian` | 158.4 ± 19.8 | 137.8 | 194.9 | 44.21 ± 15.33 |
| `python pting/day09.py input-mattcl` | 204.9 ± 49.9 | 144.8 | 301.8 | 57.17 ± 23.14 |
| `python pting/day09.py input-pting` | 166.1 ± 14.2 | 142.2 | 199.6 | 46.35 ± 15.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
