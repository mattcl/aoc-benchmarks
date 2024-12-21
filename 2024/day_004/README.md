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
| lanjian | input-mattcl | 1.2 ± 0.4 | 0.5 | 2.2 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.3 | 0.5 | 2.2 | 1.05 ± 0.44 |
| lanjian | input-mikofo | 1.4 ± 0.4 | 0.5 | 2.6 | 1.17 ± 0.49 |
| mattcl | input-mikofo | 1.7 ± 0.4 | 0.5 | 2.7 | 1.35 ± 0.54 |
| mattcl | input-lanjian | 1.7 ± 0.3 | 1.0 | 2.6 | 1.35 ± 0.51 |
| lanjian | input-lanjian | 1.7 ± 0.3 | 1.0 | 2.9 | 1.40 ± 0.53 |
| lanjian | input-kcen | 1.7 ± 0.4 | 1.0 | 2.8 | 1.40 ± 0.54 |
| mattcl | input-kcen | 1.7 ± 0.4 | 1.0 | 2.9 | 1.41 ± 0.54 |
| kcen | input-mattcl | 2.1 ± 0.5 | 1.0 | 3.4 | 1.69 ± 0.65 |
| kcen | input-kcen | 2.4 ± 0.3 | 1.5 | 3.7 | 1.97 ± 0.68 |
| kcen | input-mikofo | 2.4 ± 0.4 | 1.5 | 4.9 | 1.99 ± 0.70 |
| kcen | input-lanjian | 2.5 ± 0.3 | 1.5 | 3.6 | 2.02 ± 0.68 |
| mattcl-py | input-lanjian | 22.7 ± 0.5 | 21.5 | 24.3 | 18.41 ± 5.87 |
| mattcl-py | input-kcen | 22.8 ± 0.7 | 21.1 | 25.8 | 18.51 ± 5.91 |
| mattcl-py | input-mikofo | 22.8 ± 0.7 | 21.5 | 25.4 | 18.52 ± 5.91 |
| mattcl-py | input-mattcl | 23.0 ± 0.7 | 21.4 | 25.7 | 18.65 ± 5.96 |
| mikofo | input-mikofo | 26.1 ± 0.6 | 24.9 | 28.9 | 21.16 ± 6.74 |
| mikofo | input-kcen | 26.1 ± 0.9 | 24.7 | 29.3 | 21.22 ± 6.78 |
| mikofo | input-lanjian | 26.3 ± 0.8 | 24.9 | 29.0 | 21.33 ± 6.81 |
| mikofo | input-mattcl | 26.7 ± 1.5 | 25.4 | 38.2 | 21.68 ± 6.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|