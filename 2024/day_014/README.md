# Day 14 benchmarks

[link to problem](https://adventofcode.com/2024/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.4 | 0.3 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.4 | 0.2 | 2.2 | 1.07 ± 0.53 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.6 | 1.26 ± 0.48 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.3 | 2.2 | 1.27 ± 0.48 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.5 | 2.7 | 1.28 ± 0.49 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.6 | 1.29 ± 0.49 |
| kcen | input-mattcl | 25.8 ± 1.1 | 24.6 | 29.3 | 23.19 ± 8.07 |
| kcen | input-lanjian | 28.5 ± 0.9 | 27.2 | 32.0 | 25.62 ± 8.89 |
| kcen | input-kcen | 32.6 ± 1.1 | 30.8 | 36.1 | 29.29 ± 10.16 |
| mattcl-py | input-mattcl | 56.4 ± 1.2 | 54.7 | 59.4 | 50.75 ± 17.56 |
| mattcl-py | input-lanjian | 60.9 ± 1.5 | 58.9 | 68.0 | 54.80 ± 18.98 |
| mattcl-py | input-kcen | 65.4 ± 1.5 | 63.4 | 70.4 | 58.85 ± 20.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|