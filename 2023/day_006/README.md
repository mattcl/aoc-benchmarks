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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.00 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.40 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.0 | 1.04 ± 0.40 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.0 | 0.9 | 1.09 ± 0.43 |
| lanjian | input-mattcl | 0.7 ± 0.1 | 0.3 | 0.9 | 1.10 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.3 | 1.0 | 1.12 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 0.9 | 1.13 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.15 ± 0.40 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.4 | 1.16 ± 0.39 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.4 | 0.9 | 1.17 ± 0.38 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.1 | 10.8 | 14.60 ± 4.22 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.1 | 11.1 | 14.62 ± 4.23 |
| mattcl-ts | input-pting | 10.0 ± 0.4 | 9.0 | 11.8 | 14.65 ± 4.25 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.1 | 10.9 | 14.71 ± 4.25 |
| mattcl-ts | input-mattcl | 10.2 ± 3.4 | 8.9 | 58.3 | 14.93 ± 6.61 |
| pting | input-chancalan | 14.0 ± 0.4 | 13.0 | 17.2 | 20.53 ± 5.94 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.1 | 20.60 ± 5.99 |
| pting | input-kcen | 14.1 ± 0.6 | 13.0 | 17.0 | 20.63 ± 5.99 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.0 | 17.2 | 20.63 ± 6.00 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 12.9 | 17.7 | 20.66 ± 6.01 |
| pting | input-pting | 14.1 ± 0.5 | 13.1 | 16.3 | 20.68 ± 5.99 |
| kcen | input-pting | 14.1 ± 0.5 | 13.2 | 17.3 | 20.68 ± 6.00 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 13.2 | 18.3 | 20.68 ± 6.02 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.1 | 17.7 | 20.69 ± 6.02 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.2 | 17.1 | 20.70 ± 6.02 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.3 | 20.71 ± 6.02 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.1 | 18.0 | 20.73 ± 6.06 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.2 | 17.0 | 20.75 ± 6.03 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.8 | 20.76 ± 6.04 |
| mattcl-py | input-lanjian | 14.2 ± 0.7 | 13.2 | 17.7 | 20.77 ± 6.07 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 12.9 | 17.1 | 20.77 ± 6.05 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.5 | 20.81 ± 6.05 |
| kcen | input-chancalan | 14.2 ± 0.7 | 13.3 | 17.5 | 20.83 ± 6.08 |
| kcen | input-lanjian | 14.3 ± 0.7 | 13.4 | 17.5 | 20.89 ± 6.10 |
| pting | input-mattcl | 14.3 ± 0.7 | 13.1 | 18.2 | 20.91 ± 6.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|