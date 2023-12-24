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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.03 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.10 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.37 |
| mattcl-py | input-lanjian | 15.8 ± 0.6 | 14.8 | 18.3 | 16.92 ± 4.02 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.7 | 18.5 | 17.05 ± 4.05 |
| mattcl-py | input-kcen | 15.9 ± 0.8 | 14.8 | 19.1 | 17.07 ± 4.09 |
| mattcl-py | input-mattcl | 16.0 ± 0.8 | 14.8 | 19.4 | 17.23 ± 4.14 |
| pting | input-kcen | 17.0 ± 0.6 | 15.7 | 20.0 | 18.22 ± 4.33 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.0 | 20.0 | 18.30 ± 4.35 |
| pting | input-mattcl | 17.4 ± 2.4 | 16.3 | 48.0 | 18.66 ± 5.10 |
| pting | input-pting | 17.5 ± 3.6 | 16.1 | 60.4 | 18.79 ± 5.85 |
| kcen | input-lanjian | 20.2 ± 0.8 | 19.0 | 23.8 | 21.67 ± 5.15 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.2 | 23.6 | 21.72 ± 5.16 |
| kcen | input-pting | 20.5 ± 0.8 | 19.4 | 23.3 | 21.98 ± 5.22 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.6 | 23.6 | 22.22 ± 5.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|