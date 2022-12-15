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
| `lanjian/day_14 input-lanjian` | 3.5 ± 0.2 | 3.3 | 5.0 | 3.67 ± 0.30 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 9.6 | 5.61 ± 0.45 |
| `lanjian/day_14 input-pting` | 5.3 ± 0.2 | 5.0 | 8.0 | 5.48 ± 0.45 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 1.4 | 1.02 ± 0.10 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 1.8 | 1.09 ± 0.10 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 1.5 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 163.1 ± 2.2 | 159.6 | 168.9 | 170.26 ± 11.67 |
| `python pting/day14/day14.py input-mattcl` | 165.1 ± 1.5 | 163.3 | 168.5 | 172.31 ± 11.69 |
| `python pting/day14/day14.py input-pting` | 165.1 ± 2.5 | 162.1 | 170.6 | 172.33 ± 11.87 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
