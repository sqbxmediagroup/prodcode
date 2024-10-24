
# ProdCode V3 Specification

ProdCode is SQBX's production coding system for media projects.

V3 is the current working version of ProdCode.
## ProdCode Allocation

A 'ProdCode' is issued to each individual project.

This includes:

* Single Series
* Standalone Projects

For projects that have multiple series, each individual series will have its own unique ProdCode allocated.
## Code Format

`AA00-XYZ`

The core 'ProdCode' is comprised of:

* `AA`: Production Company or Client Prefix
* `00`: Year of Registration, Production, or Release
* `XYZ`: Unique Production Reference

### Production Company Prefix

**The "Production Company" prefix incidates the registered company that is taking ownership of the production. It must be 2 uppercase alphabetic characters, A-Z.**

Production Companies can hold multiple prefixes with SQBX, and are often used to separate by brand, or to allow for more codes.

For example, Company A can own the prefixes `AA` and `AB`.

In the event of a co-production, the main production company's prefix should be used. Otherwise, a new company can be registered for that specific production with a new prefix.

### Production Year

**The "Production Year" can refer to the project's registration, production, or release year. It must be 2 numeric characters, 0-9.**

For example, for the year 2024, the value used would be `24`.

The preference is to use the 'registration year', that is the year the project is entered into the project management system.

However, if a project has a set production or release year, it may be more appropriate to use that value.

### Production Reference

**The "Production Reference" is a quick way of identifying the project. It must be three characters.**

The reference is not unique, but it cannot be re-used by the same production company (across all registered prefixes) within the same 2 years.

For example, `AA23-XYZ` and `AA24-XYZ` is not permitted, but `AA23-XYZ` and `AA25-XYZ` is acceptable, where `XYZ` is the reference.

There are three patterns that the reference can use:

* `XYZ`: Three alphabetic characters (most common)
* `A00`: One alphabetic character followed by two numeric characters
* `AA0`: Two alphabetic characters followed by one numeric character

The reference must follow one of the patterns above and cannot start with a numeric character.
## Nesting

For related projects, the media/project management system should allow for nesting and linking.

The main way to do this is by setting a 'parent project'.

You can either register a new, blank project; or, you can link one project to another directly.

This system of nesting will only allow for one step, so you cannot create a chain of links. However, many projects can have the same parent project.

This is particularly useful for creating spin-off projects or linking different series of the same production.
## Expanded ProdCode
