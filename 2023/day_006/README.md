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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.41 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.38 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.39 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.40 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.09 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.4 | 2.2 | 1.11 ± 0.38 |
| mattcl-ts | input-kcen | 9.2 ± 0.3 | 8.1 | 10.1 | 12.88 ± 3.56 |
| mattcl-ts | input-lanjian | 9.3 ± 0.4 | 8.2 | 10.1 | 12.95 ± 3.58 |
| mattcl-ts | input-pting | 9.3 ± 0.3 | 8.3 | 10.1 | 12.95 ± 3.58 |
| mattcl-ts | input-mattcl | 9.3 ± 0.4 | 8.3 | 10.5 | 13.05 ± 3.61 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.0 | 16.5 | 19.44 ± 5.37 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.4 | 19.45 ± 5.37 |
| mattcl-py | input-kcen | 13.9 ± 0.6 | 13.1 | 17.1 | 19.49 ± 5.40 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 12.9 | 17.4 | 19.53 ± 5.44 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.1 | 16.6 | 19.53 ± 5.40 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.1 | 17.1 | 19.53 ± 5.41 |
| pting | input-lanjian | 14.0 ± 0.6 | 12.9 | 16.8 | 19.53 ± 5.41 |
| pting | input-kcen | 14.0 ± 0.7 | 13.0 | 17.3 | 19.56 ± 5.45 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.3 | 19.57 ± 5.43 |
| pting | input-mattcl | 14.0 ± 0.7 | 12.9 | 17.7 | 19.57 ± 5.45 |
| pting | input-pting | 14.1 ± 0.7 | 13.0 | 17.1 | 19.66 ± 5.48 |
| kcen | input-lanjian | 14.1 ± 0.7 | 13.1 | 17.4 | 19.66 ± 5.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|