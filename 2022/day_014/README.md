# Day 14 benchmarks

[link to problem](http://adventofcode.com/2022/day/14)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 14)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_14 input-lanjian` | 3.6 ± 0.2 | 3.4 | 5.4 | 3.69 ± 0.37 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 7.2 | 5.62 ± 0.51 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 7.3 | 5.42 ± 0.49 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 2.9 | 1.06 ± 0.13 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.1 ± 0.1 | 0.9 | 1.8 | 1.09 ± 0.11 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 2.7 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 163.3 ± 2.0 | 161.0 | 168.5 | 169.19 ± 14.30 |
| `python pting/day14/day14.py input-mattcl` | 168.4 ± 2.5 | 165.1 | 173.9 | 174.51 ± 14.82 |
| `python pting/day14/day14.py input-pting` | 164.7 ± 1.9 | 161.7 | 167.9 | 170.68 ± 14.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
