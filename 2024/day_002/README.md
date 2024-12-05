# Day 2 benchmarks

[link to problem](https://adventofcode.com/2024/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.0 ± 0.4 | 0.1 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.4 | 0.2 | 1.9 | 1.19 ± 0.59 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.1 | 1.28 ± 0.53 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.5 | 1.32 ± 0.53 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 2.0 | 1.35 ± 0.53 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 1.7 | 1.41 ± 0.53 |
| lanjian | input-mikofo | 1.4 ± 0.1 | 0.8 | 2.2 | 1.41 ± 0.54 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.42 ± 0.55 |
| kcen | input-lanjian | 1.6 ± 0.3 | 0.8 | 2.5 | 1.56 ± 0.64 |
| kcen | input-kcen | 1.6 ± 0.3 | 1.0 | 2.4 | 1.59 ± 0.65 |
| kcen | input-mattcl | 1.6 ± 0.3 | 1.2 | 2.6 | 1.61 ± 0.66 |
| kcen | input-mikofo | 1.7 ± 0.4 | 1.0 | 3.0 | 1.73 ± 0.73 |
| mikofo | input-kcen | 18.1 ± 0.6 | 17.3 | 21.3 | 18.03 ± 6.68 |
| mikofo | input-lanjian | 18.4 ± 0.7 | 17.6 | 21.6 | 18.35 ± 6.81 |
| mattcl-py | input-mikofo | 18.5 ± 0.7 | 17.5 | 21.1 | 18.39 ± 6.82 |
| mattcl-py | input-mattcl | 18.6 ± 0.7 | 17.7 | 21.8 | 18.51 ± 6.87 |
| mattcl-py | input-lanjian | 18.9 ± 0.7 | 17.5 | 22.2 | 18.76 ± 6.97 |
| mikofo | input-mattcl | 18.9 ± 0.6 | 18.0 | 21.9 | 18.86 ± 6.99 |
| mattcl-py | input-kcen | 19.0 ± 0.6 | 17.9 | 22.2 | 18.88 ± 7.00 |
| mikofo | input-mikofo | 19.3 ± 0.7 | 18.4 | 22.4 | 19.17 ± 7.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|