# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.5 | 1.03 ± 0.36 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.09 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.14 ± 0.37 |
| mattcl | input-mattcl | 1.0 ± 2.8 | 0.5 | 40.1 | 1.16 ± 3.19 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.6 | 1.6 | 1.17 ± 0.41 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.40 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.6 | 18.9 | 17.97 ± 4.43 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.5 | 19.0 | 17.98 ± 4.45 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.6 | 18.6 | 18.13 ± 4.49 |
| mattcl-py | input-mattcl | 16.3 ± 4.3 | 14.6 | 57.4 | 18.59 ± 6.66 |
| pting | input-pting | 17.0 ± 0.5 | 16.2 | 19.6 | 19.40 ± 4.76 |
| pting | input-kcen | 17.0 ± 0.7 | 16.1 | 19.9 | 19.43 ± 4.79 |
| pting | input-lanjian | 17.1 ± 2.7 | 15.7 | 52.0 | 19.55 ± 5.68 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.2 | 19.8 | 19.65 ± 4.86 |
| kcen | input-lanjian | 20.1 ± 0.6 | 19.2 | 22.5 | 22.94 ± 5.64 |
| kcen | input-kcen | 20.2 ± 0.8 | 18.9 | 23.3 | 23.02 ± 5.68 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.5 | 23.4 | 23.42 ± 5.77 |
| kcen | input-pting | 20.6 ± 0.9 | 19.5 | 24.0 | 23.47 ± 5.80 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|