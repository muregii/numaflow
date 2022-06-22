# NumaFlow

[![Go Report Card](https://goreportcard.com/badge/github.com/numaproj/numaflow)](https://goreportcard.com/report/github.com/numaproj/numaflow)
[![GoDoc](https://godoc.org/github.com/numaproj/numaflow?status.svg)](https://godoc.org/github.com/numaproj/numaflow/pkg/apis)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Release Version](https://img.shields.io/github/v/release/numaproj/numaflow?label=numaflow)](https://github.com/numaproj/numaflow/releases/latest)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/6078/badge)](https://bestpractices.coreinfrastructure.org/projects/6078)

## Summary

NumaFlow is a Kubernetes-native platform for running massive parallel data processing and streaming jobs.

A NumaFlow Pipeline is implemented as a Kubernetes custom resource, and consists of one or more source, data processing, and sink vertices.

NumaFlow installs in less than a minute and is easier and cheaper for simple data processing applications than full-featured stream processing platforms.

## Key Features

- Kubernetes-native: If you know Kubernetes, you already know 90% of what you need to use NumaFlow.
- Language agnostic: Use your favorite programming language.
- Exactly-Once semantics: No input element is duplicated or lost even as pods are rescheduled or restarted.

## Roadmap

- Auto-scaling with back-pressure: Each vertex automatically scales from zero to whatever is needed.
- Data aggregation (e.g. group-by)

## Resources

- [QUICK_START](docs/QUICK_START.md)
- [EXAMPLES](examples)
- [DEVELOPMENT](docs/DEVELOPMENT.md)
- [CONTRIBUTING](https://github.com/numaproj/numaproj/blob/main/CONTRIBUTING.md)
