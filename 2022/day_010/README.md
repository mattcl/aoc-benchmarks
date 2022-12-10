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
| `lanjian/day_10 input-lanjian` | 3.8 ± 4.4 | 0.6 | 36.1 | 2.40 ± 3.04 |
| `lanjian/day_10 input-mattcl` | 1.7 ± 0.9 | 0.5 | 11.7 | 1.11 ± 0.81 |
| `lanjian/day_10 input-pting` | 1.6 ± 0.8 | 0.5 | 7.3 | 1.00 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.0 ± 0.9 | 0.6 | 11.0 | 1.25 ± 0.84 |
| `mattcl-solver/aoc run 10 input-mattcl` | 2.3 ± 0.8 | 0.9 | 8.1 | 1.46 ± 0.90 |
| `mattcl-solver/aoc run 10 input-pting` | 2.0 ± 0.8 | 0.4 | 9.4 | 1.30 ± 0.82 |
| `python pting/day10.py input-lanjian` | 48.3 ± 6.4 | 37.1 | 73.8 | 30.70 ± 16.16 |
| `python pting/day10.py input-mattcl` | 48.5 ± 6.3 | 37.7 | 69.0 | 30.80 ± 16.19 |
| `python pting/day10.py input-pting` | 47.4 ± 6.0 | 37.9 | 75.5 | 30.12 ± 15.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>14760</pre>|<pre><br>####.####..##..####.###..#..#.###..####.<br>#....#....#..#.#....#..#.#..#.#..#.#....<br>###..###..#....###..#..#.#..#.#..#.###..<br>#....#....#.##.#....###..#..#.###..#....<br>#....#....#..#.#....#.#..#..#.#.#..#....<br>####.#.....###.####.#..#..##..#..#.####.</pre>|
|input-mattcl|<pre>11720</pre>|<pre><br>####.###...##..###..####.###...##....##.<br>#....#..#.#..#.#..#.#....#..#.#..#....#.<br>###..#..#.#....#..#.###..#..#.#.......#.<br>#....###..#....###..#....###..#.......#.<br>#....#.#..#..#.#.#..#....#....#..#.#..#.<br>####.#..#..##..#..#.####.#.....##...##..</pre>|
|input-pting|<pre>14160</pre>|<pre><br>###....##.####.###..###..####.####..##..<br>#..#....#.#....#..#.#..#.#....#....#..#.<br>#..#....#.###..#..#.#..#.###..###..#....<br>###.....#.#....###..###..#....#....#....<br>#.#..#..#.#....#.#..#....#....#....#..#.<br>#..#..##..####.#..#.#....####.#.....##..</pre>|
