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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.06 ± 0.47 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.47 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.09 ± 0.44 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.45 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 2.2 | 1.12 ± 0.49 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.14 ± 0.46 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.15 ± 0.46 |
| lanjian | input-chancalan | 0.8 ± 0.1 | 0.3 | 0.9 | 1.18 ± 0.43 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.4 | 0.9 | 1.18 ± 0.44 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.0 | 10.9 | 15.30 ± 5.14 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 8.9 | 11.3 | 15.31 ± 5.15 |
| mattcl-ts | input-pting | 10.0 ± 0.3 | 9.0 | 11.0 | 15.35 ± 5.16 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 8.9 | 10.9 | 15.36 ± 5.16 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.0 | 11.0 | 15.36 ± 5.16 |
| chancalan | input-lanjian | 13.9 ± 0.4 | 13.3 | 17.2 | 21.35 ± 7.16 |
| pting | input-lanjian | 14.0 ± 0.4 | 13.2 | 16.9 | 21.38 ± 7.18 |
| kcen | input-chancalan | 14.0 ± 0.5 | 12.9 | 16.5 | 21.46 ± 7.21 |
| chancalan | input-chancalan | 14.0 ± 0.5 | 13.2 | 16.9 | 21.48 ± 7.23 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.4 | 16.9 | 21.49 ± 7.22 |
| chancalan | input-kcen | 14.0 ± 0.5 | 12.8 | 16.4 | 21.49 ± 7.23 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.2 | 16.7 | 21.51 ± 7.23 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.1 | 16.9 | 21.52 ± 7.25 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.3 | 21.55 ± 7.27 |
| kcen | input-pting | 14.1 ± 0.7 | 13.1 | 17.5 | 21.56 ± 7.28 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.3 | 17.3 | 21.58 ± 7.28 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.5 | 21.58 ± 7.28 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.4 | 21.58 ± 7.30 |
| kcen | input-lanjian | 14.1 ± 0.5 | 12.8 | 16.9 | 21.61 ± 7.27 |
| pting | input-kcen | 14.1 ± 0.7 | 13.2 | 18.4 | 21.62 ± 7.30 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.3 | 17.4 | 21.63 ± 7.28 |
| pting | input-pting | 14.1 ± 0.6 | 13.2 | 17.3 | 21.64 ± 7.30 |
| pting | input-chancalan | 14.1 ± 0.7 | 13.4 | 17.5 | 21.64 ± 7.31 |
| mattcl-py | input-kcen | 14.2 ± 0.8 | 12.8 | 17.5 | 21.75 ± 7.39 |
| kcen | input-kcen | 14.3 ± 2.2 | 13.0 | 43.4 | 21.88 ± 8.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|