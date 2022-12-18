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
| `lanjian/day_14 input-lanjian` | 3.6 ± 0.1 | 3.4 | 5.1 | 3.60 ± 0.28 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 8.5 | 5.44 ± 0.42 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 7.4 | 5.27 ± 0.42 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 3.1 | 1.03 ± 0.11 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.1 ± 0.1 | 0.9 | 4.2 | 1.09 ± 0.12 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.9 | 1.5 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 163.6 ± 2.3 | 160.4 | 168.3 | 164.83 ± 11.67 |
| `python pting/day14/day14.py input-mattcl` | 167.7 ± 1.7 | 164.4 | 171.0 | 168.89 ± 11.84 |
| `python pting/day14/day14.py input-pting` | 164.3 ± 2.0 | 160.9 | 169.3 | 165.51 ± 11.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
