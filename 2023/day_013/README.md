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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.5 | 1.4 | 1.01 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.5 | 1.03 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.4 | 1.03 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.7 | 1.18 ± 0.40 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.18 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.7 | 1.19 ± 0.40 |
| mattcl-py | input-kcen | 15.5 ± 0.5 | 14.4 | 18.5 | 18.33 ± 4.36 |
| mattcl-py | input-lanjian | 15.6 ± 0.8 | 14.6 | 19.1 | 18.52 ± 4.45 |
| mattcl-py | input-pting | 15.7 ± 0.6 | 14.8 | 19.5 | 18.56 ± 4.43 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 14.7 | 18.7 | 18.66 ± 4.45 |
| pting | input-kcen | 16.7 ± 0.6 | 15.5 | 19.5 | 19.75 ± 4.69 |
| pting | input-lanjian | 16.9 ± 2.2 | 15.5 | 44.3 | 19.98 ± 5.37 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.1 | 19.8 | 20.02 ± 4.77 |
| pting | input-pting | 16.9 ± 0.7 | 15.7 | 20.4 | 20.06 ± 4.80 |
| kcen | input-lanjian | 19.9 ± 0.5 | 19.0 | 22.8 | 23.58 ± 5.58 |
| kcen | input-kcen | 20.0 ± 0.8 | 19.0 | 23.3 | 23.75 ± 5.66 |
| kcen | input-pting | 20.2 ± 0.7 | 19.3 | 23.2 | 23.91 ± 5.69 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.4 | 22.9 | 24.10 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|