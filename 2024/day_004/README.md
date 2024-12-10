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
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.4 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.3 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.6 | 2.9 | 1.01 ± 0.20 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.3 | 2.7 | 1.03 ± 0.20 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 1.0 | 2.8 | 1.04 ± 0.22 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.7 | 2.7 | 1.04 ± 0.23 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 0.9 | 2.8 | 1.08 ± 0.27 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 0.9 | 2.7 | 1.09 ± 0.26 |
| kcen | input-kcen | 2.1 ± 0.3 | 1.4 | 3.2 | 1.45 ± 0.29 |
| kcen | input-mikofo | 2.1 ± 0.4 | 1.3 | 3.4 | 1.45 ± 0.30 |
| kcen | input-lanjian | 2.1 ± 0.3 | 1.3 | 3.0 | 1.46 ± 0.29 |
| kcen | input-mattcl | 2.2 ± 0.4 | 1.4 | 3.1 | 1.50 ± 0.31 |
| mattcl-py | input-kcen | 22.5 ± 0.7 | 21.5 | 25.3 | 15.29 ± 2.00 |
| mattcl-py | input-mikofo | 22.5 ± 0.6 | 21.7 | 25.7 | 15.31 ± 2.00 |
| mattcl-py | input-lanjian | 22.6 ± 0.6 | 21.4 | 26.4 | 15.35 ± 2.01 |
| mattcl-py | input-mattcl | 22.7 ± 0.6 | 21.8 | 25.6 | 15.41 ± 2.01 |
| mikofo | input-mikofo | 26.0 ± 0.7 | 25.0 | 28.8 | 17.62 ± 2.30 |
| mikofo | input-kcen | 26.0 ± 0.8 | 24.9 | 28.8 | 17.67 ± 2.31 |
| mikofo | input-lanjian | 26.0 ± 0.8 | 24.6 | 28.7 | 17.68 ± 2.32 |
| mikofo | input-mattcl | 26.2 ± 0.8 | 25.2 | 30.0 | 17.81 ± 2.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|