# Day 4 benchmarks

[link to problem](https://adventofcode.com/2024/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.7 ± 0.4 | 0.7 | 2.8 | 1.00 |
| lanjian | input-lanjian | 1.7 ± 0.3 | 0.9 | 2.6 | 1.02 ± 0.30 |
| lanjian | input-mikofo | 1.7 ± 0.4 | 1.0 | 3.0 | 1.05 ± 0.33 |
| lanjian | input-kcen | 1.8 ± 0.4 | 1.0 | 2.8 | 1.07 ± 0.32 |
| mattcl | input-mattcl | 1.8 ± 0.4 | 0.9 | 2.9 | 1.07 ± 0.32 |
| mattcl | input-kcen | 1.8 ± 0.4 | 1.2 | 3.5 | 1.07 ± 0.33 |
| mattcl | input-mikofo | 1.8 ± 0.4 | 0.7 | 2.8 | 1.08 ± 0.33 |
| lanjian | input-mattcl | 1.8 ± 0.4 | 1.1 | 2.9 | 1.10 ± 0.33 |
| kcen | input-mattcl | 2.4 ± 0.3 | 1.6 | 3.8 | 1.45 ± 0.36 |
| kcen | input-mikofo | 2.4 ± 0.4 | 1.4 | 4.2 | 1.48 ± 0.38 |
| kcen | input-kcen | 2.5 ± 0.4 | 1.5 | 4.2 | 1.49 ± 0.38 |
| kcen | input-lanjian | 2.5 ± 0.3 | 1.2 | 3.7 | 1.52 ± 0.37 |
| mattcl-py | input-lanjian | 22.9 ± 0.6 | 21.9 | 25.7 | 13.89 ± 2.98 |
| mattcl-py | input-mikofo | 22.9 ± 0.7 | 21.6 | 25.9 | 13.90 ± 2.98 |
| mattcl-py | input-kcen | 23.0 ± 0.7 | 21.8 | 25.7 | 13.91 ± 2.99 |
| mattcl-py | input-mattcl | 23.0 ± 0.5 | 22.0 | 25.7 | 13.94 ± 2.98 |
| mikofo | input-kcen | 26.2 ± 0.8 | 24.7 | 29.0 | 15.87 ± 3.40 |
| mikofo | input-lanjian | 26.4 ± 0.8 | 25.0 | 30.0 | 15.99 ± 3.43 |
| mikofo | input-mikofo | 26.4 ± 0.8 | 25.3 | 29.1 | 16.01 ± 3.44 |
| mikofo | input-mattcl | 26.8 ± 0.9 | 25.6 | 30.1 | 16.22 ± 3.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|