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
| `lanjian/day_08 input-lanjian` | 3.8 ± 1.5 | 1.9 | 19.6 | 1.37 ± 0.81 |
| `lanjian/day_08 input-mattcl` | 3.7 ± 1.0 | 2.0 | 9.5 | 1.32 ± 0.69 |
| `lanjian/day_08 input-pting` | 4.2 ± 1.4 | 2.2 | 17.0 | 1.52 ± 0.84 |
| `mattcl-solver/aoc run 8 input-lanjian` | 2.8 ± 1.3 | 1.0 | 9.7 | 1.00 |
| `mattcl-solver/aoc run 8 input-mattcl` | 2.9 ± 1.2 | 1.1 | 12.7 | 1.04 ± 0.64 |
| `mattcl-solver/aoc run 8 input-pting` | 2.8 ± 2.4 | 0.9 | 57.2 | 1.02 ± 0.99 |
| `python pting/day08.py input-lanjian` | 647.1 ± 23.8 | 612.8 | 688.3 | 231.08 ± 104.11 |
| `python pting/day08.py input-mattcl` | 669.1 ± 43.1 | 616.4 | 759.7 | 238.97 ± 108.39 |
| `python pting/day08.py input-pting` | 677.6 ± 50.4 | 631.1 | 771.7 | 241.99 ± 110.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1835</pre>|<pre>263670</pre>|
|input-mattcl|<pre>1859</pre>|<pre>332640</pre>|
|input-pting|<pre>1546</pre>|<pre>519064</pre>|
