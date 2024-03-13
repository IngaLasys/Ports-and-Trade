# Domestically Significant Ports

Now you have one large data set with all information about the different ports.

We have also established the biggest ports with global significance by considering the amount of vessels handled. While we can imagine that if any of these globally significant ports experience a disruption, it would affect trade globally, what about the smaller ports? We could come up with the hypothesis, that if a small country has only few ports, or only one port, it must be quite dependent on this port.

In the following we would like to define domestically significant ports. Researchers who publish and maintain the "PortWatch" data we use define domestically significant ports as the ones that cumulatively handle more than 80% of a country's imports. Using variables from the large data set, define a dummy variable, where dummy=1 means that the port is a domestically significant port.

How many domestically significant ports did you detect (show your code)? How many are not domestically significant? Don't forget to explain your thought process and extensively comment your code.

> <img src="../.gitbook/assets/R.png" alt="" data-size="line"> \
> Again, use `dplyr`, `mutate()` should do the job. You could count obeservations using `nrwo()`.

> <img src="../.gitbook/assets/p.png" alt="" data-size="line">\
> @python please add
