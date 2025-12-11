# Day 3 benchmarks

[link to problem](https://adventofcode.com/2025/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-lanjian | 559.4 ± 177.4 | 0.0 | 1183.1 | 1.00 |
| whyando | input-whyando | 560.7 ± 202.3 | 0.0 | 962.3 | 1.00 ± 0.48 |
| mattcl | input-mattcl | 568.5 ± 170.6 | 0.0 | 971.7 | 1.02 ± 0.44 |
| mattcl | input-whyando | 603.2 ± 154.2 | 0.0 | 1439.5 | 1.08 ± 0.44 |
| whyando | input-mattcl | 610.4 ± 129.2 | 144.7 | 1045.0 | 1.09 ± 0.42 |
| mattcl | input-lanjian | 615.8 ± 164.9 | 0.0 | 1320.8 | 1.10 ± 0.46 |
| kcen | input-mattcl | 948.7 ± 136.1 | 0.0 | 1551.4 | 1.70 ± 0.59 |
| kcen | input-whyando | 952.7 ± 153.2 | 357.7 | 1617.3 | 1.70 ± 0.61 |
| kcen | input-lanjian | 989.8 ± 193.6 | 422.3 | 1563.5 | 1.77 ± 0.66 |
| lanjian | input-lanjian | 4109.6 ± 291.1 | 3437.4 | 5104.4 | 7.35 ± 2.39 |
| lanjian | input-mattcl | 4137.6 ± 335.8 | 3341.3 | 5052.5 | 7.40 ± 2.42 |
| lanjian | input-whyando | 4141.0 ± 278.9 | 3449.6 | 4979.1 | 7.40 ± 2.40 |
| mattcl-py | input-mattcl | 21165.8 ± 605.5 | 19986.0 | 23772.2 | 37.84 ± 12.04 |
| mattcl-py | input-lanjian | 21314.4 ± 631.9 | 20255.1 | 24250.8 | 38.10 ± 12.13 |
| mattcl-py | input-whyando | 21400.0 ± 725.1 | 20461.0 | 24549.2 | 38.25 ± 12.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|