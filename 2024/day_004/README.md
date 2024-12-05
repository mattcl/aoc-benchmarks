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
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.4 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.5 ± 0.1 | 0.9 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 0.8 | 2.3 | 1.01 ± 0.17 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.5 | 2.4 | 1.01 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.4 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 1.5 ± 0.3 | 0.9 | 2.7 | 1.06 ± 0.22 |
| kcen | input-kcen | 2.1 ± 0.3 | 0.9 | 3.1 | 1.43 ± 0.29 |
| kcen | input-lanjian | 2.1 ± 0.4 | 1.2 | 3.5 | 1.45 ± 0.30 |
| kcen | input-mattcl | 2.1 ± 0.3 | 1.4 | 2.8 | 1.46 ± 0.29 |
| kcen | input-mikofo | 2.1 ± 0.4 | 1.4 | 3.6 | 1.46 ± 0.31 |
| mattcl-py | input-kcen | 22.4 ± 0.8 | 21.0 | 25.8 | 15.48 ± 1.98 |
| mattcl-py | input-lanjian | 22.4 ± 0.8 | 21.3 | 25.3 | 15.53 ± 1.99 |
| mattcl-py | input-mikofo | 22.5 ± 0.7 | 21.3 | 25.4 | 15.57 ± 1.98 |
| mattcl-py | input-mattcl | 22.5 ± 0.8 | 21.4 | 25.7 | 15.59 ± 1.99 |
| mikofo | input-kcen | 25.8 ± 1.1 | 24.6 | 33.6 | 17.87 ± 2.33 |
| mikofo | input-lanjian | 25.9 ± 0.9 | 24.4 | 29.1 | 17.89 ± 2.29 |
| mikofo | input-mikofo | 26.0 ± 0.9 | 24.8 | 29.2 | 17.96 ± 2.29 |
| mikofo | input-mattcl | 26.1 ± 0.9 | 25.0 | 29.1 | 18.02 ± 2.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|