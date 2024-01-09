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
| mattcl | input-mikofo | 0.6 ± 0.3 | 0.1 | 1.1 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.1 | 1.38 ± 0.79 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.41 ± 0.81 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.46 ± 0.82 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.46 ± 0.83 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.46 ± 0.81 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.4 | 1.47 ± 0.82 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.51 ± 0.84 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.3 | 1.52 ± 0.84 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.5 | 1.57 ± 0.86 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 9.1 | 11.1 | 17.08 ± 9.00 |
| mattcl-ts | input-lanjian | 10.1 ± 0.4 | 9.0 | 11.2 | 17.08 ± 9.01 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.2 | 11.6 | 17.13 ± 9.03 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.1 | 11.7 | 17.13 ± 9.03 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.4 | 10.8 | 17.16 ± 9.04 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.6 | 23.90 ± 12.61 |
| mattcl-py | input-mattcl | 14.2 ± 0.5 | 13.1 | 17.3 | 23.97 ± 12.65 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.3 | 23.98 ± 12.66 |
| pting | input-kcen | 14.2 ± 0.6 | 13.2 | 17.7 | 24.05 ± 12.70 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.3 | 24.05 ± 12.70 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.3 | 24.06 ± 12.71 |
| kcen | input-mikofo | 14.2 ± 0.6 | 13.2 | 17.7 | 24.08 ± 12.72 |
| chancalan | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.5 | 24.09 ± 12.74 |
| mattcl-py | input-mikofo | 14.2 ± 0.6 | 13.1 | 17.3 | 24.10 ± 12.73 |
| chancalan | input-mikofo | 14.2 ± 0.7 | 13.2 | 17.7 | 24.11 ± 12.74 |
| pting | input-mikofo | 14.3 ± 0.7 | 13.3 | 17.6 | 24.15 ± 12.76 |
| pting | input-mattcl | 14.3 ± 0.5 | 13.2 | 17.4 | 24.16 ± 12.75 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.0 | 18.4 | 24.16 ± 12.76 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.3 | 17.5 | 24.17 ± 12.76 |
| kcen | input-lanjian | 14.3 ± 0.7 | 12.9 | 17.5 | 24.19 ± 12.78 |
| kcen | input-chancalan | 14.3 ± 0.6 | 13.5 | 17.6 | 24.19 ± 12.78 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.3 | 17.2 | 24.24 ± 12.81 |
| chancalan | input-kcen | 14.7 ± 3.8 | 13.1 | 53.7 | 24.94 ± 14.59 |
| pting | input-lanjian | 14.9 ± 4.7 | 12.9 | 56.6 | 25.15 ± 15.46 |
| kcen | input-kcen | 15.1 ± 4.2 | 13.6 | 44.4 | 25.57 ± 15.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|