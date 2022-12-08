# Day 8 benchmarks

[link to problem](http://adventofcode.com/2022/day/8)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 8)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_08 input-lanjian` | 4.0 ± 1.1 | 2.2 | 17.9 | 1.20 ± 0.57 |
| `lanjian/day_08 input-mattcl` | 4.4 ± 1.8 | 2.7 | 30.0 | 1.34 ± 0.75 |
| `lanjian/day_08 input-pting` | 4.3 ± 1.8 | 2.3 | 21.3 | 1.31 ± 0.73 |
| `mattcl-solver/aoc run 8 input-lanjian` | 3.3 ± 1.2 | 1.5 | 13.7 | 1.00 |
| `mattcl-solver/aoc run 8 input-mattcl` | 3.6 ± 1.2 | 1.7 | 15.9 | 1.09 ± 0.55 |
| `mattcl-solver/aoc run 8 input-pting` | 3.3 ± 1.0 | 1.5 | 11.3 | 1.01 ± 0.49 |
| `python pting/day08.py input-lanjian` | 662.0 ± 29.9 | 607.1 | 702.2 | 201.06 ± 76.55 |
| `python pting/day08.py input-mattcl` | 656.6 ± 28.0 | 612.4 | 692.1 | 199.42 ± 75.86 |
| `python pting/day08.py input-pting` | 677.4 ± 59.6 | 610.4 | 806.8 | 205.75 ± 79.86 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1835</pre>|<pre>263670</pre>|
|input-mattcl|<pre>1859</pre>|<pre>332640</pre>|
|input-pting|<pre>1546</pre>|<pre>519064</pre>|
