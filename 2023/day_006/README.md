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
| lanjian | input-mattcl | 0.5 ± 1.5 | 0.1 | 21.5 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 3.0 | 0.1 | 42.8 | 1.31 ± 6.67 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.2 | 1.48 ± 4.17 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.3 | 1.5 | 1.49 ± 4.19 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.50 ± 4.21 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.51 ± 4.24 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.55 ± 4.36 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.55 ± 4.36 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.3 | 1.0 | 1.57 ± 4.40 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.60 ± 4.51 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 8.9 | 10.8 | 18.54 ± 52.02 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.0 | 11.2 | 18.56 ± 52.08 |
| mattcl-ts | input-mikofo | 10.0 ± 0.3 | 9.0 | 11.1 | 18.58 ± 52.13 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 8.8 | 11.1 | 18.64 ± 52.31 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.1 | 11.1 | 18.66 ± 52.36 |
| kcen | input-kcen | 14.1 ± 0.5 | 13.4 | 17.4 | 26.11 ± 73.28 |
| pting | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.1 | 26.12 ± 73.29 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.1 | 17.3 | 26.14 ± 73.35 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.3 | 16.8 | 26.14 ± 73.36 |
| chancalan | input-lanjian | 14.1 ± 0.7 | 13.2 | 17.5 | 26.16 ± 73.41 |
| kcen | input-lanjian | 14.1 ± 0.7 | 12.9 | 18.4 | 26.18 ± 73.46 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.3 | 17.7 | 26.19 ± 73.49 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.8 | 26.19 ± 73.49 |
| mattcl-py | input-kcen | 14.1 ± 0.6 | 12.9 | 17.7 | 26.19 ± 73.49 |
| mattcl-py | input-mikofo | 14.1 ± 0.6 | 13.0 | 17.2 | 26.19 ± 73.49 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.4 | 26.20 ± 73.53 |
| kcen | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.3 | 26.21 ± 73.56 |
| pting | input-kcen | 14.1 ± 0.6 | 12.9 | 17.4 | 26.23 ± 73.61 |
| kcen | input-mikofo | 14.2 ± 0.7 | 13.2 | 17.4 | 26.23 ± 73.62 |
| pting | input-chancalan | 14.2 ± 0.7 | 12.9 | 17.9 | 26.24 ± 73.64 |
| pting | input-mikofo | 14.2 ± 0.6 | 13.5 | 18.2 | 26.25 ± 73.67 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.1 | 17.5 | 26.29 ± 73.79 |
| mattcl-py | input-lanjian | 14.3 ± 0.8 | 13.2 | 17.7 | 26.49 ± 74.34 |
| chancalan | input-mikofo | 14.4 ± 3.1 | 12.8 | 46.6 | 26.67 ± 75.07 |
| kcen | input-mattcl | 14.6 ± 0.7 | 13.4 | 21.0 | 27.03 ± 75.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|