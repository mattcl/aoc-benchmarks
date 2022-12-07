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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 15.0 ± 4.0 | 9.0 | 36.4 | 19.48 ± 21.52 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 14.9 ± 3.4 | 11.4 | 30.5 | 19.41 ± 21.27 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.8 ± 2.2 | 11.3 | 26.0 | 17.97 ± 19.47 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 16.3 ± 4.9 | 11.7 | 38.9 | 21.22 ± 23.64 |
| `aspidites-solver/aoc -i input-pting -d 1` | 16.5 ± 5.0 | 11.4 | 40.5 | 21.44 ± 23.88 |
| `kcen/2022/01/solve input-aspidites` | 183.4 ± 40.9 | 139.1 | 315.0 | 238.62 ± 261.28 |
| `kcen/2022/01/solve input-kcen` | 176.6 ± 23.5 | 138.5 | 235.2 | 229.80 ± 248.24 |
| `kcen/2022/01/solve input-lanjian` | 183.6 ± 48.4 | 141.6 | 320.3 | 238.88 ± 263.71 |
| `kcen/2022/01/solve input-mattcl` | 170.3 ± 43.5 | 132.5 | 284.6 | 221.67 ± 244.28 |
| `kcen/2022/01/solve input-pting` | 171.8 ± 42.1 | 141.5 | 325.0 | 223.62 ± 245.90 |
| `lanjian/day_01 input-aspidites` | 7.3 ± 10.8 | 0.0 | 68.6 | 9.52 ± 17.33 |
| `lanjian/day_01 input-kcen` | 0.8 ± 0.8 | 0.0 | 7.8 | 1.00 |
| `lanjian/day_01 input-lanjian` | 3.8 ± 3.8 | 0.0 | 46.2 | 4.97 ± 7.28 |
| `lanjian/day_01 input-mattcl` | 2.9 ± 1.8 | 0.5 | 10.1 | 3.80 ± 4.67 |
| `lanjian/day_01 input-pting` | 2.5 ± 1.8 | 0.0 | 10.8 | 3.19 ± 4.11 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.4 ± 1.9 | 0.0 | 11.5 | 3.07 ± 4.10 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.2 ± 2.3 | 0.0 | 18.7 | 2.83 ± 4.22 |
| `mattcl-solver/aoc run 1 input-lanjian` | 3.1 ± 1.9 | 0.3 | 12.4 | 4.07 ± 5.03 |
| `mattcl-solver/aoc run 1 input-mattcl` | 3.2 ± 2.0 | 0.0 | 12.9 | 4.16 ± 5.16 |
| `mattcl-solver/aoc run 1 input-pting` | 2.4 ± 1.8 | 0.0 | 10.1 | 3.09 ± 4.06 |
| `python pting/day01.py input-aspidites` | 67.8 ± 34.4 | 44.1 | 164.9 | 88.18 ± 104.57 |
| `python pting/day01.py input-kcen` | 52.6 ± 19.9 | 33.2 | 141.2 | 68.49 ± 77.87 |
| `python pting/day01.py input-lanjian` | 80.1 ± 40.6 | 41.4 | 168.5 | 104.29 ± 123.67 |
| `python pting/day01.py input-mattcl` | 57.6 ± 28.7 | 37.6 | 174.8 | 74.91 ± 88.55 |
| `python pting/day01.py input-pting` | 62.8 ± 31.5 | 39.7 | 184.0 | 81.67 ± 96.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
