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
| mattcl | input-lanjian | 1.0 ± 0.4 | 0.3 | 2.3 | 1.00 |
| lanjian | input-lanjian | 1.4 ± 0.3 | 0.3 | 2.2 | 1.35 ± 0.60 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.8 | 1.8 | 1.40 ± 0.58 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.3 | 1.42 ± 0.59 |
| mattcl | input-kcen | 1.4 ± 0.2 | 1.0 | 2.2 | 1.42 ± 0.59 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.6 | 2.4 | 1.43 ± 0.60 |
| kcen | input-mattcl | 25.7 ± 1.0 | 24.5 | 29.0 | 25.44 ± 10.23 |
| kcen | input-lanjian | 28.1 ± 0.7 | 27.0 | 31.6 | 27.85 ± 11.17 |
| kcen | input-kcen | 32.1 ± 0.8 | 30.7 | 34.7 | 31.81 ± 12.76 |
| mattcl-py | input-mattcl | 56.8 ± 1.2 | 54.8 | 60.9 | 56.23 ± 22.54 |
| mattcl-py | input-lanjian | 60.9 ± 1.3 | 58.8 | 64.7 | 60.34 ± 24.19 |
| mattcl-py | input-kcen | 66.6 ± 1.9 | 64.2 | 73.2 | 65.98 ± 26.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|