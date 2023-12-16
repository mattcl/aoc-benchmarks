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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.11 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.15 ± 0.33 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.8 | 1.9 | 1.16 ± 0.34 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.17 ± 0.34 |
| mattcl-ts | input-lanjian | 12.7 ± 0.4 | 11.7 | 13.8 | 12.86 ± 2.57 |
| mattcl-ts | input-pting | 12.7 ± 0.3 | 11.9 | 14.0 | 12.88 ± 2.57 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.6 | 13.9 | 12.88 ± 2.57 |
| mattcl-ts | input-kcen | 13.0 ± 3.9 | 11.8 | 67.1 | 13.19 ± 4.70 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.7 | 18.4 | 15.70 ± 3.16 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.3 | 18.3 | 15.75 ± 3.17 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.3 | 19.0 | 15.77 ± 3.19 |
| mattcl-py | input-lanjian | 15.6 ± 0.7 | 14.6 | 18.6 | 15.82 ± 3.20 |
| pting | input-pting | 16.6 ± 0.7 | 15.2 | 19.6 | 16.83 ± 3.41 |
| pting | input-mattcl | 16.6 ± 0.7 | 15.3 | 19.5 | 16.85 ± 3.41 |
| pting | input-lanjian | 16.8 ± 0.8 | 15.5 | 19.5 | 17.04 ± 3.47 |
| pting | input-kcen | 16.8 ± 3.1 | 15.3 | 56.0 | 17.08 ± 4.60 |
| kcen | input-pting | 18.0 ± 0.7 | 16.9 | 21.0 | 18.26 ± 3.69 |
| kcen | input-kcen | 18.1 ± 0.6 | 17.3 | 20.8 | 18.40 ± 3.68 |
| kcen | input-lanjian | 18.2 ± 0.8 | 17.3 | 21.3 | 18.44 ± 3.73 |
| kcen | input-mattcl | 18.3 ± 0.7 | 17.1 | 21.6 | 18.54 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|