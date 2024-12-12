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
| mattcl | input-kcen | 1.5 ± 0.2 | 0.9 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.4 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.4 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.5 ± 0.3 | 1.1 | 2.7 | 1.03 ± 0.23 |
| mattcl | input-mikofo | 1.5 ± 0.3 | 0.9 | 2.8 | 1.03 ± 0.23 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 0.9 | 2.7 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 1.6 ± 0.3 | 0.9 | 2.7 | 1.06 ± 0.27 |
| lanjian | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.7 | 1.07 ± 0.27 |
| kcen | input-mikofo | 2.3 ± 0.3 | 1.5 | 3.4 | 1.51 ± 0.31 |
| kcen | input-mattcl | 2.3 ± 0.3 | 1.5 | 3.3 | 1.55 ± 0.32 |
| kcen | input-lanjian | 2.3 ± 0.4 | 1.5 | 5.1 | 1.56 ± 0.35 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.6 | 4.0 | 1.57 ± 0.32 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.6 | 25.8 | 15.08 ± 2.28 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.8 | 25.4 | 15.14 ± 2.29 |
| mattcl-py | input-mikofo | 22.7 ± 0.8 | 21.5 | 25.7 | 15.16 ± 2.30 |
| mattcl-py | input-mattcl | 22.9 ± 0.9 | 21.7 | 26.4 | 15.25 ± 2.34 |
| mikofo | input-kcen | 26.0 ± 0.9 | 24.6 | 29.3 | 17.34 ± 2.64 |
| mikofo | input-lanjian | 26.1 ± 0.8 | 24.7 | 30.4 | 17.38 ± 2.63 |
| mikofo | input-mikofo | 26.2 ± 0.9 | 24.8 | 29.0 | 17.49 ± 2.66 |
| mikofo | input-mattcl | 26.3 ± 1.1 | 25.1 | 33.3 | 17.54 ± 2.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|