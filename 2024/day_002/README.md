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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.0 | 1.00 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.7 | 1.7 | 1.01 ± 0.16 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.2 | 1.05 ± 0.20 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.2 | 1.05 ± 0.20 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.7 | 1.06 ± 0.21 |
| kcen | input-lanjian | 2.2 ± 0.3 | 1.3 | 2.9 | 1.67 ± 0.34 |
| kcen | input-kcen | 2.2 ± 0.4 | 1.4 | 4.0 | 1.68 ± 0.36 |
| kcen | input-mattcl | 2.4 ± 0.3 | 1.4 | 3.1 | 1.76 ± 0.34 |
| kcen | input-mikofo | 2.4 ± 0.4 | 1.5 | 4.3 | 1.81 ± 0.36 |
| mikofo | input-kcen | 18.5 ± 0.7 | 17.3 | 22.2 | 13.85 ± 1.95 |
| mattcl-py | input-mikofo | 18.6 ± 0.7 | 17.3 | 22.2 | 13.95 ± 1.96 |
| mikofo | input-lanjian | 18.7 ± 0.6 | 17.7 | 21.3 | 13.98 ± 1.95 |
| mattcl-py | input-mattcl | 18.9 ± 0.6 | 17.6 | 21.9 | 14.13 ± 1.97 |
| mattcl-py | input-lanjian | 19.2 ± 0.6 | 18.3 | 21.6 | 14.37 ± 1.99 |
| mikofo | input-mattcl | 19.2 ± 0.8 | 18.1 | 22.6 | 14.39 ± 2.03 |
| mattcl-py | input-kcen | 19.3 ± 0.6 | 18.0 | 22.3 | 14.44 ± 2.01 |
| mikofo | input-mikofo | 19.5 ± 0.8 | 18.3 | 22.5 | 14.59 ± 2.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|