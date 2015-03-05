# Storage Specs

A place for open discussion around container storage interfaces.

# Goal

Establish a common vendor neutral storage interface for use by container
orchestration and runtime environments.


## History

As container orchestration matures and grows, storage interfaces for managing
the state of containers must grow along with it. The ecosystem’s current
trajectory will likely lead towards a disparate plethora of implementations,
each with their own interface, runtime driver, and orchestration driver.

# Design Considerations

* This interface should allow orchestration and runtime layers to state “what”
  need a container needs, not “how” it will be accomplished. Please keep this
  heuristic in mind while contributing.

## How to Contribute

1. Join our mailing list and participate in our discussions around topics such
as interface design, use cases and shortcomings. (Link coming soon)
2. Submit pull requests to this repository suggesting modifications to the
spec. Please also add supporting comments to the pull request.
