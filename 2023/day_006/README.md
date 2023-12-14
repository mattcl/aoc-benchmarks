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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.40 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.41 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.40 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.6 | 1.07 ± 0.41 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.39 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.39 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.39 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.7 | 1.11 ± 0.40 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.6 | 1.13 ± 0.38 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 8.8 | 11.4 | 13.22 ± 4.04 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 8.9 | 11.4 | 13.22 ± 4.03 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.2 | 11.0 | 13.27 ± 4.05 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.2 | 10.9 | 13.28 ± 4.05 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.0 | 10.9 | 13.30 ± 4.05 |
| kcen | input-pting | 14.1 ± 0.5 | 13.1 | 16.6 | 18.63 ± 5.68 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.1 | 17.5 | 18.63 ± 5.70 |
| chancalan | input-lanjian | 14.2 ± 0.5 | 13.0 | 17.2 | 18.69 ± 5.71 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.1 | 17.7 | 18.70 ± 5.73 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.3 | 17.6 | 18.70 ± 5.73 |
| kcen | input-chancalan | 14.2 ± 0.7 | 13.4 | 17.4 | 18.71 ± 5.74 |
| kcen | input-kcen | 14.2 ± 0.5 | 13.5 | 17.3 | 18.72 ± 5.71 |
| pting | input-kcen | 14.2 ± 0.6 | 13.4 | 17.8 | 18.72 ± 5.74 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.5 | 18.77 ± 5.74 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 12.9 | 17.9 | 18.77 ± 5.76 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.4 | 17.4 | 18.77 ± 5.75 |
| kcen | input-mattcl | 14.3 ± 0.6 | 13.4 | 18.0 | 18.78 ± 5.74 |
| mattcl-py | input-lanjian | 14.3 ± 0.7 | 13.1 | 17.4 | 18.79 ± 5.77 |
| pting | input-pting | 14.3 ± 0.6 | 13.2 | 17.4 | 18.80 ± 5.76 |
| chancalan | input-mattcl | 14.3 ± 0.6 | 13.5 | 17.5 | 18.81 ± 5.76 |
| pting | input-chancalan | 14.3 ± 0.6 | 13.1 | 17.3 | 18.84 ± 5.77 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.1 | 18.85 ± 5.78 |
| mattcl-py | input-pting | 14.3 ± 0.8 | 13.4 | 17.6 | 18.86 ± 5.81 |
| mattcl-py | input-mattcl | 14.3 ± 0.7 | 13.2 | 17.3 | 18.87 ± 5.80 |
| pting | input-lanjian | 14.4 ± 1.9 | 12.9 | 38.6 | 18.96 ± 6.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|