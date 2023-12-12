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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.41 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.42 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.08 ± 0.40 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.11 ± 0.41 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.6 | 1.12 ± 0.43 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.4 | 1.12 ± 0.42 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.13 ± 0.38 |
| lanjian | input-chancalan | 0.9 ± 1.8 | 0.2 | 26.5 | 1.15 ± 2.46 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.1 | 1.15 ± 0.42 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.8 | 11.2 | 13.20 ± 3.95 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 9.0 | 11.0 | 13.21 ± 3.95 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 8.9 | 10.8 | 13.25 ± 3.96 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 8.9 | 11.0 | 13.32 ± 3.98 |
| mattcl-ts | input-pting | 10.0 ± 0.4 | 8.8 | 11.6 | 13.32 ± 3.98 |
| chancalan | input-kcen | 14.1 ± 0.6 | 12.9 | 17.4 | 18.74 ± 5.62 |
| chancalan | input-pting | 14.1 ± 0.5 | 13.2 | 17.0 | 18.79 ± 5.62 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.2 | 18.80 ± 5.63 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.0 | 17.2 | 18.81 ± 5.63 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.2 | 16.7 | 18.81 ± 5.64 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.2 | 17.4 | 18.82 ± 5.63 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.0 | 17.1 | 18.86 ± 5.65 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.0 | 17.4 | 18.86 ± 5.65 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.0 | 17.1 | 18.86 ± 5.64 |
| pting | input-kcen | 14.2 ± 0.7 | 13.3 | 17.3 | 18.88 ± 5.67 |
| pting | input-pting | 14.2 ± 0.7 | 12.9 | 18.0 | 18.88 ± 5.68 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.3 | 18.88 ± 5.65 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.5 | 18.89 ± 5.67 |
| kcen | input-pting | 14.2 ± 0.6 | 13.0 | 17.5 | 18.90 ± 5.67 |
| mattcl-py | input-lanjian | 14.2 ± 0.7 | 12.9 | 17.1 | 18.91 ± 5.68 |
| kcen | input-lanjian | 14.2 ± 0.7 | 13.0 | 17.1 | 18.95 ± 5.69 |
| chancalan | input-chancalan | 14.3 ± 0.6 | 13.4 | 17.5 | 18.95 ± 5.67 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.5 | 18.98 ± 5.71 |
| chancalan | input-lanjian | 14.3 ± 0.6 | 13.4 | 17.0 | 18.98 ± 5.68 |
| kcen | input-chancalan | 14.7 ± 3.9 | 13.2 | 55.2 | 19.58 ± 7.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|