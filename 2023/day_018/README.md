# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 939.4 ± 198.8 | 221.6 | 1650.2 | 1.00 |
| mattcl | input-kcen | 956.6 ± 198.1 | 223.7 | 1198.7 | 1.02 ± 0.30 |
| lanjian | input-lanjian | 956.9 ± 136.9 | 217.1 | 1117.8 | 1.02 ± 0.26 |
| lanjian | input-kcen | 969.1 ± 145.9 | 380.9 | 1182.7 | 1.03 ± 0.27 |
| lanjian | input-mattcl | 971.3 ± 148.3 | 239.1 | 1150.4 | 1.03 ± 0.27 |
| lanjian | input-pting | 973.3 ± 128.6 | 212.6 | 1364.0 | 1.04 ± 0.26 |
| mattcl | input-mattcl | 995.9 ± 171.3 | 260.5 | 1709.2 | 1.06 ± 0.29 |
| mattcl | input-lanjian | 1029.9 ± 146.4 | 324.6 | 1405.3 | 1.10 ± 0.28 |
| mattcl-py | input-pting | 14355.6 ± 615.3 | 13369.7 | 17208.2 | 15.28 ± 3.30 |
| mattcl-py | input-lanjian | 14439.0 ± 535.5 | 13440.3 | 18275.5 | 15.37 ± 3.30 |
| pting | input-pting | 14660.1 ± 744.9 | 13425.7 | 17624.8 | 15.61 ± 3.40 |
| mattcl-py | input-mattcl | 14801.5 ± 603.7 | 13749.6 | 18314.2 | 15.76 ± 3.40 |
| mattcl-py | input-kcen | 14833.1 ± 740.5 | 13651.8 | 18064.6 | 15.79 ± 3.43 |
| pting | input-lanjian | 14887.4 ± 1004.0 | 13731.4 | 18582.6 | 15.85 ± 3.52 |
| pting | input-mattcl | 15080.5 ± 569.5 | 13861.2 | 17899.3 | 16.05 ± 3.45 |
| pting | input-kcen | 15115.9 ± 674.0 | 14072.0 | 18219.1 | 16.09 ± 3.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|