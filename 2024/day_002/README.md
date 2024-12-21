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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.7 | 1.00 ± 0.20 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.5 | 2.3 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.6 | 1.8 | 1.02 ± 0.19 |
| mattcl | input-mikofo | 1.4 ± 0.1 | 0.8 | 1.9 | 1.02 ± 0.20 |
| lanjian | input-kcen | 1.5 ± 0.1 | 1.2 | 1.7 | 1.03 ± 0.18 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.3 | 1.04 ± 0.23 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.4 | 1.04 ± 0.22 |
| kcen | input-mattcl | 2.3 ± 0.4 | 1.1 | 3.2 | 1.65 ± 0.38 |
| kcen | input-kcen | 2.3 ± 0.3 | 1.5 | 3.8 | 1.65 ± 0.36 |
| kcen | input-lanjian | 2.4 ± 0.3 | 1.7 | 4.1 | 1.71 ± 0.37 |
| kcen | input-mikofo | 2.6 ± 0.4 | 1.7 | 4.2 | 1.81 ± 0.39 |
| mikofo | input-kcen | 18.0 ± 0.7 | 17.0 | 21.1 | 12.79 ± 2.19 |
| mikofo | input-lanjian | 18.4 ± 0.7 | 17.3 | 21.4 | 13.02 ± 2.23 |
| mattcl-py | input-mikofo | 18.4 ± 0.8 | 17.2 | 21.7 | 13.07 ± 2.25 |
| mattcl-py | input-mattcl | 18.6 ± 0.7 | 17.4 | 21.8 | 13.15 ± 2.26 |
| mattcl-py | input-kcen | 18.8 ± 0.5 | 18.0 | 21.4 | 13.34 ± 2.25 |
| mattcl-py | input-lanjian | 18.9 ± 0.7 | 17.6 | 21.6 | 13.37 ± 2.29 |
| mikofo | input-mattcl | 18.9 ± 0.7 | 18.0 | 21.8 | 13.42 ± 2.29 |
| mikofo | input-mikofo | 19.2 ± 0.7 | 18.3 | 22.1 | 13.64 ± 2.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|