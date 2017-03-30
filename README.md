Jiles-Artherton parameter extract
=================================

### Prerequisites

* Matlab
* Simscape
* elec_inductor_hysteresis Model


### How to use 

This tool is very user unfriendly 

```
sp = 1; % starting index for logging
```

init parameters in order 

% dBdH0  % Anhysteretic B-H gradient when H is zero
% B1     % Flux density point on anhysteretic B-H curve
% H1     % Corresponding field strength
% c      % Coefficient for reversible magnetization, c
% K      % Bulk coupling coefficient, K
% alpha  % Inter-domain coupling factor
% error  % 

This here is a good fit for AlNiCo 5
```
a(1,:)= [4.76258753832144e-05 1.08137459383704 31510.3190144165 0.125292584870499 83177.9056903517 0.0622798260003811 11.9530626244814];
```


Run

### Notes

* This does like to get stuck at local minimas sometimes
* Extract reference BH loops using grabit.m
* It can take a long time to find a good fit if your initial parameters are too far of

## Licenses

TODO
