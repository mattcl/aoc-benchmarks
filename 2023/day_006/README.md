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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.33 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.33 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.32 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.32 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.7 | 10.4 | 13.15 ± 3.05 |
| mattcl-ts | input-pting | 9.7 ± 0.4 | 8.4 | 10.6 | 13.23 ± 3.06 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.7 | 10.6 | 13.24 ± 3.06 |
| mattcl-ts | input-kcen | 9.9 ± 3.5 | 8.8 | 58.6 | 13.57 ± 5.67 |
| mattcl-py | input-kcen | 13.9 ± 0.4 | 12.8 | 16.5 | 18.92 ± 4.35 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.0 | 17.0 | 18.96 ± 4.37 |
| mattcl-py | input-lanjian | 13.9 ± 0.4 | 13.1 | 17.2 | 18.97 ± 4.37 |
| kcen | input-lanjian | 13.9 ± 0.5 | 13.1 | 16.5 | 19.03 ± 4.39 |
| kcen | input-kcen | 13.9 ± 0.5 | 12.9 | 16.7 | 19.04 ± 4.39 |
| pting | input-mattcl | 14.0 ± 0.5 | 12.9 | 16.7 | 19.05 ± 4.40 |
| kcen | input-mattcl | 14.0 ± 0.5 | 12.9 | 17.0 | 19.08 ± 4.41 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 12.8 | 17.4 | 19.10 ± 4.46 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.2 | 19.10 ± 4.44 |
| pting | input-lanjian | 14.0 ± 0.7 | 13.1 | 17.6 | 19.14 ± 4.47 |
| kcen | input-pting | 14.1 ± 0.7 | 13.0 | 17.5 | 19.19 ± 4.49 |
| pting | input-pting | 14.1 ± 1.3 | 12.7 | 30.3 | 19.27 ± 4.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|