# Protobuf Files for Chemios

This is a central repository for [protobuf files]() for chemios.  Protobuf is a remote procedural call framework created by Google. In the framework, a `.proto` file defines a standard interface for a client-server interaction. 

By having all the `.proto` files in a central repository, we ensure that all drivers and the main chemios repo are using the same interface definition.

# Submodules

The best way to use the proto files during development is git submodules.  A submodules is a git repository inside a repository. You can install this repository as a submodules inside yours.  You can then sync the submodule to the central repository to make sure it is up to date. 