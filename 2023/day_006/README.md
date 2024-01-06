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
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.30 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.28 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.1 | 1.07 ± 0.25 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.08 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.1 | 1.08 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.2 | 1.10 ± 0.27 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.2 | 10.9 | 11.58 ± 2.40 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.3 | 11.0 | 11.63 ± 2.41 |
| mattcl-ts | input-lanjian | 10.2 ± 0.3 | 9.3 | 11.0 | 11.65 ± 2.41 |
| mattcl-ts | input-mattcl | 10.2 ± 0.3 | 9.2 | 11.0 | 11.65 ± 2.42 |
| mattcl-ts | input-chancalan | 10.2 ± 0.3 | 9.3 | 11.0 | 11.65 ± 2.41 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.5 | 16.25 ± 3.41 |
| pting | input-chancalan | 14.2 ± 0.5 | 13.5 | 18.0 | 16.27 ± 3.38 |
| kcen | input-mikofo | 14.2 ± 0.5 | 13.4 | 17.1 | 16.29 ± 3.39 |
| mattcl-py | input-mikofo | 14.2 ± 0.7 | 12.9 | 17.7 | 16.32 ± 3.43 |
| chancalan | input-kcen | 14.2 ± 0.7 | 13.2 | 17.9 | 16.33 ± 3.44 |
| chancalan | input-lanjian | 14.3 ± 0.6 | 13.1 | 17.5 | 16.35 ± 3.42 |
| mattcl-py | input-mattcl | 14.3 ± 0.5 | 13.2 | 17.3 | 16.35 ± 3.41 |
| kcen | input-kcen | 14.3 ± 0.7 | 13.3 | 17.3 | 16.36 ± 3.44 |
| kcen | input-chancalan | 14.3 ± 0.7 | 12.9 | 17.8 | 16.37 ± 3.44 |
| chancalan | input-chancalan | 14.3 ± 0.6 | 13.5 | 17.2 | 16.38 ± 3.43 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.0 | 17.7 | 16.39 ± 3.46 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.0 | 17.7 | 16.39 ± 3.43 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.4 | 18.3 | 16.39 ± 3.45 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.5 | 17.2 | 16.41 ± 3.43 |
| pting | input-mikofo | 14.3 ± 0.7 | 13.2 | 17.6 | 16.42 ± 3.46 |
| chancalan | input-mattcl | 14.3 ± 1.5 | 13.3 | 33.8 | 16.45 ± 3.76 |
| kcen | input-mattcl | 14.4 ± 0.6 | 13.2 | 17.1 | 16.46 ± 3.45 |
| pting | input-kcen | 14.4 ± 0.7 | 13.0 | 18.0 | 16.49 ± 3.47 |
| chancalan | input-mikofo | 14.4 ± 3.3 | 13.0 | 60.7 | 16.50 ± 5.11 |
| pting | input-lanjian | 14.4 ± 0.8 | 13.3 | 17.9 | 16.52 ± 3.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|