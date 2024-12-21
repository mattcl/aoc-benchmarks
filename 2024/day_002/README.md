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
| lanjian | input-mattcl | 1.0 ± 0.4 | 0.4 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.5 | 0.2 | 1.9 | 1.03 ± 0.60 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.7 | 1.39 ± 0.56 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 1.8 | 1.41 ± 0.55 |
| mattcl | input-mikofo | 1.4 ± 0.1 | 0.8 | 1.9 | 1.42 ± 0.55 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.7 | 2.1 | 1.43 ± 0.56 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.3 | 1.44 ± 0.56 |
| lanjian | input-mikofo | 1.5 ± 0.1 | 1.0 | 2.3 | 1.44 ± 0.56 |
| kcen | input-mattcl | 2.3 ± 0.4 | 1.1 | 3.0 | 2.24 ± 0.92 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.1 | 4.0 | 2.28 ± 0.93 |
| kcen | input-lanjian | 2.4 ± 0.4 | 1.4 | 4.3 | 2.35 ± 0.96 |
| kcen | input-mikofo | 2.4 ± 0.3 | 1.3 | 3.0 | 2.36 ± 0.95 |
| mikofo | input-kcen | 18.1 ± 0.6 | 17.1 | 20.9 | 17.78 ± 6.74 |
| mikofo | input-lanjian | 18.4 ± 0.6 | 17.4 | 21.1 | 17.98 ± 6.81 |
| mattcl-py | input-mikofo | 18.5 ± 0.9 | 17.2 | 21.9 | 18.10 ± 6.89 |
| mattcl-py | input-mattcl | 18.7 ± 0.7 | 17.3 | 21.8 | 18.35 ± 6.96 |
| mattcl-py | input-lanjian | 18.9 ± 0.7 | 17.7 | 21.8 | 18.56 ± 7.04 |
| mikofo | input-mattcl | 18.9 ± 0.6 | 17.9 | 22.4 | 18.57 ± 7.03 |
| mattcl-py | input-kcen | 19.0 ± 0.6 | 17.9 | 21.9 | 18.61 ± 7.05 |
| mikofo | input-mikofo | 19.2 ± 0.6 | 18.3 | 22.1 | 18.78 ± 7.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|