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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.1 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.21 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.4 | 2.2 | 1.04 ± 0.20 |
| lanjian | input-lanjian | 1.4 ± 0.1 | 0.8 | 1.7 | 1.05 ± 0.18 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.05 ± 0.20 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.6 | 2.5 | 1.05 ± 0.22 |
| kcen | input-lanjian | 2.3 ± 0.3 | 1.4 | 3.6 | 1.74 ± 0.36 |
| kcen | input-kcen | 2.4 ± 0.4 | 1.5 | 4.4 | 1.75 ± 0.40 |
| kcen | input-mikofo | 2.5 ± 0.3 | 1.5 | 3.1 | 1.84 ± 0.35 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.7 | 3.2 | 1.84 ± 0.35 |
| mikofo | input-kcen | 18.3 ± 0.8 | 17.1 | 21.2 | 13.56 ± 2.17 |
| mikofo | input-lanjian | 18.4 ± 0.7 | 17.3 | 21.3 | 13.69 ± 2.17 |
| mattcl-py | input-mikofo | 18.5 ± 0.8 | 17.3 | 21.8 | 13.71 ± 2.20 |
| mattcl-py | input-mattcl | 18.5 ± 0.5 | 17.4 | 21.7 | 13.73 ± 2.16 |
| mattcl-py | input-lanjian | 18.8 ± 0.5 | 17.9 | 21.0 | 13.97 ± 2.18 |
| mikofo | input-mattcl | 18.9 ± 0.7 | 17.8 | 21.6 | 14.06 ± 2.22 |
| mattcl-py | input-kcen | 19.0 ± 0.5 | 17.9 | 21.7 | 14.07 ± 2.21 |
| mikofo | input-mikofo | 19.3 ± 0.7 | 18.1 | 22.5 | 14.31 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>680</pre>|<pre>710</pre>|
|input-lanjian|<pre>564</pre>|<pre>604</pre>|
|input-mattcl|<pre>332</pre>|<pre>398</pre>|
|input-mikofo|<pre>224</pre>|<pre>293</pre>|