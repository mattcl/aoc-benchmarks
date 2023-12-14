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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.40 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.05 ± 0.41 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.39 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.40 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.40 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.12 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.0 | 1.12 ± 0.39 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.3 | 0.9 | 1.13 ± 0.36 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.1 | 1.15 ± 0.38 |
| mattcl-ts | input-chancalan | 9.8 ± 0.3 | 9.0 | 10.6 | 14.26 ± 4.14 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 9.0 | 10.9 | 14.28 ± 4.15 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.9 | 11.0 | 14.30 ± 4.15 |
| mattcl-ts | input-kcen | 9.9 ± 0.3 | 9.1 | 11.2 | 14.33 ± 4.16 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 9.0 | 10.6 | 14.35 ± 4.17 |
| kcen | input-chancalan | 13.8 ± 0.3 | 13.4 | 16.3 | 20.06 ± 5.80 |
| chancalan | input-mattcl | 13.9 ± 0.5 | 12.8 | 16.9 | 20.08 ± 5.83 |
| chancalan | input-lanjian | 13.9 ± 0.4 | 13.3 | 16.3 | 20.10 ± 5.82 |
| mattcl-py | input-chancalan | 13.9 ± 0.5 | 13.1 | 17.3 | 20.15 ± 5.86 |
| chancalan | input-pting | 13.9 ± 0.7 | 13.0 | 17.4 | 20.19 ± 5.90 |
| mattcl-py | input-kcen | 13.9 ± 0.6 | 12.9 | 17.2 | 20.19 ± 5.87 |
| mattcl-py | input-lanjian | 13.9 ± 0.6 | 12.8 | 17.5 | 20.19 ± 5.87 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 13.0 | 16.5 | 20.19 ± 5.87 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.1 | 17.6 | 20.20 ± 5.87 |
| pting | input-chancalan | 13.9 ± 0.5 | 13.1 | 16.8 | 20.21 ± 5.88 |
| pting | input-mattcl | 13.9 ± 0.6 | 13.0 | 17.2 | 20.21 ± 5.89 |
| mattcl-py | input-pting | 13.9 ± 0.6 | 13.0 | 17.3 | 20.22 ± 5.89 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.4 | 20.24 ± 5.91 |
| chancalan | input-kcen | 14.0 ± 0.6 | 12.9 | 17.3 | 20.24 ± 5.90 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.3 | 17.3 | 20.28 ± 5.94 |
| kcen | input-lanjian | 14.0 ± 0.7 | 12.8 | 17.2 | 20.30 ± 5.93 |
| kcen | input-kcen | 14.0 ± 0.7 | 12.9 | 17.5 | 20.31 ± 5.95 |
| pting | input-pting | 14.0 ± 1.8 | 13.2 | 38.7 | 20.33 ± 6.42 |
| chancalan | input-chancalan | 14.2 ± 3.4 | 13.0 | 60.6 | 20.54 ± 7.66 |
| kcen | input-pting | 14.2 ± 1.9 | 13.0 | 37.7 | 20.54 ± 6.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|