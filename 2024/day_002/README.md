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
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.2 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.9 | 1.11 ± 0.32 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.5 | 1.12 ± 0.33 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.8 | 1.8 | 1.12 ± 0.31 |
| lanjian | input-mikofo | 1.4 ± 0.1 | 0.6 | 2.0 | 1.12 ± 0.31 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.9 | 2.1 | 1.12 ± 0.31 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.13 ± 0.34 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.13 ± 0.33 |
| kcen | input-kcen | 2.3 ± 0.4 | 1.3 | 4.5 | 1.86 ± 0.57 |
| kcen | input-lanjian | 2.4 ± 0.3 | 1.5 | 3.2 | 1.90 ± 0.55 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.5 | 4.1 | 1.98 ± 0.59 |
| kcen | input-mikofo | 2.5 ± 0.3 | 1.7 | 3.9 | 1.99 ± 0.58 |
| mikofo | input-kcen | 18.2 ± 0.8 | 17.3 | 21.6 | 14.69 ± 3.90 |
| mattcl-py | input-mikofo | 18.3 ± 0.6 | 17.4 | 21.5 | 14.75 ± 3.89 |
| mikofo | input-lanjian | 18.4 ± 0.8 | 17.3 | 21.4 | 14.86 ± 3.94 |
| mattcl-py | input-mattcl | 18.6 ± 0.7 | 17.5 | 21.3 | 15.00 ± 3.98 |
| mattcl-py | input-lanjian | 18.8 ± 0.7 | 17.8 | 21.9 | 15.17 ± 4.01 |
| mikofo | input-mattcl | 18.9 ± 0.6 | 17.8 | 22.4 | 15.27 ± 4.04 |
| mattcl-py | input-kcen | 19.0 ± 0.7 | 17.7 | 22.3 | 15.32 ± 4.05 |
| mikofo | input-mikofo | 19.3 ± 0.8 | 18.0 | 22.4 | 15.53 ± 4.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|