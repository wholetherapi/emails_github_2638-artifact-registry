# Reference Implementation Registry

This registry records the release state of reference implementations for platform components.

Each component has a folder under `artifacts/<component_id>/` with a `STATUS.md` record. Only records whose `release_state` is `published` are linkable from the component catalog; `draft` records (including stubs marked "to be released") are not linkable.
