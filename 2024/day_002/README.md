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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.2 | 2.0 | 1.02 ± 0.26 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.8 | 2.3 | 1.08 ± 0.25 |
| lanjian | input-lanjian | 1.4 ± 0.1 | 0.8 | 2.3 | 1.21 ± 0.23 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 1.9 | 1.22 ± 0.24 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.8 | 2.3 | 1.23 ± 0.25 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.24 ± 0.24 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.5 | 3.3 | 1.98 ± 0.43 |
| kcen | input-lanjian | 2.4 ± 0.4 | 1.5 | 4.1 | 2.06 ± 0.47 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.4 | 4.0 | 2.12 ± 0.44 |
| kcen | input-mikofo | 2.5 ± 0.3 | 1.7 | 4.1 | 2.13 ± 0.42 |
| mikofo | input-kcen | 18.2 ± 0.6 | 17.3 | 20.7 | 15.41 ± 2.55 |
| mattcl-py | input-mikofo | 18.4 ± 0.7 | 17.2 | 21.8 | 15.62 ± 2.60 |
| mikofo | input-lanjian | 18.4 ± 0.7 | 17.3 | 21.8 | 15.64 ± 2.60 |
| mattcl-py | input-mattcl | 18.7 ± 0.7 | 17.4 | 21.9 | 15.82 ± 2.64 |
| mattcl-py | input-lanjian | 18.8 ± 0.6 | 17.7 | 21.5 | 15.96 ± 2.64 |
| mikofo | input-mattcl | 19.0 ± 0.6 | 17.9 | 21.9 | 16.11 ± 2.67 |
| mattcl-py | input-kcen | 19.0 ± 0.7 | 17.7 | 22.3 | 16.14 ± 2.70 |
| mikofo | input-mikofo | 19.1 ± 0.5 | 17.9 | 21.4 | 16.18 ± 2.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|