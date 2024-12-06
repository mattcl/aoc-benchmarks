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
| mattcl | input-mikofo | 0.9 ± 0.5 | 0.1 | 1.6 | 1.00 |
| lanjian | input-mikofo | 1.1 ± 0.4 | 0.3 | 1.8 | 1.34 ± 0.84 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.1 | 1.58 ± 0.86 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.1 | 1.58 ± 0.86 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 1.9 | 1.61 ± 0.88 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.2 | 1.65 ± 0.90 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.67 ± 0.91 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.68 ± 0.92 |
| kcen | input-mikofo | 1.6 ± 0.4 | 0.6 | 3.0 | 1.91 ± 1.13 |
| kcen | input-kcen | 1.7 ± 0.3 | 1.0 | 2.8 | 1.98 ± 1.12 |
| kcen | input-lanjian | 1.7 ± 0.4 | 1.0 | 2.8 | 2.04 ± 1.15 |
| kcen | input-mattcl | 1.8 ± 0.4 | 0.7 | 2.8 | 2.12 ± 1.20 |
| mikofo | input-kcen | 18.4 ± 0.6 | 17.3 | 21.2 | 21.47 ± 11.36 |
| mikofo | input-lanjian | 18.6 ± 0.6 | 17.6 | 21.5 | 21.70 ± 11.47 |
| mattcl-py | input-mikofo | 18.7 ± 0.7 | 17.2 | 22.0 | 21.79 ± 11.53 |
| mattcl-py | input-mattcl | 18.9 ± 0.7 | 17.5 | 22.5 | 22.02 ± 11.65 |
| mikofo | input-mattcl | 19.2 ± 0.7 | 17.8 | 21.8 | 22.42 ± 11.86 |
| mattcl-py | input-lanjian | 19.2 ± 0.6 | 18.2 | 21.6 | 22.42 ± 11.86 |
| mattcl-py | input-kcen | 19.4 ± 0.6 | 17.8 | 22.6 | 22.61 ± 11.96 |
| mikofo | input-mikofo | 19.5 ± 0.9 | 18.0 | 22.4 | 22.81 ± 12.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|