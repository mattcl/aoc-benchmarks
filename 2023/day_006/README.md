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
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.04 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.28 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.4 | 1.05 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.4 | 1.2 | 1.07 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.6 | 1.1 | 1.08 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.29 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 8.7 | 11.0 | 11.47 ± 2.64 |
| mattcl-ts | input-kcen | 10.0 ± 0.4 | 8.9 | 11.1 | 11.56 ± 2.66 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 9.1 | 10.8 | 11.58 ± 2.66 |
| mattcl-ts | input-mikofo | 10.0 ± 0.3 | 9.0 | 10.9 | 11.60 ± 2.67 |
| mattcl-ts | input-lanjian | 10.2 ± 3.0 | 8.9 | 51.5 | 11.78 ± 4.35 |
| kcen | input-mikofo | 14.0 ± 0.4 | 13.0 | 16.4 | 16.17 ± 3.70 |
| mattcl-py | input-kcen | 14.0 ± 0.3 | 13.2 | 17.0 | 16.18 ± 3.70 |
| chancalan | input-mikofo | 14.0 ± 0.5 | 13.2 | 17.6 | 16.19 ± 3.73 |
| pting | input-kcen | 14.0 ± 0.5 | 13.2 | 16.6 | 16.21 ± 3.72 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.3 | 17.5 | 16.21 ± 3.74 |
| mattcl-py | input-mattcl | 14.0 ± 0.4 | 13.1 | 17.2 | 16.22 ± 3.72 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 13.1 | 17.2 | 16.24 ± 3.75 |
| kcen | input-chancalan | 14.0 ± 0.5 | 13.3 | 16.9 | 16.24 ± 3.74 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.5 | 17.2 | 16.25 ± 3.74 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.3 | 16.26 ± 3.76 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.1 | 17.7 | 16.26 ± 3.78 |
| pting | input-chancalan | 14.1 ± 0.5 | 13.1 | 17.3 | 16.27 ± 3.74 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.3 | 17.7 | 16.27 ± 3.75 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.4 | 16.29 ± 3.76 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.2 | 16.29 ± 3.77 |
| pting | input-mikofo | 14.1 ± 0.5 | 13.4 | 16.6 | 16.30 ± 3.75 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.1 | 16.9 | 16.32 ± 3.77 |
| chancalan | input-chancalan | 14.1 ± 0.7 | 13.1 | 17.2 | 16.32 ± 3.79 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.3 | 17.5 | 16.34 ± 3.79 |
| mattcl-py | input-mikofo | 14.1 ± 0.7 | 12.9 | 17.2 | 16.35 ± 3.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|