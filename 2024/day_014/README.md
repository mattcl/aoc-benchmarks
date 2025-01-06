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
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.4 | 1.00 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.00 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.00 ± 0.19 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.6 | 1.01 ± 0.20 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.3 | 1.01 ± 0.18 |
| kcen | input-mattcl | 25.5 ± 1.0 | 24.3 | 28.9 | 17.94 ± 2.36 |
| kcen | input-lanjian | 28.3 ± 0.9 | 27.0 | 31.8 | 19.93 ± 2.59 |
| kcen | input-kcen | 32.1 ± 1.0 | 30.8 | 35.2 | 22.60 ± 2.93 |
| mattcl-py | input-mattcl | 56.1 ± 1.2 | 54.3 | 59.8 | 39.54 ± 5.06 |
| mattcl-py | input-lanjian | 60.2 ± 1.1 | 58.6 | 63.8 | 42.38 ± 5.40 |
| mattcl-py | input-kcen | 66.1 ± 1.9 | 63.4 | 74.8 | 46.57 ± 6.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|