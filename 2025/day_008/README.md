# Day 8 benchmarks

[link to problem](https://adventofcode.com/2025/day/8)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 8)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 2.6 ± 0.2 | 1.8 | 3.9 | 1.00 |
| mattcl | input-mattcl | 2.6 ± 0.3 | 1.8 | 4.9 | 1.01 ± 0.14 |
| mattcl | input-whyando | 2.6 ± 0.3 | 1.6 | 4.5 | 1.01 ± 0.13 |
| whyando | input-mattcl | 7.2 ± 0.5 | 6.0 | 10.2 | 2.81 ± 0.31 |
| whyando | input-whyando | 7.3 ± 0.6 | 6.0 | 10.5 | 2.83 ± 0.32 |
| whyando | input-lanjian | 7.3 ± 0.5 | 6.0 | 9.7 | 2.83 ± 0.31 |
| lanjian | input-whyando | 14.6 ± 0.5 | 13.6 | 18.0 | 5.65 ± 0.52 |
| lanjian | input-lanjian | 14.6 ± 0.4 | 13.7 | 16.0 | 5.65 ± 0.50 |
| lanjian | input-mattcl | 14.6 ± 0.6 | 13.6 | 17.4 | 5.66 ± 0.54 |
| kcen | input-lanjian | 56.6 ± 1.2 | 54.8 | 59.4 | 21.93 ± 1.91 |
| kcen | input-mattcl | 56.7 ± 1.0 | 55.3 | 59.1 | 21.98 ± 1.90 |
| kcen | input-whyando | 56.8 ± 1.0 | 54.8 | 59.3 | 22.01 ± 1.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>97384</pre>|<pre>9003685096</pre>|
|input-mattcl|<pre>47040</pre>|<pre>4884971896</pre>|
|input-whyando|<pre>352584</pre>|<pre>9617397716</pre>|