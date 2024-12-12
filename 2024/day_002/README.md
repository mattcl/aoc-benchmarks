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
| mattcl | input-mikofo | 1.1 ± 0.3 | 0.2 | 1.6 | 1.00 |
| lanjian | input-mikofo | 1.2 ± 0.4 | 0.2 | 2.1 | 1.10 ± 0.49 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.25 ± 0.43 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 1.7 | 1.27 ± 0.44 |
| mattcl | input-mattcl | 1.4 ± 0.3 | 0.5 | 4.3 | 1.27 ± 0.49 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.2 | 1.29 ± 0.45 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.4 | 2.2 | 1.29 ± 0.44 |
| lanjian | input-lanjian | 1.4 ± 0.1 | 0.7 | 2.3 | 1.31 ± 0.44 |
| kcen | input-lanjian | 2.2 ± 0.3 | 1.3 | 3.6 | 2.04 ± 0.73 |
| kcen | input-kcen | 2.2 ± 0.3 | 1.3 | 3.0 | 2.05 ± 0.73 |
| kcen | input-mattcl | 2.2 ± 0.4 | 1.3 | 3.5 | 2.08 ± 0.75 |
| kcen | input-mikofo | 2.3 ± 0.3 | 1.4 | 3.5 | 2.17 ± 0.76 |
| mikofo | input-kcen | 18.1 ± 0.6 | 17.2 | 21.0 | 17.02 ± 5.51 |
| mikofo | input-lanjian | 18.4 ± 0.6 | 17.6 | 21.7 | 17.25 ± 5.58 |
| mattcl-py | input-mikofo | 18.4 ± 0.7 | 17.4 | 21.8 | 17.31 ± 5.60 |
| mattcl-py | input-mattcl | 18.6 ± 0.8 | 17.3 | 21.8 | 17.47 ± 5.66 |
| mattcl-py | input-lanjian | 18.8 ± 0.6 | 17.7 | 21.6 | 17.65 ± 5.71 |
| mikofo | input-mattcl | 18.9 ± 0.7 | 17.8 | 22.4 | 17.75 ± 5.74 |
| mattcl-py | input-kcen | 18.9 ± 0.6 | 17.7 | 22.0 | 17.76 ± 5.74 |
| mikofo | input-mikofo | 19.2 ± 0.8 | 18.1 | 22.7 | 18.04 ± 5.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|