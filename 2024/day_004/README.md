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
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.2 | 2.4 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.9 | 1.01 ± 0.24 |
| mattcl | input-kcen | 1.5 ± 0.3 | 1.0 | 2.6 | 1.01 ± 0.24 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.9 | 2.3 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.7 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.9 | 2.7 | 1.03 ± 0.25 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 0.6 | 2.7 | 1.05 ± 0.27 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 1.0 | 2.7 | 1.06 ± 0.27 |
| kcen | input-mikofo | 2.3 ± 0.3 | 1.5 | 3.1 | 1.52 ± 0.30 |
| kcen | input-lanjian | 2.3 ± 0.3 | 1.6 | 4.1 | 1.55 ± 0.31 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.7 | 3.3 | 1.55 ± 0.30 |
| kcen | input-mattcl | 2.3 ± 0.3 | 1.4 | 3.1 | 1.56 ± 0.30 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.3 | 25.4 | 15.24 ± 2.17 |
| mattcl-py | input-mattcl | 22.6 ± 0.6 | 21.7 | 25.0 | 15.28 ± 2.17 |
| mattcl-py | input-mikofo | 22.7 ± 0.8 | 21.6 | 25.9 | 15.33 ± 2.21 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.3 | 24.9 | 15.34 ± 2.19 |
| mikofo | input-lanjian | 26.0 ± 0.8 | 24.9 | 29.5 | 17.53 ± 2.51 |
| mikofo | input-mikofo | 26.0 ± 0.9 | 24.6 | 29.4 | 17.54 ± 2.52 |
| mikofo | input-kcen | 26.2 ± 1.0 | 24.7 | 29.7 | 17.68 ± 2.56 |
| mikofo | input-mattcl | 26.2 ± 0.9 | 24.9 | 29.1 | 17.70 ± 2.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|