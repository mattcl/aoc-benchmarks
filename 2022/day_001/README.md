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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 0.5 | 11.5 | 13.9 | 9.96 ± 2.80 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.0 ± 0.4 | 11.3 | 13.9 | 9.84 ± 2.76 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.3 ± 0.4 | 11.6 | 14.3 | 10.14 ± 2.85 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.6 | 11.3 | 16.7 | 9.98 ± 2.82 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.6 | 11.4 | 14.1 | 10.04 ± 2.83 |
| `kcen/2022/01/solve input-aspidites` | 105.8 ± 8.5 | 91.4 | 126.3 | 87.07 ± 25.24 |
| `kcen/2022/01/solve input-kcen` | 108.0 ± 9.4 | 95.5 | 127.4 | 88.85 ± 25.92 |
| `kcen/2022/01/solve input-lanjian` | 104.9 ± 9.0 | 92.5 | 128.4 | 86.29 ± 25.16 |
| `kcen/2022/01/solve input-mattcl` | 93.5 ± 4.5 | 86.9 | 104.8 | 76.94 ± 21.75 |
| `kcen/2022/01/solve input-pting` | 100.8 ± 13.4 | 86.4 | 138.1 | 82.94 ± 25.61 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.4 | 0.9 | 3.6 | 1.13 ± 0.44 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.6 | 0.8 | 9.2 | 1.38 ± 0.62 |
| `lanjian/day_01 input-lanjian` | 1.6 ± 0.4 | 0.9 | 4.4 | 1.34 ± 0.53 |
| `lanjian/day_01 input-mattcl` | 1.5 ± 0.4 | 0.8 | 4.4 | 1.25 ± 0.49 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.4 | 0.9 | 4.7 | 1.17 ± 0.45 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.3 | 0.7 | 4.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.7 | 0.6 | 7.5 | 1.25 ± 0.68 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.3 | 0.7 | 3.5 | 1.05 ± 0.41 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.4 | 0.7 | 7.8 | 1.06 ± 0.47 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.4 | 0.7 | 5.6 | 1.02 ± 0.41 |
| `python pting/day01.py input-aspidites` | 36.4 ± 4.6 | 28.9 | 53.4 | 29.92 ± 9.14 |
| `python pting/day01.py input-kcen` | 35.2 ± 4.7 | 28.5 | 48.8 | 29.01 ± 8.96 |
| `python pting/day01.py input-lanjian` | 36.0 ± 7.1 | 29.1 | 62.5 | 29.67 ± 10.10 |
| `python pting/day01.py input-mattcl` | 32.0 ± 5.3 | 26.8 | 59.4 | 26.38 ± 8.55 |
| `python pting/day01.py input-pting` | 31.3 ± 3.7 | 26.7 | 51.6 | 25.73 ± 7.78 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
