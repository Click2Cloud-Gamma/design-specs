# Title

**Author(s)**: [Click2Cloud](https://github.com/Click2Cloud)

## Summary

In Gelato Project of OpenSDS, user can migrate its data from any on-premise or cloud's object storage to any on-premise or cloud provider's object storage. Current version of OpenSDS does not have support for controlling ongoing or upcoming migration like pause, resume, abort migration job. So in this design-spec, we will discuss about those features to manage migration job smooothly.

## Motivation

During migration, due to network issue or any technical reason if user wants to put the migration job on hold and resume it later, currently OpenSDS do not have option for the same. So adding features like Pause, Resume and Abort migration will allow user to manage migration job smoothly 

### Goals

1. Add Pause operation for migration job
2. Add Resume Operation for migration job

### Non-Goals

Use of Redis or TiDB 

## Design Details

Description of the proposed solution.

### Data model impact

Does the proposal affect data model?

### REST API impact

Does the proposal affect API?

### Security impact

Does it affect security?

### Other end user impact

Other than API, are there other changes that affect a user? For example the CLI changes.

### Performance impact

Is there any performance impact?

### Other deployer impact

How does it affect the deployment? Are there config option changes?

### Developer impact

Does this affect other developers?

## Use Cases

List use cases for the proposal.

## Implementation

Describe how the feature will be implemented. This can be a list of work items.

## Alternatives considered

Describe alternative solutions to be considered.

## Open issues

Describe some open issues to be considered.
