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
| `lanjian/day_09 input-lanjian` | 5.4 ± 1.3 | 3.4 | 14.0 | 1.25 ± 0.47 |
| `lanjian/day_09 input-mattcl` | 5.4 ± 1.1 | 3.4 | 13.1 | 1.26 ± 0.45 |
| `lanjian/day_09 input-pting` | 5.4 ± 1.4 | 3.4 | 16.0 | 1.25 ± 0.49 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.5 ± 1.4 | 2.7 | 19.7 | 1.05 ± 0.44 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.7 ± 1.1 | 2.6 | 12.0 | 1.10 ± 0.41 |
| `mattcl-solver/aoc run 9 input-pting` | 4.3 ± 1.3 | 2.5 | 16.0 | 1.00 |
| `python pting/day09.py input-lanjian` | 253.3 ± 86.1 | 162.8 | 426.3 | 58.73 ± 26.37 |
| `python pting/day09.py input-mattcl` | 164.6 ± 14.6 | 144.9 | 186.4 | 38.17 ± 11.70 |
| `python pting/day09.py input-pting` | 179.6 ± 22.3 | 154.2 | 223.8 | 41.64 ± 13.26 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
