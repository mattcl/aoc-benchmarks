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
| `lanjian/day_14 input-lanjian` | 3.5 ± 0.1 | 3.3 | 5.3 | 3.74 ± 0.34 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 7.3 | 5.74 ± 0.51 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 6.5 | 5.52 ± 0.49 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 1.6 | 1.05 ± 0.11 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 2.1 | 1.11 ± 0.13 |
| `mattcl-solver/aoc run 14 input-pting` | 0.9 ± 0.1 | 0.8 | 3.1 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 163.1 ± 2.0 | 160.0 | 168.2 | 173.48 ± 14.70 |
| `python pting/day14/day14.py input-mattcl` | 166.3 ± 2.5 | 163.5 | 172.9 | 176.91 ± 15.07 |
| `python pting/day14/day14.py input-pting` | 163.5 ± 1.9 | 161.2 | 169.6 | 173.98 ± 14.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
