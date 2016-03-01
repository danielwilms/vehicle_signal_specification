(C) 2016 Jaguar Land Rover - All rights reserved.

All documents in this repository are available under the Creative
Commons Attribution 4.0 International (CC BY 4.0).

Click [here](https://creativecommons.org/licenses/by/4.0/) for
details.

All code in this repository is available under Mozilla Public License
v2 (MPLv2).

Click [here](https://www.mozilla.org/en-US/MPL/2.0/) for details.

# VEHICLE SIGNAL SPECIFICATION
This repository specifies a set of vehicle signals that can be used in
automotive applications to communicate the state of various vehicle
systems.

The collection of signal specifications, or simply signals, are vendor
independent. Vendor-specific extensions can be specified in a dediceated and
uncontrolled branch of the signal specification tree. 

The format of the directories and signal specification files is aimed
at allowing easy, git-based management with branching, merging, and
release.

A released signal specification can be used, together with tools in
this repository, to automatically generate a number of different
target specification formats, such as JSON, FrancaIDL, etc.

The release management process will be driven in the context of GENIVI
and its Remote Vehicle Interaction expert group.

# SIGNAL DEFINITION

A signal is a named entity, such as rpm, that at any time can have a
value, such as 3400.

Signals are organized into a tree such as outlined below.

![Signal tree](https://github.com/PDXostc/vehicle_signal_interface/raw/master/pics/tree.png)


Signal naming convention

Node vs. tree
What constitutes a signal
Setter vs. Current signals
Interval



# SIGNAL SPECIFICATION FORMAT

## ENTRY

## FILE

## INCLUDE DIRECTIVES

# TOOLS

# SPECIFICATION VERSIONING

## BRANCHING
## RELEASES
