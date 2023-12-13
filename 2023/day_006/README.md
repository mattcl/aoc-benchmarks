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
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.38 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.4 | 1.06 ± 0.39 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.37 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.37 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.38 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.09 ± 0.38 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.2 | 1.09 ± 0.38 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.4 | 1.11 ± 0.36 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.0 | 1.14 ± 0.36 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 9.1 | 11.7 | 14.48 ± 3.89 |
| mattcl-ts | input-pting | 10.0 ± 0.3 | 9.1 | 10.7 | 14.49 ± 3.87 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 8.9 | 11.2 | 14.50 ± 3.88 |
| mattcl-ts | input-lanjian | 10.0 ± 0.4 | 9.0 | 10.8 | 14.52 ± 3.89 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 9.0 | 11.6 | 14.54 ± 3.89 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.8 | 20.40 ± 5.49 |
| pting | input-pting | 14.0 ± 0.6 | 12.8 | 17.5 | 20.43 ± 5.49 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 13.0 | 17.6 | 20.43 ± 5.48 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.3 | 16.7 | 20.43 ± 5.47 |
| kcen | input-kcen | 14.1 ± 0.6 | 12.8 | 17.3 | 20.51 ± 5.52 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 12.8 | 17.6 | 20.51 ± 5.52 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.4 | 16.7 | 20.52 ± 5.49 |
| pting | input-chancalan | 14.1 ± 0.6 | 12.8 | 16.9 | 20.54 ± 5.51 |
| kcen | input-chancalan | 14.1 ± 0.6 | 13.0 | 17.6 | 20.55 ± 5.53 |
| pting | input-mattcl | 14.1 ± 0.5 | 13.0 | 17.4 | 20.55 ± 5.50 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.3 | 17.3 | 20.56 ± 5.53 |
| chancalan | input-pting | 14.1 ± 0.7 | 12.9 | 17.6 | 20.58 ± 5.56 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 12.8 | 17.7 | 20.59 ± 5.53 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.5 | 20.60 ± 5.54 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.2 | 17.1 | 20.62 ± 5.56 |
| kcen | input-pting | 14.2 ± 0.6 | 13.3 | 17.6 | 20.62 ± 5.54 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.4 | 17.7 | 20.67 ± 5.58 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.5 | 17.3 | 20.72 ± 5.58 |
| pting | input-kcen | 14.2 ± 0.8 | 13.2 | 17.4 | 20.72 ± 5.61 |
| chancalan | input-kcen | 14.4 ± 4.7 | 13.1 | 73.6 | 20.98 ± 8.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|