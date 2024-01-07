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
| lanjian | input-mikofo | 0.7 ± 0.2 | 0.0 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 0.9 | 1.02 ± 0.35 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.38 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.1 | 1.05 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.37 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.09 ± 0.36 |
| mattcl | input-mikofo | 0.8 ± 0.1 | 0.3 | 1.5 | 1.12 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.0 | 1.14 ± 0.33 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.7 | 10.7 | 13.25 ± 3.57 |
| mattcl-ts | input-mikofo | 9.9 ± 0.4 | 8.8 | 11.0 | 13.31 ± 3.58 |
| mattcl-ts | input-chancalan | 9.9 ± 0.3 | 9.1 | 10.7 | 13.34 ± 3.58 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.1 | 10.8 | 13.36 ± 3.59 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 8.8 | 10.8 | 13.37 ± 3.59 |
| pting | input-chancalan | 14.0 ± 0.4 | 13.0 | 16.3 | 18.80 ± 5.04 |
| chancalan | input-mikofo | 14.0 ± 0.5 | 13.2 | 17.2 | 18.81 ± 5.05 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.3 | 18.81 ± 5.08 |
| kcen | input-chancalan | 14.0 ± 0.5 | 13.1 | 17.4 | 18.82 ± 5.06 |
| mattcl-py | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.1 | 18.84 ± 5.07 |
| mattcl-py | input-mattcl | 14.1 ± 0.4 | 13.2 | 17.3 | 18.84 ± 5.06 |
| chancalan | input-mattcl | 14.1 ± 0.5 | 13.1 | 16.9 | 18.87 ± 5.08 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.1 | 18.91 ± 5.11 |
| kcen | input-mikofo | 14.1 ± 0.6 | 12.9 | 17.7 | 18.91 ± 5.10 |
| mattcl-py | input-chancalan | 14.1 ± 0.7 | 13.0 | 18.1 | 18.93 ± 5.14 |
| pting | input-kcen | 14.1 ± 0.6 | 13.2 | 18.0 | 18.94 ± 5.11 |
| mattcl-py | input-kcen | 14.1 ± 0.5 | 13.0 | 17.0 | 18.94 ± 5.10 |
| mattcl-py | input-mikofo | 14.1 ± 0.6 | 13.2 | 18.2 | 18.96 ± 5.13 |
| kcen | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.6 | 18.96 ± 5.11 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.1 | 19.00 ± 5.14 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.1 | 17.7 | 19.01 ± 5.16 |
| chancalan | input-kcen | 14.2 ± 0.8 | 13.2 | 17.6 | 19.02 ± 5.17 |
| pting | input-mikofo | 14.2 ± 0.7 | 13.2 | 18.0 | 19.02 ± 5.16 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.1 | 18.0 | 19.04 ± 5.15 |
| kcen | input-kcen | 14.2 ± 0.8 | 13.2 | 17.8 | 19.05 ± 5.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|