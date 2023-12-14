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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.5 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.38 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.36 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.33 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.3 | 1.0 | 1.07 ± 0.30 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.8 | 10.5 | 13.16 ± 3.28 |
| mattcl-ts | input-pting | 9.9 ± 0.3 | 8.8 | 10.6 | 13.23 ± 3.29 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.9 | 11.2 | 13.23 ± 3.30 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.7 | 10.6 | 13.24 ± 3.30 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 9.0 | 10.6 | 13.26 ± 3.30 |
| kcen | input-chancalan | 13.9 ± 0.4 | 12.9 | 16.6 | 18.57 ± 4.61 |
| mattcl-py | input-lanjian | 13.9 ± 0.6 | 12.9 | 17.5 | 18.59 ± 4.65 |
| kcen | input-lanjian | 13.9 ± 0.4 | 13.1 | 16.4 | 18.60 ± 4.62 |
| chancalan | input-mattcl | 13.9 ± 0.5 | 13.1 | 16.9 | 18.60 ± 4.63 |
| kcen | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.2 | 18.65 ± 4.65 |
| pting | input-kcen | 13.9 ± 0.5 | 12.9 | 16.9 | 18.66 ± 4.64 |
| mattcl-py | input-chancalan | 13.9 ± 0.6 | 13.0 | 17.3 | 18.66 ± 4.68 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.1 | 17.3 | 18.68 ± 4.67 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.1 | 16.5 | 18.68 ± 4.65 |
| chancalan | input-pting | 14.0 ± 0.6 | 13.0 | 17.5 | 18.69 ± 4.68 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.2 | 18.69 ± 4.69 |
| chancalan | input-kcen | 14.0 ± 0.6 | 13.0 | 17.6 | 18.69 ± 4.68 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.0 | 16.5 | 18.70 ± 4.66 |
| pting | input-pting | 14.0 ± 0.6 | 13.1 | 17.0 | 18.71 ± 4.68 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.0 | 17.0 | 18.71 ± 4.67 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.0 | 17.4 | 18.72 ± 4.70 |
| pting | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.1 | 18.76 ± 4.70 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.2 | 18.79 ± 4.72 |
| kcen | input-pting | 14.0 ± 0.7 | 13.2 | 17.1 | 18.80 ± 4.72 |
| pting | input-mattcl | 14.2 ± 2.4 | 13.0 | 47.5 | 19.06 ± 5.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|