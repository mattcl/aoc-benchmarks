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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.7 | 1.07 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.38 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.8 | 1.16 ± 0.39 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.38 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.40 |
| mattcl-ts | input-pting | 11.5 ± 0.4 | 10.4 | 12.9 | 13.43 ± 3.25 |
| mattcl-ts | input-mattcl | 11.5 ± 0.4 | 10.5 | 12.9 | 13.44 ± 3.26 |
| mattcl-ts | input-lanjian | 11.5 ± 0.4 | 10.5 | 12.6 | 13.45 ± 3.25 |
| mattcl-ts | input-kcen | 11.6 ± 0.4 | 10.6 | 12.9 | 13.49 ± 3.27 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.1 | 17.9 | 17.67 ± 4.29 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.3 | 17.76 ± 4.31 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.1 | 18.6 | 17.91 ± 4.35 |
| mattcl-py | input-pting | 15.4 ± 0.7 | 14.3 | 19.2 | 17.92 ± 4.37 |
| pting | input-kcen | 16.3 ± 0.6 | 15.1 | 18.9 | 18.96 ± 4.59 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.0 | 19.1 | 19.07 ± 4.62 |
| pting | input-pting | 16.4 ± 0.8 | 15.1 | 20.0 | 19.11 ± 4.67 |
| pting | input-lanjian | 16.4 ± 1.2 | 15.3 | 29.8 | 19.15 ± 4.80 |
| kcen | input-pting | 17.5 ± 0.7 | 16.3 | 20.5 | 20.39 ± 4.95 |
| kcen | input-lanjian | 17.6 ± 0.8 | 16.2 | 21.1 | 20.56 ± 5.01 |
| kcen | input-kcen | 17.7 ± 0.9 | 16.4 | 21.3 | 20.62 ± 5.04 |
| kcen | input-mattcl | 18.0 ± 3.1 | 16.9 | 57.1 | 20.93 ± 6.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|