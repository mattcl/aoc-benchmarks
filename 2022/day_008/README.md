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
| `lanjian/day_08 input-lanjian` | 18.0 ± 15.5 | 3.5 | 103.1 | 5.17 ± 5.84 |
| `lanjian/day_08 input-mattcl` | 3.6 ± 1.6 | 1.5 | 20.2 | 1.05 ± 0.90 |
| `lanjian/day_08 input-pting` | 4.2 ± 1.4 | 1.6 | 15.0 | 1.20 ± 0.97 |
| `mattcl-solver/aoc run 8 input-lanjian` | 3.5 ± 2.6 | 0.8 | 17.1 | 1.00 |
| `mattcl-solver/aoc run 8 input-mattcl` | 3.6 ± 2.3 | 1.3 | 30.6 | 1.03 ± 1.01 |
| `mattcl-solver/aoc run 8 input-pting` | 3.6 ± 1.7 | 1.5 | 17.4 | 1.04 ± 0.91 |
| `python pting/day08.py input-lanjian` | 675.4 ± 37.1 | 610.0 | 720.4 | 193.78 ± 143.10 |
| `python pting/day08.py input-mattcl` | 682.1 ± 51.9 | 626.9 | 788.9 | 195.69 ± 144.88 |
| `python pting/day08.py input-pting` | 694.0 ± 35.8 | 622.8 | 749.2 | 199.09 ± 146.98 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1835</pre>|<pre>263670</pre>|
|input-mattcl|<pre>1859</pre>|<pre>332640</pre>|
