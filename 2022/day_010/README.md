# Day 10 benchmarks

[link to problem](http://adventofcode.com/2022/day/10)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 10)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_10 input-lanjian` | 2.3 ± 0.9 | 0.7 | 10.3 | 1.02 ± 0.66 |
| `lanjian/day_10 input-mattcl` | 2.7 ± 1.5 | 0.4 | 17.3 | 1.20 ± 0.89 |
| `lanjian/day_10 input-pting` | 2.3 ± 1.2 | 0.5 | 13.5 | 1.00 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.6 ± 1.1 | 0.8 | 11.1 | 1.17 ± 0.78 |
| `mattcl-solver/aoc run 10 input-mattcl` | 2.3 ± 0.9 | 0.7 | 7.9 | 1.02 ± 0.65 |
| `mattcl-solver/aoc run 10 input-pting` | 2.7 ± 1.3 | 0.8 | 24.2 | 1.20 ± 0.83 |
| `python pting/day10.py input-lanjian` | 54.5 ± 7.7 | 42.4 | 71.0 | 24.14 ± 12.84 |
| `python pting/day10.py input-mattcl` | 59.8 ± 8.4 | 43.3 | 75.1 | 26.47 ± 14.08 |
| `python pting/day10.py input-pting` | 56.9 ± 9.6 | 40.0 | 79.2 | 25.20 ± 13.60 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>14760</pre>|<pre><br>####.####..##..####.###..#..#.###..####.<br>#....#....#..#.#....#..#.#..#.#..#.#....<br>###..###..#....###..#..#.#..#.#..#.###..<br>#....#....#.##.#....###..#..#.###..#....<br>#....#....#..#.#....#.#..#..#.#.#..#....<br>####.#.....###.####.#..#..##..#..#.####.</pre>|
|input-mattcl|<pre>11720</pre>|<pre><br>####.###...##..###..####.###...##....##.<br>#....#..#.#..#.#..#.#....#..#.#..#....#.<br>###..#..#.#....#..#.###..#..#.#.......#.<br>#....###..#....###..#....###..#.......#.<br>#....#.#..#..#.#.#..#....#....#..#.#..#.<br>####.#..#..##..#..#.####.#.....##...##..</pre>|
|input-pting|<pre>14160</pre>|<pre><br>###....##.####.###..###..####.####..##..<br>#..#....#.#....#..#.#..#.#....#....#..#.<br>#..#....#.###..#..#.#..#.###..###..#....<br>###.....#.#....###..###..#....#....#....<br>#.#..#..#.#....#.#..#....#....#....#..#.<br>#..#..##..####.#..#.#....####.#.....##..</pre>|
