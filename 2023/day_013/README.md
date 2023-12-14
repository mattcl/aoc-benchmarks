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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.4 | 1.00 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.4 | 1.02 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.5 | 1.03 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.7 | 1.17 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.20 ± 0.40 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.22 ± 0.41 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.7 | 2.4 | 1.22 ± 0.41 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.7 | 19.3 | 18.47 ± 4.37 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.7 | 18.3 | 18.54 ± 4.39 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.6 | 19.5 | 18.71 ± 4.44 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.8 | 18.7 | 18.77 ± 4.47 |
| pting | input-lanjian | 16.9 ± 0.6 | 15.6 | 20.6 | 19.88 ± 4.71 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.0 | 20.2 | 20.10 ± 4.77 |
| pting | input-pting | 17.1 ± 0.7 | 16.0 | 20.6 | 20.17 ± 4.79 |
| pting | input-kcen | 17.6 ± 4.2 | 16.1 | 58.7 | 20.65 ± 6.94 |
| kcen | input-kcen | 20.1 ± 0.8 | 18.6 | 23.7 | 23.68 ± 5.62 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.3 | 22.6 | 23.74 ± 5.60 |
| kcen | input-pting | 20.3 ± 0.7 | 19.4 | 23.4 | 23.85 ± 5.63 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.5 | 23.2 | 24.05 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|