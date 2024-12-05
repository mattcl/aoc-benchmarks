# Day 4 benchmarks

[link to problem](https://adventofcode.com/2024/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.4 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.5 ± 0.1 | 0.9 | 2.3 | 1.12 ± 0.31 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.13 ± 0.33 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.4 | 1.14 ± 0.34 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.8 | 1.14 ± 0.35 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.5 | 1.15 ± 0.33 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.4 | 1.17 ± 0.36 |
| lanjian | input-mikofo | 1.5 ± 0.3 | 0.8 | 2.5 | 1.18 ± 0.37 |
| kcen | input-kcen | 2.1 ± 0.4 | 1.0 | 3.7 | 1.62 ± 0.52 |
| kcen | input-lanjian | 2.1 ± 0.3 | 1.2 | 3.1 | 1.64 ± 0.51 |
| kcen | input-mattcl | 2.1 ± 0.4 | 1.1 | 3.5 | 1.64 ± 0.53 |
| kcen | input-mikofo | 2.2 ± 0.4 | 1.3 | 3.6 | 1.67 ± 0.54 |
| mattcl-py | input-kcen | 22.4 ± 0.8 | 21.3 | 25.4 | 17.27 ± 4.65 |
| mattcl-py | input-mattcl | 22.4 ± 0.6 | 21.4 | 25.1 | 17.31 ± 4.64 |
| mattcl-py | input-lanjian | 22.4 ± 0.9 | 21.3 | 26.4 | 17.32 ± 4.67 |
| mattcl-py | input-mikofo | 22.4 ± 1.2 | 21.1 | 33.7 | 17.33 ± 4.72 |
| mikofo | input-mikofo | 1073.1 ± 16.8 | 1056.2 | 1089.8 | 828.67 ± 221.56 |
| mikofo | input-mattcl | 1089.1 ± 15.0 | 1072.1 | 1100.6 | 841.01 ± 224.77 |
| mikofo | input-kcen | 1117.0 ± 19.5 | 1101.6 | 1138.9 | 862.57 ± 230.72 |
| mikofo | input-lanjian | 1167.7 ± 7.2 | 1160.0 | 1174.2 | 901.75 ± 240.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|