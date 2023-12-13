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
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.35 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.34 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.2 | 1.0 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.4 | 1.04 ± 0.38 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.35 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.06 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.3 | 1.0 | 1.07 ± 0.32 |
| mattcl-ts | input-mattcl | 9.8 ± 0.4 | 8.5 | 10.9 | 13.36 ± 3.44 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.7 | 10.5 | 13.37 ± 3.44 |
| mattcl-ts | input-lanjian | 9.8 ± 0.3 | 8.9 | 10.5 | 13.42 ± 3.45 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.9 | 11.0 | 13.45 ± 3.46 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.9 | 10.9 | 13.46 ± 3.47 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.2 | 17.9 | 19.32 ± 4.97 |
| chancalan | input-mattcl | 14.1 ± 0.5 | 12.9 | 17.0 | 19.32 ± 4.97 |
| pting | input-mattcl | 14.1 ± 0.5 | 13.0 | 16.7 | 19.34 ± 4.96 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.2 | 17.3 | 19.34 ± 5.00 |
| chancalan | input-chancalan | 14.2 ± 0.6 | 13.1 | 17.5 | 19.38 ± 4.99 |
| mattcl-py | input-pting | 14.2 ± 0.5 | 13.4 | 17.2 | 19.40 ± 4.99 |
| kcen | input-mattcl | 14.2 ± 0.6 | 12.9 | 18.4 | 19.40 ± 5.01 |
| kcen | input-pting | 14.2 ± 0.6 | 13.2 | 17.3 | 19.40 ± 5.00 |
| pting | input-pting | 14.2 ± 0.7 | 13.4 | 18.3 | 19.40 ± 5.02 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.2 | 18.3 | 19.41 ± 5.01 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.4 | 17.4 | 19.41 ± 5.01 |
| chancalan | input-pting | 14.2 ± 0.7 | 13.5 | 17.9 | 19.41 ± 5.03 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.3 | 17.0 | 19.45 ± 5.00 |
| chancalan | input-lanjian | 14.2 ± 0.8 | 13.2 | 17.4 | 19.45 ± 5.05 |
| pting | input-lanjian | 14.2 ± 0.7 | 12.9 | 17.9 | 19.45 ± 5.04 |
| mattcl-py | input-kcen | 14.2 ± 0.8 | 13.1 | 17.6 | 19.46 ± 5.06 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.2 | 19.50 ± 5.04 |
| pting | input-kcen | 14.3 ± 0.7 | 13.2 | 17.7 | 19.52 ± 5.07 |
| kcen | input-lanjian | 14.5 ± 2.9 | 13.1 | 54.4 | 19.88 ± 6.43 |
| mattcl-py | input-lanjian | 14.7 ± 4.0 | 13.1 | 49.2 | 20.06 ± 7.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|