The partialConf.h is used to avoid errors while handling non boolean variables. The following sources may help to create
a useful partialConf.h.
* https://github.com/ckaestne/TypeChef-LinuxAnalysis2/blob/master/data/partialConf.h should be used as basis
* http://elixir.free-electrons.com/ helps in locating macro definitions and usage


The partialConf.h needs only configuration values for variables from the variability model, e.g., CONFIG_<name>. Other
elements should be dependent of the variability variables and, thus, not require a specific configuration.