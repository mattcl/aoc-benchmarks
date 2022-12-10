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
| `lanjian/day_10 input-lanjian` | 2.4 ± 0.8 | 0.9 | 9.9 | 1.05 ± 0.65 |
| `lanjian/day_10 input-mattcl` | 3.1 ± 3.6 | 0.8 | 51.4 | 1.36 ± 1.72 |
| `lanjian/day_10 input-pting` | 2.3 ± 1.2 | 0.8 | 24.6 | 1.00 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.7 ± 1.2 | 0.9 | 25.8 | 1.19 ± 0.81 |
| `mattcl-solver/aoc run 10 input-mattcl` | 2.5 ± 0.8 | 0.9 | 9.6 | 1.08 ± 0.66 |
| `mattcl-solver/aoc run 10 input-pting` | 2.7 ± 1.0 | 1.0 | 10.9 | 1.19 ± 0.77 |
| `python pting/day10.py input-lanjian` | 49.2 ± 5.7 | 39.5 | 62.9 | 21.73 ± 11.65 |
| `python pting/day10.py input-mattcl` | 131.1 ± 85.6 | 44.9 | 357.3 | 57.96 ± 48.47 |
| `python pting/day10.py input-pting` | 55.5 ± 8.7 | 43.5 | 85.6 | 24.52 ± 13.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>14760</pre>|<pre><br>####.####..##..####.###..#..#.###..####.<br>#....#....#..#.#....#..#.#..#.#..#.#....<br>###..###..#....###..#..#.#..#.#..#.###..<br>#....#....#.##.#....###..#..#.###..#....<br>#....#....#..#.#....#.#..#..#.#.#..#....<br>####.#.....###.####.#..#..##..#..#.####.</pre>|
|input-mattcl|<pre>11720</pre>|<pre><br>####.###...##..###..####.###...##....##.<br>#....#..#.#..#.#..#.#....#..#.#..#....#.<br>###..#..#.#....#..#.###..#..#.#.......#.<br>#....###..#....###..#....###..#.......#.<br>#....#.#..#..#.#.#..#....#....#..#.#..#.<br>####.#..#..##..#..#.####.#.....##...##..</pre>|
|input-pting|<pre>14160</pre>|<pre><br>###....##.####.###..###..####.####..##..<br>#..#....#.#....#..#.#..#.#....#....#..#.<br>#..#....#.###..#..#.#..#.###..###..#....<br>###.....#.#....###..###..#....#....#....<br>#.#..#..#.#....#.#..#....#....#....#..#.<br>#..#..##..####.#..#.#....####.#.....##..</pre>|
