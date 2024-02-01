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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.30 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.6 | 1.06 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.07 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.09 ± 0.34 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.10 ± 0.34 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.35 |
| mattcl-ts | input-pting | 12.3 ± 0.4 | 11.2 | 13.4 | 13.02 ± 2.73 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 10.9 | 13.4 | 13.06 ± 2.74 |
| mattcl-ts | input-kcen | 12.3 ± 0.4 | 11.1 | 13.2 | 13.06 ± 2.74 |
| mattcl-ts | input-lanjian | 12.3 ± 0.4 | 11.3 | 13.4 | 13.06 ± 2.74 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.6 | 16.24 ± 3.43 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.4 | 18.1 | 16.25 ± 3.44 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.2 | 18.1 | 16.27 ± 3.44 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.3 | 17.5 | 16.27 ± 3.44 |
| pting | input-pting | 16.2 ± 0.6 | 15.2 | 19.7 | 17.22 ± 3.62 |
| pting | input-lanjian | 16.3 ± 0.6 | 14.9 | 19.7 | 17.27 ± 3.64 |
| pting | input-kcen | 16.4 ± 0.8 | 14.9 | 19.6 | 17.37 ± 3.70 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.2 | 19.1 | 17.38 ± 3.67 |
| kcen | input-pting | 17.5 ± 0.6 | 16.1 | 20.7 | 18.58 ± 3.91 |
| kcen | input-mattcl | 17.7 ± 0.8 | 16.3 | 20.5 | 18.80 ± 3.99 |
| kcen | input-lanjian | 17.8 ± 0.8 | 17.0 | 20.9 | 18.83 ± 3.99 |
| kcen | input-kcen | 17.8 ± 0.7 | 16.8 | 21.1 | 18.83 ± 3.98 |
| chancalan | input-pting | 19.8 ± 0.8 | 18.8 | 23.2 | 21.00 ± 4.44 |
| chancalan | input-mattcl | 19.9 ± 0.7 | 18.5 | 22.3 | 21.08 ± 4.43 |
| chancalan | input-kcen | 20.0 ± 0.7 | 19.0 | 22.8 | 21.24 ± 4.48 |
| chancalan | input-lanjian | 20.0 ± 0.7 | 19.0 | 22.8 | 21.24 ± 4.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|