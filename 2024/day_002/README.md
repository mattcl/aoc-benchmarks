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
| mattcl | input-kcen | 1.3 ± 0.3 | 0.3 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.3 ± 0.3 | 0.4 | 2.2 | 1.02 ± 0.30 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.2 | 1.9 | 1.07 ± 0.27 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.4 | 2.6 | 1.07 ± 0.31 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.7 | 1.07 ± 0.27 |
| mattcl | input-mikofo | 1.4 ± 0.1 | 0.7 | 1.9 | 1.08 ± 0.25 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.7 | 1.11 ± 0.27 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.2 | 1.13 ± 0.29 |
| kcen | input-kcen | 2.1 ± 0.3 | 1.4 | 3.5 | 1.64 ± 0.44 |
| kcen | input-lanjian | 2.2 ± 0.3 | 1.5 | 3.5 | 1.67 ± 0.43 |
| kcen | input-mattcl | 2.2 ± 0.4 | 1.0 | 3.0 | 1.71 ± 0.45 |
| kcen | input-mikofo | 2.2 ± 0.4 | 1.3 | 3.6 | 1.72 ± 0.46 |
| mikofo | input-kcen | 18.4 ± 0.7 | 17.4 | 21.4 | 14.12 ± 3.00 |
| mikofo | input-lanjian | 18.7 ± 0.8 | 17.3 | 22.1 | 14.33 ± 3.05 |
| mattcl-py | input-mikofo | 18.7 ± 0.7 | 17.4 | 21.3 | 14.35 ± 3.05 |
| mattcl-py | input-mattcl | 18.8 ± 0.5 | 17.7 | 22.1 | 14.42 ± 3.04 |
| mattcl-py | input-lanjian | 19.2 ± 0.6 | 18.2 | 21.6 | 14.72 ± 3.12 |
| mikofo | input-mattcl | 19.2 ± 0.6 | 18.2 | 22.2 | 14.75 ± 3.12 |
| mattcl-py | input-kcen | 19.3 ± 0.7 | 17.7 | 22.7 | 14.82 ± 3.15 |
| mikofo | input-mikofo | 19.5 ± 0.8 | 18.3 | 22.4 | 14.94 ± 3.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|