# Scaffold for The Composable Architecure 

## Motivation

[The Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture) is opinionated; there's a certain way to do things (with some wriggle room obviously).

With this in mind, a simple scaffolding tool for quickly generating stubs of features (e.g. Reducers and Views) might be useful.

At a minimum, this helper would allow you to quickly create the stubs of a feature or features, with the usual boilerplate/conformance in the View and Reducer stubs.

## Implementation

It's highly desirable that the template files that generate the stubs are tweakable by the user.

The scaffold could be a standalone tool, or perhaps just template files for some existing templating tool. Convenience is the main aim.

## A pause for thought

It's worth bearing in mind that the tool should be kept up to date with changes to TCA and not spread around deprecated or bad patterns of use.
