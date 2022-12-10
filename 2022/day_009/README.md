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
| `lanjian/day_09 input-lanjian` | 5.3 ± 1.5 | 2.5 | 13.1 | 1.38 ± 0.49 |
| `lanjian/day_09 input-mattcl` | 5.1 ± 1.0 | 3.2 | 10.5 | 1.34 ± 0.40 |
| `lanjian/day_09 input-pting` | 7.8 ± 6.7 | 2.7 | 78.7 | 2.05 ± 1.81 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.5 ± 1.4 | 2.8 | 12.4 | 1.17 ± 0.45 |
| `mattcl-solver/aoc run 9 input-mattcl` | 3.9 ± 1.1 | 2.4 | 12.0 | 1.03 ± 0.36 |
| `mattcl-solver/aoc run 9 input-pting` | 3.8 ± 0.8 | 2.2 | 7.9 | 1.00 |
| `python pting/day09.py input-lanjian` | 163.4 ± 15.0 | 141.6 | 198.2 | 42.98 ± 10.03 |
| `python pting/day09.py input-mattcl` | 158.1 ± 14.8 | 139.9 | 193.4 | 41.58 ± 9.73 |
| `python pting/day09.py input-pting` | 171.2 ± 18.2 | 150.3 | 212.6 | 45.02 ± 10.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
