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
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.3 | 1.00 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.6 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.4 | 1.01 ± 0.22 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.9 | 2.7 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.5 ± 0.3 | 0.6 | 2.5 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.8 | 2.6 | 1.04 ± 0.25 |
| mattcl | input-mikofo | 1.5 ± 0.3 | 0.7 | 2.7 | 1.04 ± 0.26 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 0.6 | 2.9 | 1.08 ± 0.27 |
| kcen | input-mikofo | 2.0 ± 0.3 | 1.3 | 3.0 | 1.37 ± 0.29 |
| kcen | input-mattcl | 2.0 ± 0.3 | 1.2 | 2.9 | 1.38 ± 0.29 |
| kcen | input-lanjian | 2.1 ± 0.4 | 1.4 | 3.4 | 1.41 ± 0.31 |
| kcen | input-kcen | 2.1 ± 0.4 | 1.3 | 3.7 | 1.41 ± 0.33 |
| mattcl-py | input-mikofo | 22.7 ± 0.7 | 21.5 | 25.4 | 15.48 ± 2.21 |
| mattcl-py | input-lanjian | 22.8 ± 0.8 | 21.1 | 25.8 | 15.55 ± 2.24 |
| mattcl-py | input-mattcl | 22.8 ± 0.8 | 21.5 | 26.2 | 15.56 ± 2.23 |
| mattcl-py | input-kcen | 22.8 ± 0.8 | 21.6 | 25.7 | 15.59 ± 2.23 |
| mikofo | input-mikofo | 26.0 ± 0.8 | 25.1 | 29.7 | 17.74 ± 2.53 |
| mikofo | input-kcen | 26.1 ± 0.9 | 25.1 | 29.0 | 17.81 ± 2.55 |
| mikofo | input-lanjian | 26.2 ± 1.0 | 24.9 | 29.1 | 17.88 ± 2.58 |
| mikofo | input-mattcl | 26.2 ± 0.8 | 24.8 | 29.2 | 17.89 ± 2.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|