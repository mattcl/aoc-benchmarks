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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 14.0 ± 2.3 | 11.8 | 27.3 | 14.48 ± 11.58 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.7 ± 2.9 | 12.3 | 30.3 | 15.14 ± 12.23 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 14.9 ± 4.2 | 12.0 | 53.5 | 15.37 ± 12.79 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 16.3 ± 6.5 | 12.2 | 63.4 | 16.79 ± 14.77 |
| `aspidites-solver/aoc -i input-pting -d 1` | 14.5 ± 3.5 | 11.7 | 41.9 | 14.98 ± 12.28 |
| `kcen/2022/01/solve input-aspidites` | 170.9 ± 16.2 | 149.1 | 205.7 | 176.34 ± 139.07 |
| `kcen/2022/01/solve input-kcen` | 177.6 ± 20.4 | 148.6 | 209.8 | 183.17 ± 144.95 |
| `kcen/2022/01/solve input-lanjian` | 165.3 ± 17.3 | 140.8 | 207.5 | 170.56 ± 134.73 |
| `kcen/2022/01/solve input-mattcl` | 180.2 ± 16.2 | 159.6 | 218.5 | 185.85 ± 146.47 |
| `kcen/2022/01/solve input-pting` | 167.0 ± 10.3 | 144.1 | 181.7 | 172.24 ± 135.27 |
| `lanjian/day_01 input-aspidites` | 2.4 ± 1.5 | 0.5 | 14.8 | 2.50 ± 2.51 |
| `lanjian/day_01 input-kcen` | 3.4 ± 2.7 | 0.5 | 34.7 | 3.51 ± 3.94 |
| `lanjian/day_01 input-lanjian` | 2.3 ± 1.6 | 0.4 | 16.5 | 2.41 ± 2.52 |
| `lanjian/day_01 input-mattcl` | 5.6 ± 6.8 | 0.2 | 38.5 | 5.79 ± 8.39 |
| `lanjian/day_01 input-pting` | 2.8 ± 2.0 | 0.3 | 19.3 | 2.88 ± 3.03 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.8 ± 2.2 | 0.4 | 13.3 | 2.94 ± 3.24 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.1 ± 2.5 | 0.4 | 30.9 | 3.16 ± 3.55 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.3 ± 2.6 | 0.5 | 19.2 | 3.44 ± 3.82 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.8 ± 1.7 | 0.2 | 13.5 | 2.93 ± 2.87 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.8 | 0.0 | 10.9 | 1.00 |
| `python pting/day01.py input-aspidites` | 55.2 ± 7.1 | 41.3 | 83.0 | 56.97 ± 45.21 |
| `python pting/day01.py input-kcen` | 82.1 ± 43.4 | 46.5 | 202.2 | 84.69 ± 80.02 |
| `python pting/day01.py input-lanjian` | 60.3 ± 13.3 | 45.6 | 142.1 | 62.18 ± 50.57 |
| `python pting/day01.py input-mattcl` | 64.4 ± 18.8 | 45.3 | 141.1 | 66.48 ± 55.54 |
| `python pting/day01.py input-pting` | 64.3 ± 20.7 | 42.3 | 148.5 | 66.36 ± 56.19 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
