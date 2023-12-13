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
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 ± 0.35 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.35 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.5 | 1.02 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.3 | 1.0 | 1.04 ± 0.31 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.05 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.2 | 1.07 ± 0.32 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.5 | 1.08 ± 0.36 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 8.8 | 10.8 | 13.20 ± 3.24 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 9.2 | 11.4 | 13.23 ± 3.25 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 8.9 | 11.2 | 13.28 ± 3.26 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.1 | 10.8 | 13.30 ± 3.25 |
| mattcl-ts | input-mattcl | 10.3 ± 3.6 | 9.3 | 60.3 | 13.64 ± 5.77 |
| chancalan | input-kcen | 14.1 ± 0.5 | 13.0 | 16.7 | 18.65 ± 4.57 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.1 | 16.8 | 18.66 ± 4.58 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.0 | 17.3 | 18.71 ± 4.61 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.1 | 17.7 | 18.71 ± 4.62 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.7 | 18.73 ± 4.63 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.0 | 17.8 | 18.73 ± 4.59 |
| pting | input-kcen | 14.1 ± 0.5 | 12.9 | 17.2 | 18.73 ± 4.60 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.0 | 17.5 | 18.78 ± 4.62 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.5 | 18.80 ± 4.63 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.4 | 18.81 ± 4.64 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 12.9 | 17.6 | 18.81 ± 4.67 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.3 | 18.81 ± 4.63 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.2 | 16.8 | 18.81 ± 4.62 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.4 | 18.81 ± 4.64 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.5 | 18.82 ± 4.64 |
| kcen | input-pting | 14.2 ± 0.7 | 13.0 | 17.2 | 18.85 ± 4.66 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.3 | 17.9 | 18.86 ± 4.66 |
| pting | input-pting | 14.3 ± 0.7 | 13.3 | 17.0 | 18.90 ± 4.67 |
| mattcl-py | input-mattcl | 14.3 ± 0.7 | 13.0 | 20.8 | 18.90 ± 4.68 |
| mattcl-py | input-pting | 14.4 ± 3.9 | 12.9 | 68.3 | 19.06 ± 6.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|