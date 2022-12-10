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
| `lanjian/day_10 input-lanjian` | 3.0 ± 2.8 | 0.2 | 33.7 | 1.63 ± 1.69 |
| `lanjian/day_10 input-mattcl` | 2.0 ± 0.9 | 0.5 | 7.2 | 1.09 ± 0.70 |
| `lanjian/day_10 input-pting` | 1.9 ± 0.9 | 0.4 | 11.7 | 1.00 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.4 ± 0.8 | 0.6 | 11.0 | 1.30 ± 0.75 |
| `mattcl-solver/aoc run 10 input-mattcl` | 2.1 ± 0.9 | 0.4 | 10.5 | 1.12 ± 0.72 |
| `mattcl-solver/aoc run 10 input-pting` | 2.3 ± 0.8 | 1.0 | 6.9 | 1.27 ± 0.73 |
| `python pting/day10.py input-lanjian` | 51.9 ± 7.0 | 39.5 | 66.2 | 28.02 ± 13.47 |
| `python pting/day10.py input-mattcl` | 53.7 ± 7.0 | 39.8 | 68.6 | 28.99 ± 13.89 |
| `python pting/day10.py input-pting` | 54.3 ± 6.5 | 42.6 | 67.5 | 29.31 ± 13.96 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>14760</pre>|<pre><br>####.####..##..####.###..#..#.###..####.<br>#....#....#..#.#....#..#.#..#.#..#.#....<br>###..###..#....###..#..#.#..#.#..#.###..<br>#....#....#.##.#....###..#..#.###..#....<br>#....#....#..#.#....#.#..#..#.#.#..#....<br>####.#.....###.####.#..#..##..#..#.####.</pre>|
|input-mattcl|<pre>11720</pre>|<pre><br>####.###...##..###..####.###...##....##.<br>#....#..#.#..#.#..#.#....#..#.#..#....#.<br>###..#..#.#....#..#.###..#..#.#.......#.<br>#....###..#....###..#....###..#.......#.<br>#....#.#..#..#.#.#..#....#....#..#.#..#.<br>####.#..#..##..#..#.####.#.....##...##..</pre>|
|input-pting|<pre>14160</pre>|<pre><br>###....##.####.###..###..####.####..##..<br>#..#....#.#....#..#.#..#.#....#....#..#.<br>#..#....#.###..#..#.#..#.###..###..#....<br>###.....#.#....###..###..#....#....#....<br>#.#..#..#.#....#.#..#....#....#....#..#.<br>#..#..##..####.#..#.#....####.#.....##..</pre>|
