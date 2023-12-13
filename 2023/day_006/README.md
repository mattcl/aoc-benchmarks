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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.46 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.44 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.09 ± 0.44 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.12 ± 0.43 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.12 ± 0.44 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.15 ± 0.44 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.3 | 1.4 | 1.15 ± 0.44 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.4 | 1.0 | 1.16 ± 0.42 |
| mattcl | input-mattcl | 0.8 ± 2.7 | 0.1 | 38.5 | 1.17 ± 3.74 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 8.8 | 10.8 | 13.77 ± 4.59 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 9.0 | 10.9 | 13.78 ± 4.60 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 8.8 | 11.1 | 13.78 ± 4.60 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.2 | 11.0 | 13.81 ± 4.60 |
| mattcl-ts | input-pting | 10.2 ± 3.4 | 9.0 | 58.2 | 14.13 ± 6.67 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.2 | 19.29 ± 6.44 |
| kcen | input-chancalan | 14.0 ± 0.4 | 12.9 | 17.1 | 19.30 ± 6.43 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.0 | 17.1 | 19.37 ± 6.47 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 13.2 | 17.0 | 19.37 ± 6.46 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.7 | 19.37 ± 6.48 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.2 | 17.1 | 19.37 ± 6.47 |
| kcen | input-kcen | 14.0 ± 0.5 | 13.1 | 17.2 | 19.37 ± 6.47 |
| pting | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.3 | 19.37 ± 6.47 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.2 | 17.6 | 19.37 ± 6.46 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.4 | 19.37 ± 6.48 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.3 | 16.4 | 19.37 ± 6.46 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 13.1 | 17.3 | 19.38 ± 6.48 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.1 | 19.40 ± 6.49 |
| chancalan | input-kcen | 14.0 ± 0.6 | 12.9 | 17.4 | 19.41 ± 6.50 |
| kcen | input-pting | 14.1 ± 0.7 | 12.9 | 17.5 | 19.45 ± 6.52 |
| pting | input-kcen | 14.1 ± 0.7 | 13.1 | 18.6 | 19.49 ± 6.54 |
| pting | input-pting | 14.1 ± 0.7 | 13.3 | 17.3 | 19.51 ± 6.54 |
| pting | input-lanjian | 14.1 ± 0.7 | 13.2 | 17.5 | 19.51 ± 6.55 |
| kcen | input-mattcl | 14.2 ± 3.0 | 12.9 | 55.2 | 19.61 ± 7.69 |
| mattcl-py | input-mattcl | 14.2 ± 2.2 | 13.1 | 43.3 | 19.69 ± 7.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|