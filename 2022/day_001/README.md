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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.5 ± 2.0 | 11.6 | 25.8 | 9.44 ± 3.23 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.1 ± 0.5 | 11.2 | 14.7 | 8.46 ± 2.64 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.7 ± 0.8 | 11.1 | 15.7 | 8.84 ± 2.80 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.4 ± 0.9 | 12.2 | 21.2 | 9.36 ± 2.97 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.5 ± 1.0 | 11.4 | 23.4 | 8.69 ± 2.78 |
| `kcen/2022/01/solve input-aspidites` | 121.7 ± 17.4 | 97.8 | 169.7 | 84.97 ± 28.98 |
| `kcen/2022/01/solve input-kcen` | 110.0 ± 6.8 | 96.6 | 127.9 | 76.77 ± 24.25 |
| `kcen/2022/01/solve input-lanjian` | 121.6 ± 14.3 | 96.9 | 161.9 | 84.92 ± 28.13 |
| `kcen/2022/01/solve input-mattcl` | 131.6 ± 19.7 | 103.7 | 189.3 | 91.88 ± 31.60 |
| `kcen/2022/01/solve input-pting` | 120.8 ± 15.3 | 97.0 | 159.7 | 84.33 ± 28.23 |
| `lanjian/day_01 input-aspidites` | 2.3 ± 0.9 | 0.9 | 6.9 | 1.61 ± 0.79 |
| `lanjian/day_01 input-kcen` | 2.1 ± 1.2 | 0.9 | 10.8 | 1.49 ± 0.93 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.6 | 1.0 | 10.7 | 1.22 ± 0.55 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.5 | 0.9 | 4.1 | 1.27 ± 0.52 |
| `lanjian/day_01 input-pting` | 2.2 ± 0.8 | 1.1 | 9.6 | 1.52 ± 0.75 |
| `mattcl-solver/aoc run 1 input-aspidites` | 3.0 ± 1.4 | 1.0 | 13.9 | 2.06 ± 1.18 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.0 ± 0.7 | 0.9 | 7.4 | 1.42 ± 0.65 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.6 ± 0.5 | 0.8 | 6.2 | 1.09 ± 0.48 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.4 ± 0.4 | 0.8 | 4.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 2.3 ± 0.9 | 0.8 | 7.9 | 1.63 ± 0.80 |
| `python pting/day01.py input-aspidites` | 37.0 ± 8.4 | 28.3 | 67.5 | 25.85 ± 9.92 |
| `python pting/day01.py input-kcen` | 33.8 ± 4.5 | 27.3 | 59.8 | 23.62 ± 7.96 |
| `python pting/day01.py input-lanjian` | 34.5 ± 3.5 | 28.4 | 49.3 | 24.09 ± 7.86 |
| `python pting/day01.py input-mattcl` | 34.0 ± 4.9 | 27.8 | 50.6 | 23.75 ± 8.11 |
| `python pting/day01.py input-pting` | 35.8 ± 7.1 | 26.6 | 59.6 | 25.01 ± 9.19 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
