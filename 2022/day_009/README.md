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
| `lanjian/day_09 input-lanjian` | 5.0 ± 1.1 | 2.7 | 10.3 | 1.28 ± 0.43 |
| `lanjian/day_09 input-mattcl` | 4.8 ± 1.4 | 2.7 | 12.8 | 1.22 ± 0.48 |
| `lanjian/day_09 input-pting` | 6.5 ± 4.9 | 3.1 | 48.0 | 1.65 ± 1.32 |
| `mattcl-solver/aoc run 9 input-lanjian` | 3.9 ± 1.0 | 2.2 | 13.1 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.5 ± 1.1 | 2.5 | 12.1 | 1.14 ± 0.40 |
| `mattcl-solver/aoc run 9 input-pting` | 4.0 ± 1.0 | 2.2 | 10.2 | 1.03 ± 0.37 |
| `python pting/day09.py input-lanjian` | 158.7 ± 14.7 | 143.0 | 198.9 | 40.48 ± 10.87 |
| `python pting/day09.py input-mattcl` | 171.6 ± 17.1 | 151.9 | 210.9 | 43.78 ± 11.87 |
| `python pting/day09.py input-pting` | 197.8 ± 37.7 | 163.4 | 295.5 | 50.44 ± 15.94 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
