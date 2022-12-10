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
| `lanjian/day_10 input-lanjian` | 2.5 ± 1.3 | 0.9 | 17.8 | 1.31 ± 0.92 |
| `lanjian/day_10 input-mattcl` | 2.0 ± 0.9 | 0.5 | 11.6 | 1.06 ± 0.68 |
| `lanjian/day_10 input-pting` | 1.9 ± 0.9 | 0.6 | 9.3 | 1.00 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.8 ± 0.8 | 1.0 | 7.5 | 1.47 ± 0.83 |
| `mattcl-solver/aoc run 10 input-mattcl` | 3.1 ± 0.9 | 1.4 | 8.4 | 1.64 ± 0.92 |
| `mattcl-solver/aoc run 10 input-pting` | 2.2 ± 1.2 | 0.7 | 20.3 | 1.18 ± 0.84 |
| `python pting/day10.py input-lanjian` | 52.7 ± 6.4 | 42.9 | 71.8 | 27.70 ± 13.74 |
| `python pting/day10.py input-mattcl` | 45.0 ± 4.2 | 39.6 | 61.1 | 23.63 ± 11.58 |
| `python pting/day10.py input-pting` | 50.2 ± 6.7 | 39.4 | 68.4 | 26.39 ± 13.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>14760</pre>|<pre><br>####.####..##..####.###..#..#.###..####.<br>#....#....#..#.#....#..#.#..#.#..#.#....<br>###..###..#....###..#..#.#..#.#..#.###..<br>#....#....#.##.#....###..#..#.###..#....<br>#....#....#..#.#....#.#..#..#.#.#..#....<br>####.#.....###.####.#..#..##..#..#.####.</pre>|
|input-mattcl|<pre>11720</pre>|<pre><br>####.###...##..###..####.###...##....##.<br>#....#..#.#..#.#..#.#....#..#.#..#....#.<br>###..#..#.#....#..#.###..#..#.#.......#.<br>#....###..#....###..#....###..#.......#.<br>#....#.#..#..#.#.#..#....#....#..#.#..#.<br>####.#..#..##..#..#.####.#.....##...##..</pre>|
|input-pting|<pre>14160</pre>|<pre><br>###....##.####.###..###..####.####..##..<br>#..#....#.#....#..#.#..#.#....#....#..#.<br>#..#....#.###..#..#.#..#.###..###..#....<br>###.....#.#....###..###..#....#....#....<br>#.#..#..#.#....#.#..#....#....#....#..#.<br>#..#..##..####.#..#.#....####.#.....##..</pre>|
