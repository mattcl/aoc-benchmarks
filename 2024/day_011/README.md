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
| mattcl | input-lanjian | 3.4 ± 0.4 | 2.5 | 6.7 | 1.00 |
| mattcl | input-kcen | 3.6 ± 0.5 | 2.6 | 7.0 | 1.07 ± 0.20 |
| mattcl | input-mattcl | 3.6 ± 0.4 | 2.6 | 4.8 | 1.07 ± 0.18 |
| lanjian | input-lanjian | 11.0 ± 0.4 | 10.3 | 13.9 | 3.26 ± 0.44 |
| lanjian | input-kcen | 11.3 ± 0.6 | 10.4 | 14.3 | 3.35 ± 0.46 |
| lanjian | input-mattcl | 11.6 ± 0.6 | 10.8 | 14.8 | 3.42 ± 0.47 |
| kcen | input-lanjian | 19.6 ± 0.6 | 18.5 | 22.2 | 5.79 ± 0.76 |
| kcen | input-mattcl | 20.8 ± 0.6 | 20.0 | 24.0 | 6.15 ± 0.81 |
| kcen | input-kcen | 20.9 ± 0.8 | 19.8 | 23.7 | 6.17 ± 0.82 |
| mattcl-py | input-lanjian | 63.3 ± 1.2 | 61.3 | 65.9 | 18.70 ± 2.42 |
| mattcl-py | input-kcen | 69.4 ± 1.4 | 67.1 | 72.4 | 20.50 ± 2.65 |
| mattcl-py | input-mattcl | 70.0 ± 1.7 | 67.4 | 75.2 | 20.67 ± 2.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>194782</pre>|<pre>233007586663131</pre>|
|input-lanjian|<pre>218956</pre>|<pre>259593838049805</pre>|
|input-mattcl|<pre>189547</pre>|<pre>224577979481346</pre>|