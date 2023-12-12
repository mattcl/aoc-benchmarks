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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.33 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.32 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.5 | 1.03 ± 0.33 |
| lanjian | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.1 | 1.06 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.08 ± 0.30 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 9.3 | 11.1 | 12.50 ± 2.85 |
| mattcl-ts | input-lanjian | 10.1 ± 0.4 | 8.7 | 11.3 | 12.59 ± 2.88 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 8.8 | 11.2 | 12.60 ± 2.87 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.3 | 11.1 | 12.63 ± 2.87 |
| mattcl-ts | input-kcen | 10.1 ± 0.4 | 9.2 | 11.1 | 12.64 ± 2.88 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.1 | 17.4 | 17.56 ± 4.02 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 13.3 | 17.4 | 17.61 ± 4.03 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.5 | 17.64 ± 4.05 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.3 | 17.65 ± 4.04 |
| chancalan | input-mattcl | 14.2 ± 0.7 | 13.1 | 17.4 | 17.65 ± 4.08 |
| pting | input-pting | 14.2 ± 0.6 | 13.2 | 17.7 | 17.65 ± 4.04 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.2 | 18.0 | 17.66 ± 4.05 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.4 | 17.67 ± 4.05 |
| chancalan | input-lanjian | 14.2 ± 0.7 | 13.2 | 17.3 | 17.67 ± 4.06 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.0 | 17.5 | 17.67 ± 4.06 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.0 | 17.7 | 17.67 ± 4.08 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.5 | 16.8 | 17.69 ± 4.05 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.0 | 17.0 | 17.71 ± 4.07 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.1 | 17.71 ± 4.05 |
| mattcl-py | input-mattcl | 14.2 ± 0.7 | 13.1 | 17.6 | 17.73 ± 4.09 |
| pting | input-kcen | 14.3 ± 0.7 | 13.4 | 17.9 | 17.81 ± 4.12 |
| kcen | input-mattcl | 14.3 ± 0.7 | 13.4 | 17.7 | 17.83 ± 4.12 |
| kcen | input-lanjian | 14.3 ± 0.8 | 13.1 | 18.3 | 17.86 ± 4.16 |
| kcen | input-pting | 14.3 ± 2.8 | 13.3 | 53.1 | 17.86 ± 5.33 |
| chancalan | input-pting | 14.6 ± 3.6 | 13.1 | 47.1 | 18.21 ± 6.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|