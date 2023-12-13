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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.36 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.05 ± 0.37 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.2 | 1.0 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.08 ± 0.37 |
| lanjian | input-chancalan | 0.8 ± 0.1 | 0.4 | 1.0 | 1.09 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.0 | 1.15 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.0 | 1.15 ± 0.33 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 9.0 | 10.6 | 13.16 ± 3.45 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 9.0 | 10.9 | 13.17 ± 3.45 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 9.0 | 11.0 | 13.17 ± 3.45 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.1 | 11.5 | 13.24 ± 3.47 |
| mattcl-ts | input-chancalan | 10.2 ± 2.9 | 9.2 | 51.4 | 13.39 ± 5.19 |
| mattcl-py | input-kcen | 14.1 ± 0.5 | 13.1 | 17.1 | 18.47 ± 4.84 |
| kcen | input-pting | 14.1 ± 0.5 | 13.2 | 16.6 | 18.51 ± 4.86 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.1 | 16.9 | 18.52 ± 4.89 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.2 | 17.9 | 18.52 ± 4.89 |
| pting | input-kcen | 14.2 ± 0.6 | 13.2 | 17.8 | 18.53 ± 4.88 |
| pting | input-pting | 14.2 ± 0.4 | 13.3 | 16.6 | 18.54 ± 4.85 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.0 | 17.1 | 18.55 ± 4.90 |
| chancalan | input-mattcl | 14.2 ± 0.7 | 13.1 | 17.9 | 18.56 ± 4.91 |
| chancalan | input-lanjian | 14.2 ± 0.7 | 13.0 | 18.4 | 18.57 ± 4.93 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.2 | 18.1 | 18.58 ± 4.89 |
| chancalan | input-pting | 14.2 ± 0.6 | 13.0 | 17.4 | 18.60 ± 4.91 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.4 | 17.3 | 18.61 ± 4.90 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.4 | 18.62 ± 4.90 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.2 | 17.3 | 18.66 ± 4.92 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.0 | 17.3 | 18.68 ± 4.94 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.2 | 17.6 | 18.68 ± 4.95 |
| pting | input-mattcl | 14.3 ± 0.8 | 13.0 | 17.8 | 18.73 ± 4.97 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.4 | 17.7 | 18.74 ± 4.96 |
| mattcl-py | input-chancalan | 14.3 ± 2.3 | 13.0 | 42.0 | 18.77 ± 5.71 |
| pting | input-chancalan | 14.4 ± 2.2 | 13.2 | 43.8 | 18.79 ± 5.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|