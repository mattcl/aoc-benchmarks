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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.37 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.02 ± 0.37 |
| lanjian | input-chancalan | 0.7 ± 0.1 | 0.0 | 1.0 | 1.03 ± 0.35 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.1 | 1.4 | 1.04 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.38 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.38 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.38 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.2 | 10.9 | 13.73 ± 3.80 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.1 | 10.8 | 13.79 ± 3.82 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.8 | 11.3 | 13.81 ± 3.83 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 9.1 | 11.3 | 13.83 ± 3.84 |
| mattcl-ts | input-pting | 10.1 ± 1.8 | 8.9 | 35.1 | 13.94 ± 4.57 |
| kcen | input-kcen | 14.1 ± 0.6 | 12.9 | 17.7 | 19.40 ± 5.39 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.1 | 17.1 | 19.40 ± 5.40 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.2 | 19.41 ± 5.40 |
| pting | input-lanjian | 14.1 ± 0.5 | 13.0 | 17.2 | 19.43 ± 5.39 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 12.9 | 17.6 | 19.48 ± 5.43 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.3 | 17.1 | 19.48 ± 5.41 |
| pting | input-pting | 14.1 ± 0.6 | 13.4 | 17.6 | 19.49 ± 5.43 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 13.2 | 16.7 | 19.49 ± 5.41 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.1 | 18.0 | 19.51 ± 5.44 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.0 | 17.4 | 19.53 ± 5.44 |
| pting | input-chancalan | 14.2 ± 0.7 | 12.9 | 17.6 | 19.54 ± 5.45 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.8 | 19.54 ± 5.44 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.2 | 17.2 | 19.54 ± 5.45 |
| chancalan | input-pting | 14.2 ± 0.7 | 13.3 | 17.4 | 19.58 ± 5.46 |
| pting | input-kcen | 14.2 ± 0.7 | 13.3 | 17.4 | 19.58 ± 5.47 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.5 | 17.3 | 19.59 ± 5.45 |
| kcen | input-lanjian | 14.2 ± 0.7 | 13.1 | 17.3 | 19.63 ± 5.50 |
| kcen | input-pting | 14.3 ± 0.6 | 13.2 | 17.1 | 19.67 ± 5.48 |
| kcen | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.6 | 19.68 ± 5.49 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.2 | 17.4 | 19.73 ± 5.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|