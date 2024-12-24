# Day 11 benchmarks

[link to problem](https://adventofcode.com/2024/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 3.4 ± 0.5 | 2.5 | 6.4 | 1.00 |
| mattcl | input-lanjian | 3.5 ± 0.4 | 2.6 | 6.8 | 1.02 ± 0.20 |
| mattcl | input-mattcl | 3.7 ± 0.4 | 2.8 | 6.5 | 1.08 ± 0.21 |
| lanjian | input-lanjian | 11.1 ± 0.4 | 10.3 | 13.4 | 3.26 ± 0.51 |
| lanjian | input-mattcl | 11.6 ± 0.5 | 10.5 | 14.0 | 3.42 ± 0.55 |
| lanjian | input-kcen | 11.6 ± 0.6 | 10.5 | 14.2 | 3.43 ± 0.55 |
| kcen | input-lanjian | 19.8 ± 0.7 | 18.6 | 22.8 | 5.83 ± 0.92 |
| kcen | input-kcen | 20.9 ± 0.5 | 20.0 | 24.2 | 6.16 ± 0.96 |
| kcen | input-mattcl | 21.2 ± 0.8 | 20.1 | 24.8 | 6.25 ± 0.99 |
| mattcl-py | input-lanjian | 64.5 ± 1.3 | 62.6 | 68.7 | 19.00 ± 2.94 |
| mattcl-py | input-kcen | 70.8 ± 1.2 | 68.4 | 73.3 | 20.86 ± 3.22 |
| mattcl-py | input-mattcl | 70.9 ± 1.7 | 68.5 | 77.8 | 20.89 ± 3.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>194782</pre>|<pre>233007586663131</pre>|
|input-lanjian|<pre>218956</pre>|<pre>259593838049805</pre>|
|input-mattcl|<pre>189547</pre>|<pre>224577979481346</pre>|