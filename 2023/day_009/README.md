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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.02 ± 0.26 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 2.9 | 0.2 | 41.8 | 1.10 ± 3.25 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.34 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.35 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.7 | 1.8 | 1.16 ± 0.37 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.6 | 13.3 | 13.94 ± 2.83 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.4 | 13.5 | 13.95 ± 2.83 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.3 | 13.98 ± 2.84 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.5 | 13.99 ± 2.84 |
| mattcl-py | input-mattcl | 15.2 ± 0.5 | 14.3 | 18.4 | 16.87 ± 3.44 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.0 | 17.8 | 16.90 ± 3.46 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.2 | 18.6 | 16.93 ± 3.49 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.4 | 18.8 | 16.98 ± 3.49 |
| pting | input-pting | 16.2 ± 0.6 | 15.2 | 18.6 | 18.03 ± 3.68 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.5 | 19.5 | 18.11 ± 3.70 |
| pting | input-lanjian | 16.4 ± 0.7 | 15.3 | 19.6 | 18.22 ± 3.75 |
| pting | input-kcen | 16.6 ± 3.5 | 15.0 | 58.9 | 18.44 ± 5.41 |
| kcen | input-pting | 17.4 ± 0.7 | 16.5 | 20.7 | 19.39 ± 3.97 |
| kcen | input-kcen | 17.6 ± 0.6 | 16.8 | 20.9 | 19.54 ± 3.99 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.5 | 20.8 | 19.60 ± 4.01 |
| kcen | input-lanjian | 17.8 ± 2.4 | 16.6 | 47.0 | 19.76 ± 4.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|