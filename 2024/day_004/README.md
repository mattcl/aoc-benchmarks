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
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.3 | 1.01 ± 0.19 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.5 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.3 | 1.02 ± 0.18 |
| lanjian | input-mikofo | 1.5 ± 0.3 | 0.8 | 2.5 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 0.9 | 2.9 | 1.05 ± 0.23 |
| mattcl | input-mikofo | 1.5 ± 0.3 | 1.0 | 2.7 | 1.05 ± 0.22 |
| kcen | input-kcen | 1.7 ± 0.4 | 1.0 | 3.0 | 1.19 ± 0.29 |
| kcen | input-mattcl | 1.8 ± 0.4 | 1.1 | 2.8 | 1.21 ± 0.29 |
| kcen | input-lanjian | 1.8 ± 0.3 | 1.1 | 3.0 | 1.22 ± 0.29 |
| kcen | input-mikofo | 1.8 ± 0.4 | 1.0 | 3.0 | 1.23 ± 0.32 |
| mattcl-py | input-kcen | 22.4 ± 0.8 | 21.3 | 25.3 | 15.34 ± 2.08 |
| mattcl-py | input-lanjian | 22.5 ± 0.6 | 21.5 | 25.0 | 15.43 ± 2.07 |
| mattcl-py | input-mikofo | 22.7 ± 0.7 | 21.6 | 25.6 | 15.55 ± 2.09 |
| mattcl-py | input-mattcl | 22.8 ± 0.7 | 21.5 | 25.6 | 15.60 ± 2.10 |
| mikofo | input-kcen | 25.8 ± 0.8 | 24.9 | 28.5 | 17.71 ± 2.38 |
| mikofo | input-lanjian | 25.9 ± 1.1 | 24.6 | 33.3 | 17.77 ± 2.44 |
| mikofo | input-mikofo | 26.2 ± 1.0 | 24.6 | 29.6 | 17.92 ± 2.45 |
| mikofo | input-mattcl | 26.2 ± 0.8 | 25.1 | 28.9 | 17.92 ± 2.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|