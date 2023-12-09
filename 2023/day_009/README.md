# Day 9 benchmarks

[link to problem](https://adventofcode.com/2023/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.30 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.14 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.18 ± 0.39 |
| mattcl-ts | input-lanjian | 11.8 ± 0.3 | 11.1 | 12.8 | 14.10 ± 3.09 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.7 | 13.3 | 14.19 ± 3.11 |
| mattcl-ts | input-mattcl | 11.9 ± 0.3 | 11.0 | 12.9 | 14.21 ± 3.11 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.7 | 19.2 | 20.01 ± 4.40 |
| pting | input-kcen | 16.9 ± 0.7 | 15.5 | 20.5 | 20.13 ± 4.45 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.1 | 20.4 | 20.15 ± 4.44 |
| kcen | input-mattcl | 17.4 ± 0.6 | 16.5 | 20.3 | 20.69 ± 4.55 |
| kcen | input-lanjian | 17.4 ± 0.6 | 16.5 | 20.2 | 20.71 ± 4.56 |
| mattcl-py | input-kcen | 17.4 ± 0.7 | 16.5 | 20.7 | 20.75 ± 4.58 |
| kcen | input-kcen | 17.4 ± 0.7 | 16.4 | 20.1 | 20.76 ± 4.58 |
| mattcl-py | input-lanjian | 17.5 ± 0.7 | 16.7 | 20.8 | 20.80 ± 4.59 |
| mattcl-py | input-mattcl | 18.4 ± 6.3 | 16.4 | 62.0 | 21.90 ± 8.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|