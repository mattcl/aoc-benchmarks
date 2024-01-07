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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.39 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.0 | 1.09 ± 0.39 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.11 ± 0.39 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.12 ± 0.43 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.12 ± 0.40 |
| mattcl | input-mattcl | 0.9 ± 2.9 | 0.1 | 42.0 | 1.13 ± 3.79 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.5 | 1.15 ± 0.38 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.17 ± 0.42 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.4 | 1.18 ± 0.41 |
| mattcl-ts | input-mattcl | 9.8 ± 0.4 | 8.8 | 10.5 | 12.56 ± 3.86 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.7 | 10.8 | 12.56 ± 3.87 |
| mattcl-ts | input-mikofo | 9.8 ± 0.4 | 8.7 | 10.6 | 12.58 ± 3.87 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 9.0 | 10.8 | 12.59 ± 3.87 |
| mattcl-ts | input-lanjian | 10.1 ± 3.0 | 8.6 | 46.1 | 13.03 ± 5.53 |
| chancalan | input-mikofo | 14.0 ± 0.5 | 13.1 | 17.4 | 17.96 ± 5.53 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 13.0 | 16.7 | 17.99 ± 5.54 |
| chancalan | input-lanjian | 14.0 ± 0.5 | 12.9 | 16.6 | 17.99 ± 5.54 |
| kcen | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.8 | 18.00 ± 5.55 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.4 | 16.9 | 18.00 ± 5.53 |
| pting | input-mikofo | 14.0 ± 0.5 | 13.2 | 17.4 | 18.01 ± 5.54 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.1 | 19.7 | 18.03 ± 5.56 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.5 | 17.5 | 18.04 ± 5.56 |
| pting | input-kcen | 14.0 ± 0.6 | 13.1 | 17.7 | 18.04 ± 5.56 |
| mattcl-py | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.3 | 18.05 ± 5.56 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.2 | 18.05 ± 5.56 |
| pting | input-mattcl | 14.0 ± 0.6 | 13.4 | 17.3 | 18.06 ± 5.57 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.1 | 17.6 | 18.07 ± 5.58 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 13.0 | 17.2 | 18.08 ± 5.58 |
| kcen | input-mikofo | 14.1 ± 0.7 | 13.3 | 17.7 | 18.08 ± 5.59 |
| pting | input-chancalan | 14.1 ± 0.6 | 13.3 | 17.5 | 18.08 ± 5.58 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.6 | 18.08 ± 5.57 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.2 | 17.6 | 18.10 ± 5.60 |
| kcen | input-mattcl | 14.2 ± 2.1 | 13.0 | 42.2 | 18.23 ± 6.16 |
| mattcl-py | input-mattcl | 14.2 ± 2.6 | 13.2 | 50.8 | 18.26 ± 6.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|