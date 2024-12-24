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
| mattcl | input-lanjian | 0.9 ± 0.4 | 0.2 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.4 | 0.3 | 2.6 | 1.32 ± 0.77 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 2.0 | 1.57 ± 0.80 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.5 | 1.62 ± 0.81 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.2 | 1.63 ± 0.81 |
| lanjian | input-mattcl | 1.4 ± 0.3 | 0.5 | 2.8 | 1.64 ± 0.86 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.4 | 1.66 ± 0.84 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.3 | 1.67 ± 0.84 |
| kcen | input-lanjian | 2.2 ± 0.5 | 1.0 | 4.5 | 2.54 ± 1.36 |
| kcen | input-mattcl | 2.3 ± 0.5 | 1.0 | 4.3 | 2.66 ± 1.39 |
| kcen | input-kcen | 2.4 ± 0.3 | 1.4 | 3.9 | 2.76 ± 1.38 |
| kcen | input-mikofo | 2.6 ± 0.3 | 1.8 | 4.5 | 2.95 ± 1.46 |
| mikofo | input-kcen | 18.5 ± 0.7 | 17.0 | 21.2 | 21.11 ± 10.19 |
| mikofo | input-lanjian | 18.8 ± 0.7 | 17.6 | 21.4 | 21.45 ± 10.35 |
| mattcl-py | input-mikofo | 18.9 ± 0.7 | 17.7 | 21.9 | 21.58 ± 10.42 |
| mattcl-py | input-mattcl | 19.0 ± 0.6 | 18.1 | 22.0 | 21.71 ± 10.47 |
| mattcl-py | input-lanjian | 19.3 ± 0.6 | 17.9 | 22.4 | 22.04 ± 10.64 |
| mikofo | input-mattcl | 19.4 ± 0.6 | 18.3 | 22.2 | 22.13 ± 10.68 |
| mattcl-py | input-kcen | 19.4 ± 0.8 | 18.1 | 22.6 | 22.18 ± 10.72 |
| mikofo | input-mikofo | 19.6 ± 0.7 | 18.2 | 22.6 | 22.36 ± 10.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|