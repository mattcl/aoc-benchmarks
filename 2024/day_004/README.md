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
| lanjian | input-mikofo | 1.1 ± 0.4 | 0.4 | 2.3 | 1.00 |
| kcen | input-mikofo | 1.2 ± 0.3 | 0.6 | 2.3 | 1.12 ± 0.47 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.5 | 2.6 | 1.30 ± 0.50 |
| mattcl | input-mikofo | 1.5 ± 0.3 | 0.6 | 2.3 | 1.31 ± 0.50 |
| mattcl | input-kcen | 1.5 ± 0.3 | 0.5 | 2.7 | 1.35 ± 0.53 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.7 | 2.6 | 1.45 ± 0.54 |
| mattcl | input-lanjian | 1.7 ± 0.4 | 1.0 | 3.0 | 1.48 ± 0.58 |
| mattcl | input-mattcl | 1.7 ± 0.3 | 0.9 | 2.5 | 1.49 ± 0.56 |
| lanjian | input-lanjian | 1.7 ± 0.4 | 0.9 | 2.9 | 1.50 ± 0.58 |
| kcen | input-kcen | 1.9 ± 0.4 | 1.0 | 2.9 | 1.69 ± 0.64 |
| kcen | input-lanjian | 1.9 ± 0.4 | 1.2 | 3.2 | 1.72 ± 0.64 |
| kcen | input-mattcl | 1.9 ± 0.4 | 1.2 | 3.0 | 1.75 ± 0.65 |
| mattcl-py | input-lanjian | 22.9 ± 0.7 | 21.8 | 26.1 | 20.54 ± 6.62 |
| mattcl-py | input-kcen | 22.9 ± 0.7 | 21.6 | 26.4 | 20.58 ± 6.64 |
| mattcl-py | input-mattcl | 23.0 ± 0.9 | 21.5 | 26.0 | 20.66 ± 6.68 |
| mattcl-py | input-mikofo | 23.1 ± 0.8 | 21.8 | 25.8 | 20.73 ± 6.69 |
| mikofo | input-lanjian | 26.4 ± 0.8 | 25.0 | 29.1 | 23.64 ± 7.63 |
| mikofo | input-kcen | 26.5 ± 1.0 | 24.9 | 30.4 | 23.73 ± 7.67 |
| mikofo | input-mattcl | 26.5 ± 1.0 | 25.1 | 29.9 | 23.75 ± 7.68 |
| mikofo | input-mikofo | 26.5 ± 0.9 | 25.3 | 31.2 | 23.75 ± 7.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|