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
| whyando | input-lanjian | 530.1 ± 208.9 | 0.0 | 1006.3 | 1.00 |
| mattcl | input-lanjian | 557.2 ± 167.1 | 0.0 | 1128.4 | 1.05 ± 0.52 |
| mattcl | input-mattcl | 559.8 ± 150.0 | 0.0 | 1042.4 | 1.06 ± 0.50 |
| whyando | input-whyando | 572.3 ± 166.5 | 0.0 | 987.1 | 1.08 ± 0.53 |
| whyando | input-mattcl | 575.0 ± 134.6 | 14.2 | 945.0 | 1.08 ± 0.50 |
| mattcl | input-whyando | 630.8 ± 189.4 | 0.0 | 1352.0 | 1.19 ± 0.59 |
| kcen | input-lanjian | 940.3 ± 154.5 | 384.7 | 1540.9 | 1.77 ± 0.76 |
| kcen | input-whyando | 950.1 ± 133.2 | 464.5 | 1432.6 | 1.79 ± 0.75 |
| kcen | input-mattcl | 970.0 ± 146.5 | 57.5 | 1675.4 | 1.83 ± 0.77 |
| lanjian | input-mattcl | 8614.1 ± 70.6 | 8369.2 | 8799.6 | 16.25 ± 6.41 |
| lanjian | input-whyando | 8616.0 ± 76.6 | 8364.6 | 8902.5 | 16.25 ± 6.41 |
| lanjian | input-lanjian | 8623.2 ± 102.2 | 8429.5 | 9730.0 | 16.27 ± 6.41 |
| mattcl-py | input-lanjian | 21299.6 ± 660.3 | 20026.9 | 24522.5 | 40.18 ± 15.88 |
| mattcl-py | input-mattcl | 21303.3 ± 685.0 | 20107.6 | 24133.6 | 40.18 ± 15.89 |
| mattcl-py | input-whyando | 21329.7 ± 569.8 | 20424.2 | 24402.5 | 40.23 ± 15.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17493</pre>|<pre>173685428989126</pre>|
|input-mattcl|<pre>17179</pre>|<pre>170025781683941</pre>|
|input-whyando|<pre>17087</pre>|<pre>169019504359949</pre>|