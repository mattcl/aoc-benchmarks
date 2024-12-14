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
| mattcl | input-mattcl | 1.4 ± 0.1 | 0.7 | 1.9 | 1.00 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.3 | 1.02 ± 0.14 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.4 | 1.04 ± 0.14 |
| mattcl | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.5 | 1.04 ± 0.16 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.6 | 2.4 | 1.04 ± 0.17 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.7 | 2.4 | 1.06 ± 0.18 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.9 | 2.4 | 1.06 ± 0.20 |
| mattcl | input-kcen | 1.6 ± 0.3 | 1.0 | 2.7 | 1.09 ± 0.22 |
| kcen | input-lanjian | 2.3 ± 0.3 | 1.5 | 3.9 | 1.61 ± 0.27 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.5 | 3.5 | 1.61 ± 0.26 |
| kcen | input-mikofo | 2.3 ± 0.4 | 1.4 | 4.2 | 1.62 ± 0.28 |
| kcen | input-mattcl | 2.3 ± 0.3 | 1.5 | 3.1 | 1.65 ± 0.25 |
| mattcl-py | input-mikofo | 22.5 ± 0.6 | 21.7 | 25.4 | 15.80 ± 1.20 |
| mattcl-py | input-kcen | 22.6 ± 0.7 | 21.3 | 25.6 | 15.86 ± 1.24 |
| mattcl-py | input-lanjian | 22.7 ± 0.9 | 21.5 | 25.7 | 15.95 ± 1.28 |
| mattcl-py | input-mattcl | 22.9 ± 0.8 | 21.8 | 25.7 | 16.05 ± 1.26 |
| mikofo | input-kcen | 25.8 ± 0.7 | 24.6 | 28.6 | 18.14 ± 1.37 |
| mikofo | input-mikofo | 26.1 ± 0.8 | 25.1 | 28.6 | 18.33 ± 1.43 |
| mikofo | input-lanjian | 26.2 ± 1.0 | 25.0 | 29.3 | 18.38 ± 1.48 |
| mikofo | input-mattcl | 26.3 ± 0.9 | 25.1 | 29.5 | 18.48 ± 1.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|