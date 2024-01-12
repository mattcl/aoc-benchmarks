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
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.0 | 1.04 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.4 | 1.10 ± 0.29 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 8.9 | 10.8 | 11.55 ± 2.54 |
| mattcl-ts | input-mikofo | 9.9 ± 0.4 | 8.9 | 11.1 | 11.58 ± 2.55 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.9 | 11.1 | 11.62 ± 2.56 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.9 | 10.7 | 11.64 ± 2.56 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.9 | 11.3 | 11.65 ± 2.56 |
| chancalan | input-lanjian | 13.9 ± 0.4 | 13.0 | 16.7 | 16.29 ± 3.57 |
| chancalan | input-kcen | 14.0 ± 0.6 | 12.9 | 17.4 | 16.34 ± 3.60 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.3 | 16.36 ± 3.62 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.1 | 17.0 | 16.37 ± 3.60 |
| kcen | input-chancalan | 14.0 ± 0.5 | 13.1 | 17.1 | 16.38 ± 3.60 |
| chancalan | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.4 | 16.39 ± 3.63 |
| kcen | input-mikofo | 14.0 ± 0.6 | 12.9 | 17.1 | 16.39 ± 3.62 |
| mattcl-py | input-chancalan | 14.0 ± 0.5 | 13.0 | 16.4 | 16.39 ± 3.59 |
| pting | input-chancalan | 14.0 ± 0.5 | 13.4 | 16.7 | 16.39 ± 3.59 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.3 | 16.39 ± 3.62 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.0 | 17.4 | 16.40 ± 3.61 |
| pting | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.2 | 16.40 ± 3.62 |
| pting | input-kcen | 14.0 ± 0.5 | 13.4 | 17.0 | 16.41 ± 3.61 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.3 | 17.2 | 16.41 ± 3.62 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.3 | 16.43 ± 3.63 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.2 | 18.3 | 16.45 ± 3.65 |
| mattcl-py | input-mikofo | 14.1 ± 0.7 | 13.0 | 17.4 | 16.48 ± 3.66 |
| chancalan | input-chancalan | 14.1 ± 0.8 | 12.9 | 17.7 | 16.51 ± 3.69 |
| kcen | input-lanjian | 14.1 ± 0.7 | 12.9 | 17.4 | 16.51 ± 3.68 |
| pting | input-mikofo | 14.3 ± 3.5 | 13.0 | 55.4 | 16.77 ± 5.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|