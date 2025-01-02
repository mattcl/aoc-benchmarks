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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.6 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.1 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.4 | 2.2 | 1.01 ± 0.17 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.2 | 1.02 ± 0.16 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.07 ± 0.20 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.6 | 2.4 | 1.08 ± 0.23 |
| kcen | input-mattcl | 25.7 ± 0.9 | 24.2 | 28.8 | 18.33 ± 2.22 |
| kcen | input-lanjian | 28.6 ± 1.1 | 27.0 | 32.5 | 20.37 ± 2.50 |
| kcen | input-kcen | 32.5 ± 0.8 | 31.6 | 35.9 | 23.14 ± 2.75 |
| mattcl-py | input-mattcl | 56.2 ± 1.8 | 53.8 | 64.8 | 40.02 ± 4.81 |
| mattcl-py | input-lanjian | 60.1 ± 1.1 | 58.1 | 62.6 | 42.77 ± 5.03 |
| mattcl-py | input-kcen | 65.7 ± 1.5 | 62.9 | 71.1 | 46.78 ± 5.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>214400550</pre>|<pre>8149</pre>|
|input-lanjian|<pre>229839456</pre>|<pre>7138</pre>|
|input-mattcl|<pre>219512160</pre>|<pre>6398</pre>|