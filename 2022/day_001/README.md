# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 1)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.2 ± 0.5 | 11.4 | 14.6 | 11.79 ± 6.39 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.9 ± 0.7 | 10.9 | 16.8 | 11.51 ± 6.25 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.1 ± 1.4 | 11.1 | 24.7 | 11.69 ± 6.45 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.5 | 11.0 | 14.2 | 11.77 ± 6.38 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.9 ± 0.6 | 10.9 | 14.3 | 11.49 ± 6.23 |
| `kcen/2022/01/solve input-aspidites` | 106.4 ± 8.0 | 93.0 | 123.9 | 103.05 ± 56.19 |
| `kcen/2022/01/solve input-kcen` | 115.6 ± 9.2 | 97.6 | 129.9 | 111.99 ± 61.14 |
| `kcen/2022/01/solve input-lanjian` | 105.2 ± 10.7 | 86.2 | 134.5 | 101.93 ± 56.02 |
| `kcen/2022/01/solve input-mattcl` | 98.2 ± 8.4 | 84.5 | 117.4 | 95.18 ± 52.04 |
| `kcen/2022/01/solve input-pting` | 98.4 ± 6.8 | 89.7 | 123.7 | 95.34 ± 51.91 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.5 | 0.7 | 4.7 | 1.52 ± 0.98 |
| `lanjian/day_01 input-kcen` | 1.4 ± 0.4 | 0.8 | 3.9 | 1.35 ± 0.82 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.4 | 0.5 | 4.0 | 1.25 ± 0.79 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.9 | 0.6 | 15.0 | 1.33 ± 1.13 |
| `lanjian/day_01 input-pting` | 1.3 ± 0.8 | 0.7 | 10.6 | 1.27 ± 1.04 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.6 | 0.4 | 7.4 | 1.24 ± 0.86 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.1 ± 0.6 | 0.5 | 17.7 | 1.05 ± 0.79 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.4 | 0.6 | 4.7 | 1.43 ± 0.88 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.5 ± 1.3 | 0.4 | 14.0 | 1.49 ± 1.48 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.6 | 0.6 | 15.7 | 1.00 |
| `python pting/day01.py input-aspidites` | 33.5 ± 3.5 | 28.3 | 45.3 | 32.43 ± 17.83 |
| `python pting/day01.py input-kcen` | 33.8 ± 4.5 | 28.1 | 46.3 | 32.76 ± 18.22 |
| `python pting/day01.py input-lanjian` | 33.5 ± 7.2 | 24.9 | 70.4 | 32.47 ± 18.88 |
| `python pting/day01.py input-mattcl` | 32.0 ± 4.2 | 25.1 | 42.5 | 30.97 ± 17.22 |
| `python pting/day01.py input-pting` | 31.3 ± 2.6 | 27.3 | 39.0 | 30.33 ± 16.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
