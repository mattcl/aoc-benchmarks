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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.37 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.39 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.37 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.36 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.38 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.6 | 1.10 ± 0.38 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.0 | 1.11 ± 0.35 |
| mattcl-ts | input-mattcl | 9.7 ± 0.4 | 8.6 | 10.4 | 12.72 ± 3.55 |
| mattcl-ts | input-chancalan | 9.8 ± 0.3 | 8.7 | 10.7 | 12.75 ± 3.56 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.7 | 10.7 | 12.82 ± 3.58 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.6 | 10.8 | 12.84 ± 3.59 |
| mattcl-ts | input-lanjian | 10.3 ± 5.4 | 9.0 | 74.5 | 13.40 ± 8.00 |
| mattcl-py | input-chancalan | 14.0 ± 0.4 | 13.0 | 17.3 | 18.21 ± 5.07 |
| pting | input-chancalan | 14.0 ± 0.3 | 13.2 | 15.8 | 18.25 ± 5.07 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 12.9 | 17.2 | 18.25 ± 5.09 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 13.0 | 17.0 | 18.26 ± 5.11 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.0 | 17.4 | 18.28 ± 5.11 |
| kcen | input-pting | 14.0 ± 0.5 | 13.2 | 17.1 | 18.28 ± 5.10 |
| kcen | input-chancalan | 14.0 ± 0.5 | 13.1 | 17.5 | 18.29 ± 5.11 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.6 | 18.29 ± 5.11 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.3 | 17.2 | 18.30 ± 5.12 |
| chancalan | input-kcen | 14.0 ± 0.6 | 13.1 | 17.8 | 18.30 ± 5.12 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.2 | 18.31 ± 5.13 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.2 | 17.1 | 18.32 ± 5.12 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 13.1 | 17.3 | 18.33 ± 5.13 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.2 | 18.33 ± 5.14 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.3 | 17.7 | 18.34 ± 5.14 |
| pting | input-kcen | 14.1 ± 0.6 | 13.0 | 17.1 | 18.36 ± 5.15 |
| pting | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.4 | 18.37 ± 5.15 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.6 | 18.39 ± 5.16 |
| kcen | input-lanjian | 14.2 ± 0.8 | 13.1 | 17.5 | 18.48 ± 5.21 |
| pting | input-pting | 14.3 ± 3.1 | 13.1 | 57.1 | 18.63 ± 6.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|