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
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.38 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.3 | 1.03 ± 0.38 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.37 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.05 ± 0.35 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.37 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.5 | 1.06 ± 0.37 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.2 | 0.9 | 1.07 ± 0.36 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.5 | 1.09 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.3 | 1.4 | 1.13 ± 0.35 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.5 | 11.1 | 14.19 ± 3.84 |
| mattcl-ts | input-kcen | 9.9 ± 0.3 | 8.9 | 11.0 | 14.23 ± 3.84 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.2 | 10.7 | 14.32 ± 3.87 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 8.9 | 10.9 | 14.33 ± 3.87 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.9 | 11.3 | 14.34 ± 3.88 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.2 | 20.00 ± 5.42 |
| pting | input-chancalan | 14.0 ± 0.5 | 12.8 | 17.8 | 20.01 ± 5.42 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.3 | 20.01 ± 5.43 |
| pting | input-lanjian | 14.0 ± 0.5 | 12.8 | 17.4 | 20.03 ± 5.42 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.1 | 16.8 | 20.06 ± 5.42 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.2 | 17.2 | 20.07 ± 5.45 |
| kcen | input-mattcl | 14.0 ± 0.5 | 12.9 | 17.0 | 20.08 ± 5.43 |
| mattcl-py | input-kcen | 14.0 ± 0.7 | 12.8 | 17.8 | 20.08 ± 5.46 |
| kcen | input-lanjian | 14.0 ± 0.6 | 12.9 | 18.2 | 20.10 ± 5.46 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.0 | 17.8 | 20.11 ± 5.46 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.2 | 20.12 ± 5.46 |
| pting | input-pting | 14.0 ± 0.6 | 12.8 | 17.0 | 20.13 ± 5.47 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.6 | 20.14 ± 5.47 |
| kcen | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.7 | 20.17 ± 5.48 |
| chancalan | input-kcen | 14.1 ± 0.7 | 12.9 | 17.8 | 20.18 ± 5.51 |
| mattcl-py | input-chancalan | 14.1 ± 0.7 | 12.9 | 17.9 | 20.20 ± 5.51 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 12.8 | 17.2 | 20.21 ± 5.46 |
| kcen | input-pting | 14.1 ± 0.6 | 13.2 | 17.2 | 20.25 ± 5.50 |
| pting | input-mattcl | 14.2 ± 0.7 | 12.9 | 17.6 | 20.28 ± 5.54 |
| mattcl-py | input-pting | 14.3 ± 3.5 | 12.9 | 62.9 | 20.56 ± 7.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|