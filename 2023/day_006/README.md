# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.41 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.42 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.42 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.5 | 1.05 ± 0.41 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.39 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.5 | 1.07 ± 0.41 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.09 ± 0.37 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.6 | 1.11 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.13 ± 0.38 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 8.7 | 11.8 | 13.50 ± 4.09 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.0 | 10.8 | 13.57 ± 4.10 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 8.9 | 10.8 | 13.57 ± 4.10 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 8.9 | 11.2 | 13.58 ± 4.11 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.1 | 11.3 | 13.68 ± 4.13 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.4 | 17.5 | 19.08 ± 5.79 |
| chancalan | input-lanjian | 14.2 ± 0.6 | 13.4 | 17.4 | 19.13 ± 5.80 |
| pting | input-kcen | 14.2 ± 0.5 | 13.3 | 17.1 | 19.14 ± 5.79 |
| chancalan | input-kcen | 14.2 ± 0.7 | 13.0 | 17.5 | 19.15 ± 5.82 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.1 | 17.8 | 19.17 ± 5.83 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.0 | 17.5 | 19.18 ± 5.81 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.0 | 17.4 | 19.19 ± 5.82 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.0 | 17.7 | 19.20 ± 5.84 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.0 | 18.6 | 19.20 ± 5.83 |
| pting | input-pting | 14.2 ± 0.5 | 13.3 | 17.8 | 19.21 ± 5.81 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.2 | 17.2 | 19.21 ± 5.83 |
| chancalan | input-pting | 14.2 ± 0.8 | 13.2 | 17.6 | 19.22 ± 5.86 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.3 | 19.24 ± 5.84 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.8 | 19.28 ± 5.86 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.1 | 17.6 | 19.28 ± 5.86 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.2 | 17.8 | 19.29 ± 5.85 |
| mattcl-py | input-lanjian | 14.3 ± 0.7 | 13.2 | 18.1 | 19.29 ± 5.87 |
| mattcl-py | input-mattcl | 14.3 ± 0.7 | 13.3 | 17.6 | 19.30 ± 5.88 |
| pting | input-chancalan | 14.3 ± 0.8 | 13.2 | 17.7 | 19.38 ± 5.91 |
| kcen | input-pting | 14.4 ± 2.7 | 13.4 | 50.8 | 19.53 ± 6.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|