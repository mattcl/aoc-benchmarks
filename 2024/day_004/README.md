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
| mattcl | input-kcen | 1.5 ± 0.3 | 0.6 | 2.5 | 1.00 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.9 | 1.01 ± 0.26 |
| lanjian | input-mikofo | 1.5 ± 0.3 | 0.6 | 2.3 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.6 ± 0.3 | 0.5 | 2.6 | 1.05 ± 0.30 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 0.7 | 2.6 | 1.05 ± 0.27 |
| mattcl | input-mattcl | 1.6 ± 0.3 | 0.6 | 3.0 | 1.05 ± 0.29 |
| lanjian | input-kcen | 1.6 ± 0.4 | 0.6 | 2.9 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.7 | 1.07 ± 0.29 |
| kcen | input-mikofo | 1.7 ± 0.4 | 0.7 | 2.9 | 1.14 ± 0.36 |
| kcen | input-lanjian | 1.7 ± 0.4 | 0.6 | 2.7 | 1.17 ± 0.35 |
| kcen | input-mattcl | 1.8 ± 0.4 | 0.7 | 3.2 | 1.20 ± 0.36 |
| kcen | input-kcen | 1.9 ± 0.4 | 0.8 | 3.0 | 1.26 ± 0.36 |
| mattcl-py | input-kcen | 22.9 ± 0.6 | 21.5 | 25.7 | 15.36 ± 2.95 |
| mattcl-py | input-lanjian | 23.1 ± 0.7 | 22.0 | 25.8 | 15.50 ± 2.98 |
| mattcl-py | input-mattcl | 23.3 ± 0.8 | 21.9 | 26.5 | 15.64 ± 3.02 |
| mattcl-py | input-mikofo | 23.5 ± 0.7 | 22.0 | 25.7 | 15.77 ± 3.04 |
| mikofo | input-lanjian | 26.6 ± 0.8 | 25.2 | 30.1 | 17.84 ± 3.44 |
| mikofo | input-kcen | 26.7 ± 0.8 | 25.3 | 29.9 | 17.90 ± 3.45 |
| mikofo | input-mattcl | 27.3 ± 0.8 | 25.4 | 29.8 | 18.31 ± 3.53 |
| mikofo | input-mikofo | 27.4 ± 1.1 | 26.1 | 36.4 | 18.37 ± 3.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|