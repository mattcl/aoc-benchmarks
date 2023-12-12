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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.43 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 0.9 | 1.06 ± 0.39 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.07 ± 0.39 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.41 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.11 ± 0.40 |
| lanjian | input-chancalan | 0.7 ± 0.1 | 0.4 | 0.9 | 1.11 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.4 | 1.12 ± 0.41 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.4 | 0.9 | 1.13 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.2 | 1.15 ± 0.39 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 8.8 | 10.8 | 14.69 ± 4.43 |
| mattcl-ts | input-kcen | 9.9 ± 0.3 | 9.1 | 10.8 | 14.70 ± 4.43 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.6 | 10.6 | 14.72 ± 4.43 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.5 | 10.7 | 14.75 ± 4.45 |
| mattcl-ts | input-chancalan | 9.9 ± 0.3 | 8.8 | 10.7 | 14.81 ± 4.46 |
| chancalan | input-lanjian | 13.8 ± 0.4 | 13.0 | 16.3 | 20.61 ± 6.19 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 17.3 | 20.62 ± 6.21 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 12.9 | 17.0 | 20.66 ± 6.22 |
| kcen | input-kcen | 13.9 ± 0.5 | 12.9 | 17.2 | 20.67 ± 6.22 |
| chancalan | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.1 | 20.68 ± 6.24 |
| kcen | input-chancalan | 13.9 ± 0.4 | 13.0 | 16.9 | 20.69 ± 6.22 |
| chancalan | input-pting | 13.9 ± 0.6 | 12.9 | 16.7 | 20.71 ± 6.26 |
| chancalan | input-chancalan | 13.9 ± 0.5 | 12.7 | 16.6 | 20.71 ± 6.24 |
| pting | input-mattcl | 13.9 ± 0.6 | 12.8 | 17.2 | 20.71 ± 6.25 |
| kcen | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.6 | 20.72 ± 6.24 |
| kcen | input-mattcl | 13.9 ± 0.6 | 13.0 | 16.7 | 20.72 ± 6.25 |
| kcen | input-pting | 13.9 ± 0.5 | 13.1 | 16.6 | 20.73 ± 6.24 |
| pting | input-pting | 13.9 ± 0.5 | 13.0 | 17.2 | 20.73 ± 6.25 |
| pting | input-kcen | 13.9 ± 0.6 | 13.0 | 17.3 | 20.74 ± 6.26 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.5 | 20.78 ± 6.28 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.2 | 20.79 ± 6.28 |
| pting | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.4 | 20.82 ± 6.30 |
| chancalan | input-kcen | 14.1 ± 2.0 | 12.8 | 39.9 | 20.96 ± 6.92 |
| mattcl-py | input-chancalan | 14.1 ± 2.0 | 12.9 | 41.3 | 21.05 ± 6.99 |
| mattcl-py | input-lanjian | 14.1 ± 2.7 | 13.0 | 50.8 | 21.05 ± 7.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|