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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.32 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.19 ± 0.38 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.6 | 18.7 | 17.43 ± 4.13 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.4 | 18.2 | 17.43 ± 4.13 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.7 | 18.4 | 17.57 ± 4.17 |
| mattcl-py | input-lanjian | 15.9 ± 3.5 | 14.8 | 50.2 | 17.89 ± 5.71 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.5 | 19.8 | 18.73 ± 4.45 |
| pting | input-pting | 16.7 ± 0.5 | 15.8 | 19.7 | 18.77 ± 4.43 |
| pting | input-kcen | 16.8 ± 0.7 | 15.6 | 19.8 | 18.82 ± 4.46 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.6 | 19.00 ± 4.50 |
| kcen | input-kcen | 20.0 ± 0.7 | 18.8 | 23.1 | 22.40 ± 5.29 |
| kcen | input-lanjian | 20.0 ± 0.7 | 18.7 | 22.8 | 22.40 ± 5.29 |
| kcen | input-pting | 20.1 ± 0.7 | 19.0 | 23.2 | 22.54 ± 5.32 |
| kcen | input-mattcl | 20.3 ± 0.8 | 19.2 | 23.2 | 22.74 ± 5.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|