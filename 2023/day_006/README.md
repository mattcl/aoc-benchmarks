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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.37 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.37 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 1.4 | 1.08 ± 0.35 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.38 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.08 ± 0.39 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.13 ± 0.37 |
| mattcl | input-mikofo | 0.8 ± 0.1 | 0.5 | 1.0 | 1.16 ± 0.34 |
| mattcl-ts | input-mikofo | 9.9 ± 0.4 | 8.7 | 11.1 | 13.46 ± 3.58 |
| mattcl-ts | input-chancalan | 9.9 ± 0.3 | 9.1 | 10.7 | 13.46 ± 3.58 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 8.9 | 10.9 | 13.53 ± 3.60 |
| mattcl-ts | input-lanjian | 9.9 ± 0.3 | 9.0 | 10.6 | 13.55 ± 3.61 |
| mattcl-ts | input-kcen | 10.2 ± 3.8 | 8.9 | 62.7 | 13.88 ± 6.29 |
| pting | input-kcen | 13.9 ± 0.4 | 13.0 | 16.7 | 18.92 ± 5.02 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.3 | 18.93 ± 5.03 |
| pting | input-mikofo | 13.9 ± 0.5 | 12.9 | 16.7 | 18.97 ± 5.04 |
| pting | input-mattcl | 13.9 ± 0.5 | 12.9 | 16.9 | 18.97 ± 5.04 |
| mattcl-py | input-mikofo | 13.9 ± 0.5 | 12.9 | 16.7 | 18.97 ± 5.05 |
| chancalan | input-lanjian | 13.9 ± 0.6 | 12.8 | 16.9 | 18.99 ± 5.08 |
| kcen | input-chancalan | 13.9 ± 0.6 | 13.1 | 17.0 | 19.01 ± 5.07 |
| chancalan | input-kcen | 13.9 ± 0.6 | 13.0 | 17.0 | 19.01 ± 5.08 |
| kcen | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.4 | 19.02 ± 5.07 |
| chancalan | input-mikofo | 13.9 ± 0.6 | 13.0 | 17.0 | 19.03 ± 5.08 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 13.2 | 17.3 | 19.05 ± 5.09 |
| kcen | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.7 | 19.05 ± 5.09 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.3 | 19.05 ± 5.11 |
| pting | input-chancalan | 14.0 ± 0.6 | 12.9 | 16.9 | 19.06 ± 5.09 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.0 | 19.07 ± 5.10 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.6 | 19.08 ± 5.13 |
| chancalan | input-mattcl | 14.0 ± 0.7 | 13.1 | 17.3 | 19.11 ± 5.13 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.3 | 17.5 | 19.12 ± 5.12 |
| kcen | input-kcen | 14.1 ± 1.9 | 12.8 | 40.0 | 19.25 ± 5.72 |
| mattcl-py | input-kcen | 14.3 ± 3.0 | 13.0 | 46.9 | 19.45 ± 6.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|