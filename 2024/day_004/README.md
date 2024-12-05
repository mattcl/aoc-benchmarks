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
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.8 | 2.2 | 1.00 ± 0.14 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.4 | 1.01 ± 0.16 |
| lanjian | input-mikofo | 1.5 ± 0.1 | 1.0 | 2.4 | 1.01 ± 0.15 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 1.2 | 2.5 | 1.02 ± 0.16 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 0.8 | 2.4 | 1.03 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.4 | 1.03 ± 0.18 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.7 | 1.04 ± 0.20 |
| kcen | input-mattcl | 2.1 ± 0.3 | 1.4 | 2.9 | 1.46 ± 0.28 |
| kcen | input-kcen | 2.1 ± 0.4 | 1.3 | 3.3 | 1.48 ± 0.31 |
| kcen | input-lanjian | 2.1 ± 0.3 | 1.4 | 3.3 | 1.48 ± 0.29 |
| kcen | input-mikofo | 2.2 ± 0.4 | 1.3 | 3.9 | 1.49 ± 0.30 |
| mattcl-py | input-kcen | 22.3 ± 0.6 | 21.2 | 25.4 | 15.49 ± 1.78 |
| mattcl-py | input-lanjian | 22.4 ± 0.7 | 21.2 | 25.3 | 15.57 ± 1.80 |
| mattcl-py | input-mikofo | 22.5 ± 0.7 | 21.3 | 25.0 | 15.62 ± 1.81 |
| mattcl-py | input-mattcl | 22.7 ± 0.8 | 21.3 | 25.6 | 15.77 ± 1.84 |
| mikofo | input-kcen | 25.8 ± 0.8 | 24.6 | 28.8 | 17.88 ± 2.06 |
| mikofo | input-mikofo | 25.8 ± 0.7 | 24.8 | 28.7 | 17.89 ± 2.04 |
| mikofo | input-lanjian | 25.8 ± 0.9 | 24.6 | 28.9 | 17.93 ± 2.09 |
| mikofo | input-mattcl | 26.1 ± 0.8 | 25.1 | 29.9 | 18.11 ± 2.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|