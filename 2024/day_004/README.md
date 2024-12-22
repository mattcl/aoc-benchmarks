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
| lanjian | input-mattcl | 1.5 ± 0.3 | 0.7 | 2.5 | 1.00 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.7 | 2.8 | 1.01 ± 0.27 |
| lanjian | input-kcen | 1.6 ± 0.3 | 1.0 | 2.4 | 1.02 ± 0.26 |
| mattcl | input-kcen | 1.6 ± 0.3 | 0.8 | 2.6 | 1.02 ± 0.27 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 0.5 | 2.7 | 1.02 ± 0.27 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 1.0 | 2.7 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.4 | 1.04 ± 0.27 |
| mattcl | input-lanjian | 1.6 ± 0.3 | 1.0 | 2.7 | 1.05 ± 0.29 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.3 | 3.1 | 1.50 ± 0.35 |
| kcen | input-mikofo | 2.3 ± 0.3 | 1.4 | 3.9 | 1.51 ± 0.35 |
| kcen | input-mattcl | 2.3 ± 0.4 | 1.3 | 4.6 | 1.52 ± 0.38 |
| kcen | input-lanjian | 2.3 ± 0.3 | 1.5 | 3.8 | 1.53 ± 0.36 |
| mattcl-py | input-lanjian | 22.6 ± 0.6 | 21.6 | 25.4 | 14.78 ± 2.69 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.5 | 25.7 | 14.79 ± 2.70 |
| mattcl-py | input-mikofo | 22.6 ± 0.7 | 21.7 | 25.4 | 14.81 ± 2.70 |
| mattcl-py | input-mattcl | 22.8 ± 0.6 | 21.9 | 25.3 | 14.90 ± 2.71 |
| mikofo | input-kcen | 25.8 ± 0.6 | 24.7 | 29.0 | 16.88 ± 3.05 |
| mikofo | input-mikofo | 26.0 ± 0.8 | 24.9 | 29.2 | 16.97 ± 3.09 |
| mikofo | input-lanjian | 26.0 ± 0.8 | 24.9 | 28.9 | 17.03 ± 3.11 |
| mikofo | input-mattcl | 26.2 ± 0.7 | 25.2 | 29.2 | 17.11 ± 3.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|